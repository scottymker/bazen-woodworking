# Bazen Woodworking — Jekyll Site

This repository hosts the static marketing site for Bazen Woodworking, built with Jekyll and Tailwind CSS (via CDN) for deployment on GitHub Pages.

## Local development

1. Install dependencies:
   ```bash
   bundle install
   ```
2. Run the development server with live reload:
   ```bash
   bundle exec jekyll serve
   ```
3. Visit `http://127.0.0.1:4000` to preview the site.

## Deploy on GitHub Pages

1. Push the `main` branch to GitHub.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`, then save.
5. GitHub Pages will build and publish the site automatically.

## DNS configuration

1. Set a CNAME record pointing `www.bazenwoodworkingllc.com` to `<username>.github.io`.
2. Add apex A records for `bazenwoodworkingllc.com` using the [GitHub Pages IPs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/about-custom-domains-and-github-pages#configuring-an-apex-domain).
3. In the GitHub repository, add both hostnames to the `CNAME` file (already included here).

## Content updates

- **Formspree:** The production endpoint is already wired in `_includes/contact-form.html` — no updates needed unless the ID changes.
- **Images:** Swap photography inside `assets/img/` (hero, gallery, process, and about-page image) with your preferred shots. Update filenames or references in the HTML pages if you change them.
- **SEO:** Update page descriptions or Open Graph images via front matter (`description` and `image`).

All content pages (`index.html`, `latest-projects.html`, `about-steve.html`, `contact.html`, and `faq.html`) are straight HTML with Tailwind utility classes so you can edit copy directly without Markdown.

All content pages live at the root level to keep clean permalinks required by the existing Wix site.

---
title: Home
description: Bazen Woodworking crafts custom cabinets and built-ins for homes across southeastern South Dakota with precise fit, premium materials, and hands-on service.
permalink: /
---

<section class="relative bg-slate-900">
  <img src="{{ '/assets/img/hero-shop.jpg' | relative_url }}" alt="Custom cabinetry workshop with freshly built cabinet frames" class="h-80 w-full object-cover opacity-70 md:h-96">
  <div class="absolute inset-0 bg-gradient-to-r from-slate-900/80 via-slate-900/70 to-transparent"></div>
  <div class="absolute inset-0 flex items-center">
    <div class="mx-auto flex max-w-content flex-col gap-6 px-6 py-12 text-white">
      <p class="text-sm uppercase tracking-[0.3em] text-brand-200">Bazen Woodworking</p>
      <h1 class="max-w-xl text-3xl font-semibold sm:text-4xl md:text-5xl">Custom Cabinets, Built Locally</h1>
      <p class="max-w-xl text-base text-slate-200 md:text-lg">
        From first measurements to the final install, we design and build cabinets that match your space, timeline, and everyday life.
      </p>
      <div class="flex flex-wrap gap-3">
        <a href="{{ '/contact/' | relative_url }}#contact-form" class="inline-flex items-center rounded-md bg-brand-500 px-5 py-3 text-sm font-semibold text-white shadow-lg transition hover:bg-brand-400 focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-brand-300">Request a Quote</a>
        <a href="{{ '/latest-projects/' | relative_url }}" class="inline-flex items-center rounded-md border border-white/70 px-5 py-3 text-sm font-semibold text-white transition hover:border-white hover:bg-white/10 focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-brand-300">See Latest Projects</a>
      </div>
    </div>
  </div>
</section>

<section class="mx-auto max-w-content px-6 py-16">
  <div class="grid gap-10 md:grid-cols-5 md:items-center">
    <div class="md:col-span-3">
      <h2 class="text-2xl font-semibold md:text-3xl">Cabinetry designed for the way you live</h2>
      <p class="mt-4 text-base text-slate-600">
        Every project starts with listening. We measure, plan, build, and install in-house so the fit is precise and the finish lasts. Expect honest timelines, transparent pricing, and a crew that respects your home.
      </p>
    </div>
    <div class="md:col-span-2 rounded-xl bg-white p-6 shadow ring-1 ring-slate-200">
      <h3 class="text-lg font-semibold text-slate-900">Let’s get started</h3>
      <p class="mt-3 text-sm text-slate-600">
        Call <a href="tel:+16055533304" class="font-medium text-brand-600 hover:underline focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-brand-400">(605) 553-3304</a> or email
        <a href="mailto:bazensteve@gmail.com" class="font-medium text-brand-600 hover:underline focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-brand-400">bazensteve@gmail.com</a>.
      </p>
    </div>
  </div>
</section>

<section class="bg-white py-16">
  <div class="mx-auto max-w-content px-6">
    <h2 class="text-2xl font-semibold md:text-3xl">What we build</h2>
    <p class="mt-3 max-w-2xl text-base text-slate-600">
      From one-room refreshes to whole-home cabinetry packages, we’re hands-on through every step—measure, design, build, finish, and install.
    </p>
    <div class="mt-10 grid gap-6 sm:grid-cols-2 lg:grid-cols-3">
      <article class="flex h-full flex-col rounded-xl border border-slate-200 bg-slate-50 p-6 shadow-sm">
        <h3 class="text-lg font-semibold text-slate-900">Kitchens &amp; pantries</h3>
        <p class="mt-3 text-sm text-slate-600">
          Custom layouts, premium hardware, and durable finishes that stand up to daily cooking, gathering, and celebrating.
        </p>
      </article>
      <article class="flex h-full flex-col rounded-xl border border-slate-200 bg-slate-50 p-6 shadow-sm">
        <h3 class="text-lg font-semibold text-slate-900">Mudrooms &amp; built-ins</h3>
        <p class="mt-3 text-sm text-slate-600">
          Lockers, benches, fireplace surrounds, and storage walls tailored to keep every inch of your home organized.
        </p>
      </article>
      <article class="flex h-full flex-col rounded-xl border border-slate-200 bg-slate-50 p-6 shadow-sm">
        <h3 class="text-lg font-semibold text-slate-900">Bathrooms &amp; laundry</h3>
        <p class="mt-3 text-sm text-slate-600">
          Vanities, linen towers, and laundry systems built to handle moisture, maximize storage, and stay beautiful.
        </p>
      </article>
    </div>
  </div>
</section>

<section class="mx-auto max-w-content px-6 py-16">
  <div class="grid gap-10 lg:grid-cols-2">
    <img src="{{ '/assets/img/project-cabinet-1.jpg' | relative_url }}" alt="Custom kitchen cabinets with shaker doors and quartz countertops" class="h-72 w-full rounded-2xl object-cover shadow-lg">
    <div class="flex flex-col justify-center">
      <span class="text-sm uppercase tracking-[0.3em] text-brand-500">Our Process</span>
      <h2 class="mt-4 text-2xl font-semibold text-slate-900 md:text-3xl">Measure → Design → Build → Install</h2>
      <p class="mt-4 text-base text-slate-600">
        Steve Bazen leads every project personally. We collaborate with your designer or bring ours, produce precise shop drawings, and build in our Corsica shop before delivering a clean install.
      </p>
      <div class="mt-6">
        <a href="{{ '/about-steve/' | relative_url }}" class="inline-flex items-center rounded-md border border-brand-500 px-4 py-2 text-sm font-semibold text-brand-600 transition hover:bg-brand-50 focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-brand-400">
          Meet Steve
        </a>
      </div>
    </div>
  </div>
</section>

{% include contact-form.html %}

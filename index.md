---
# ─────────────────────────────────────────────
# Home / Landing Page  ·  MVeng
# Layout "page" renders with the Chirpy sidebar
# but WITHOUT the post-feed pagination loop.
# ─────────────────────────────────────────────
layout: page
title: Home
permalink: /
icon: fas fa-house
order: 1
# Disable breadcrumb and ToC on the landing page
toc: false
---

<!-- ════════════════════════════════════════════
     HERO
════════════════════════════════════════════ -->
<section class="mv-hero text-center py-5">
  <h1 class="display-5 fw-bold">
    45+ Years of&nbsp;<span class="text-primary">Software &amp; Systems Engineering</span>
  </h1>
  <p class="lead mt-3 mb-4 mx-auto" style="max-width:680px;">
    From PCB layout to embedded RTOS work to enterprise UNIX and Windows
    applications — decades of hands-on engineering at a single defense
    contractor, now available for consulting and part-time work as I
    ease into semi-retirement.
  </p>
  <div class="d-flex flex-wrap justify-content-center gap-3">
    <a href="#expertise" class="btn btn-primary btn-lg px-4">
      <i class="fas fa-cogs me-2"></i>What I Do
    </a>
    <a href="#contact" class="btn btn-outline-secondary btn-lg px-4">
      <i class="fas fa-envelope me-2"></i>Get in Touch
    </a>
  </div>
</section>

<hr class="my-5">

<!-- ════════════════════════════════════════════
     BACKGROUND
════════════════════════════════════════════ -->
<section id="about" class="mb-5" markdown="1">

## Background

I spent 45+ years at the same small defense contractor — starting as a
design draftsman, moving into PCB layout, and by the early 1980s landing
in software engineering (how that happened is probably its own blog
post).

As a software engineer, I supported a multi-user application written in
C running on a variant of BSD UNIX — everything from ongoing development
to installations to end-user training. That meant a lot of domestic and
international travel early in my career.

That application evolved right along with the hardware: from
minicomputers, to Sun workstations, to Windows in the early 2000s. It
gave me a solid grounding in C/C++ and application development across
both UNIX/Linux and Windows environments. Along the way I also worked on
embedded systems built on RTOSes like VxWorks, RT-Kernel, and FreeRTOS,
as well as bare-metal microcontroller systems.

Somewhere in there I started consulting for other companies on the side
— that's where MVeng got its start, and it's the base I'm building on now.

<div class="row g-4 mt-3">
  <div class="col-md-4">
    <div class="card h-100 border-0 shadow-sm text-center">
      <i class="fas fa-code fa-2x text-primary mb-3"></i>
      <h5 class="fw-semibold">45+ Years, One Thread</h5>
      <p class="small text-muted">From design draftsman to PCB layout to software engineer — continuous, hands-on engineering at one company.</p>
    </div>
  </div>
  <div class="col-md-4">
    <div class="card h-100 border-0 shadow-sm text-center">
      <i class="fas fa-server fa-2x text-primary mb-3"></i>
      <h5 class="fw-semibold">Minicomputers to Windows</h5>
      <p class="small text-muted">C/C++ application development spanning minicomputer, Sun/UNIX, Linux, and Windows platforms.</p>
    </div>
  </div>
  <div class="col-md-4">
    <div class="card h-100 border-0 shadow-sm text-center">
      <i class="fas fa-microchip fa-2x text-primary mb-3"></i>
      <h5 class="fw-semibold">Embedded &amp; Bare Metal</h5>
      <p class="small text-muted">RTOS work with VxWorks, RT-Kernel, and FreeRTOS, plus bare-metal microcontroller systems.</p>
    </div>
  </div>
</div>

</section>

<hr class="my-5">

<!-- ════════════════════════════════════════════
     WHERE I AM NOW
════════════════════════════════════════════ -->
<section id="now" class="mb-5" markdown="1">

## Where I Am Now

I'm about three years past what would've been a traditional retirement
date and easing into semi-retirement. I'll keep working part-time with
my current company and taking on consulting engagements — this site is
home base for that next chapter.

</section>

<hr class="my-5">

<!-- ════════════════════════════════════════════
     EXPERTISE
════════════════════════════════════════════ -->
<section id="expertise" class="mb-5" markdown="1">

## Areas of Expertise

<div class="row g-4 mt-2">

  <div class="col-sm-6 col-lg-4">
    <div class="card h-100 border-0 shadow-sm">
      <div class="d-flex align-items-center mb-2">
        <i class="fas fa-code text-primary me-3 fa-lg"></i>
        <h5 class="fw-semibold mb-0">Software Development (C/C++)</h5>
      </div>
      <p class="small text-muted mb-2">
        Decades of hands-on development and maintenance of a multi-user C application.
      </p>
      <ul class="small text-muted ps-3 mb-0">
        <li>Multi-user application development</li>
        <li>UNIX/Linux and Windows platforms</li>
        <li>Long-term maintenance &amp; modernization</li>
      </ul>
    </div>
  </div>

  <div class="col-sm-6 col-lg-4">
    <div class="card h-100 border-0 shadow-sm">
      <div class="d-flex align-items-center mb-2">
        <i class="fas fa-microchip text-primary me-3 fa-lg"></i>
        <h5 class="fw-semibold mb-0">Embedded Systems &amp; RTOS</h5>
      </div>
      <p class="small text-muted mb-2">
        Embedded development across multiple real-time operating systems and bare metal.
      </p>
      <ul class="small text-muted ps-3 mb-0">
        <li>VxWorks, RT-Kernel, FreeRTOS</li>
        <li>Bare-metal microcontroller systems</li>
        <li>Hardware/software integration</li>
      </ul>
    </div>
  </div>

  <div class="col-sm-6 col-lg-4">
    <div class="card h-100 border-0 shadow-sm">
      <div class="d-flex align-items-center mb-2">
        <i class="fas fa-server text-primary me-3 fa-lg"></i>
        <h5 class="fw-semibold mb-0">UNIX/Linux &amp; Windows Platforms</h5>
      </div>
      <p class="small text-muted mb-2">
        Cross-platform application experience from minicomputer-era UNIX through modern Windows.
      </p>
      <ul class="small text-muted ps-3 mb-0">
        <li>BSD UNIX &amp; Linux</li>
        <li>Sun workstation to Windows migrations</li>
        <li>Platform ports &amp; re-architecture</li>
      </ul>
    </div>
  </div>

  <div class="col-sm-6 col-lg-4">
    <div class="card h-100 border-0 shadow-sm">
      <div class="d-flex align-items-center mb-2">
        <i class="fas fa-plane text-primary me-3 fa-lg"></i>
        <h5 class="fw-semibold mb-0">Installation, Support &amp; Training</h5>
      </div>
      <p class="small text-muted mb-2">
        On-site installation and end-user training, domestic and international.
      </p>
      <ul class="small text-muted ps-3 mb-0">
        <li>Field installations</li>
        <li>End-user &amp; operator training</li>
        <li>Ongoing customer support</li>
      </ul>
    </div>
  </div>

  <div class="col-sm-6 col-lg-4">
    <div class="card h-100 border-0 shadow-sm">
      <div class="d-flex align-items-center mb-2">
        <i class="fas fa-file-contract text-primary me-3 fa-lg"></i>
        <h5 class="fw-semibold mb-0">Technical Documentation</h5>
      </div>
      <p class="small text-muted mb-2">
        Documentation written for both technical and non-technical audiences.
      </p>
      <ul class="small text-muted ps-3 mb-0">
        <li>User manuals &amp; training materials</li>
        <li>Design &amp; maintenance documentation</li>
        <li>Process &amp; procedure write-ups</li>
      </ul>
    </div>
  </div>

  <div class="col-sm-6 col-lg-4">
    <div class="card h-100 border-0 shadow-sm">
      <div class="d-flex align-items-center mb-2">
        <i class="fas fa-handshake text-primary me-3 fa-lg"></i>
        <h5 class="fw-semibold mb-0">Contract &amp; Part-Time Engineering</h5>
      </div>
      <p class="small text-muted mb-2">
        Flexible consulting engagements as I transition into semi-retirement.
      </p>
      <ul class="small text-muted ps-3 mb-0">
        <li>Part-time &amp; contract work</li>
        <li>Legacy system support</li>
        <li>Independent technical review</li>
      </ul>
    </div>
  </div>

</div>
</section>

<hr class="my-5">

<!-- ════════════════════════════════════════════
     RECENT WRITING  (links to external blog)
════════════════════════════════════════════ -->
<section id="writing" class="mb-5" markdown="1">

## From the Blog

Write-ups on past projects I've been part of, hobby projects, RVing and
RV projects, and whatever else comes to mind — published on the MVeng blog.

<div class="d-flex flex-wrap gap-2 mt-3">
  <a href="https://mvaughn51.github.io/mvaughn51/" class="btn btn-sm btn-outline-primary" target="_blank" rel="noopener">
    <i class="fas fa-rss me-1"></i>Read All Posts
  </a>
  <a href="https://mvaughn51.github.io/mvaughn51/categories" class="btn btn-sm btn-outline-secondary" target="_blank" rel="noopener">
    <i class="fas fa-folder-open me-1"></i>Browse by Category
  </a>
  <a href="https://mvaughn51.github.io/mvaughn51/tags" class="btn btn-sm btn-outline-secondary" target="_blank" rel="noopener">
    <i class="fas fa-tags me-1"></i>Browse by Tag
  </a>
</div>

</section>

<hr class="my-5">

<!-- ════════════════════════════════════════════
     CALL TO ACTION / CONTACT
════════════════════════════════════════════ -->
<section id="contact" class="text-center py-4 mb-3" markdown="1">

## Interested in Working Together?

I'm easing into semi-retirement, splitting time between part-time work
at my current company and select consulting engagements. If you have a
legacy system that needs support, an embedded project that needs
real-world RTOS experience, or documentation and training needs, let's
talk.

<div class="d-flex flex-wrap justify-content-center gap-3 mt-4">
  <a href="mailto:mvaughn51@gmail.com" class="btn btn-primary btn-lg px-5">
    <i class="fas fa-paper-plane me-2"></i>Send a Message
  </a>
  <a href="https://mvaughn51.github.io/mvaughn51/" class="btn btn-outline-secondary btn-lg px-5" target="_blank" rel="noopener">
    <i class="fas fa-book-open me-2"></i>Read the Blog
  </a>
</div>

<p class="text-muted small mt-4">
  Typical response time: <strong>1–2 business days</strong>
</p>

</section>

<!-- ════════════════════════════════════════════
     CUSTOM STYLES  (scoped to landing page only)
     Chirpy injects page content inside .content,
     so these rules won't bleed into other pages.
════════════════════════════════════════════ -->
<style>
.mv-hero {
  padding-block: 3.5rem;
}
.card {
  padding: 1.5rem;
  transition: transform 0.18s ease, box-shadow 0.18s ease;
}
.card:hover {
  transform: translateY(-4px);
  box-shadow: 0 .5rem 1.5rem rgba(0,0,0,.12) !important;
}
</style>

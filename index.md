---
layout: evol
title: 'EVOL Lab — Software Evolution, UNLV'
description: 'The Software Evolution (EVOL) Lab at UNLV pioneers dependable software evolution through empirical software engineering and AI-assisted development. We study how software ecosystems evolve and create intelligent methods for understanding, adapting, and reusing software changes at scale.'
---

<main id="top">

  <!-- ================= HERO ================= -->
  <section class="hero">
    <div class="wrap">
      <div class="eyebrow">Software Evolution (EVOL) Lab· Dept. of Computer Science, UNLV</div>
      <div class="hero-grid">
        <div class="hero-copy">
          <h1>Understanding software evolution. Building the future of dependable software.</h1>
            <p class="lede">
            EVOL Lab advances empirical software engineering and AI-assisted software engineering at the University of Nevada, Las Vegas. We study how software systems evolve, develop intelligent methods for adapting reusable changes across long-lived software ecosystems, and build open tools, datasets, and benchmarks that enable reproducible research.
            </p>
          <div class="hero-ctas">
            <a class="btn btn-primary" href="#publications">Read our papers</a>
            <a class="btn btn-outline" href="join.html">Join the lab</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ================= ABOUT ================= -->
  <section id="about">
    <div class="wrap">
      <div class="section-head">
        <div>
          <div class="section-tag">about</div>
          <h2>Research Vision</h2>
        </div>
        <div class="section-note"></div>
      </div>
      <p class="lede-block">
        EVOL Lab advances <strong>dependable software evolution</strong> through empirical software engineering and AI-assisted software engineering. We investigate how software systems evolve, why reusable changes become difficult to transfer across independently evolving software variants, and how intelligent, evidence-driven methods can discover, adapt, verify, and integrate those changes safely at scale.
        </p>
      <div class="rq-grid">
        <div class="rq-card">
          <span class="rq-id">Research Theme 1</span>
          <h3>Understanding Software Evolution</h3>
          <p>We study software repositories at scale to understand how systems,
            variants, and developer communities change, diverge, collaborate, and
            accumulate maintenance challenges over time.</p>
        </div>
        <div class="rq-card">
          <span class="rq-id">Research Theme 2</span>
          <h3>Autonomous Reusable Change Adaptation</h3>
          <p>We develop methods to discover, adapt, verify, and integrate reusable
            fixes, enhancements, and capabilities across independently evolving
            software variants.</p>
        </div>
        <div class="rq-card">
          <span class="rq-id">Research Theme 3</span>
          <h3>AI-Assisted Software Engineering</h3>
          <p>We combine empirical evidence and large language models to build
    trustworthy developer tools that improve software quality while
    preserving human oversight.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- ================= NEWS ================= -->
  <section id="news">
    <div class="wrap">
      <div class="section-head">
        <div>
          <div class="section-tag">news</div>
          <h2>Recent news</h2>
        </div>
        <div class="section-note"></div>
      </div>
      {% include news-list.html limit=6 %}
      <div class="join-compact projects-cta" style="margin-top:18px;">
        <p>Browse the complete list of lab updates.</p>
        <a class="btn btn-primary" href="news.html">View all news</a>
      </div>
    </div>
  </section>

  <!-- ================= PEOPLE ================= -->
  <section id="people">
    <div class="wrap">
      <div class="section-head">
        <div>
          <div class="section-tag">people</div>
          <h2>Who's in the lab</h2>
        </div>
        <div class="section-note"></div>
      </div>

      <p class="people-subhead">Current team</p>
      {% include team-cards.html featured_only=true %}
    </div>
  </section>

  <!-- ================= PUBLICATIONS ================= -->
  <section id="publications">
    <div class="wrap">
      <div class="section-head">
        <div>
          <div class="section-tag">publications</div>
          <h2>Selected papers</h2>
        </div>
        <div class="section-note"></div>
      </div>
      {% include publication-list.html limit=6 %}
      <div class="join-compact projects-cta" style="margin-top:18px;">
        <p>See the full archive for the remaining publications.</p>
        <a class="btn btn-primary" href="publications.html">View all publications</a>
      </div>
    </div>
  </section>

  <!-- ================= PROJECTS ================= -->
  <section id="projects">
    <div class="wrap">
      <div class="section-head">
        <div>
          <div class="section-tag">projects</div>
          <h2>Selected projects</h2>
        </div>
        <div class="section-note"></div>
      </div>
      {% include project-cards.html featured_only=true %}
      <div class="projects-cta">
        <p>See all active and past EVOL Lab projects, outputs in one place.</p>
        <a class="btn btn-primary" href="projects/index.html">Browse all projects</a>
      </div>
    </div>
  </section>

</main>

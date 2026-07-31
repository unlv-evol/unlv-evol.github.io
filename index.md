---
layout: evol
title: 'EVOL Lab — Software Evolution, UNLV'
description: 'The Software Evolution (EVOL) Lab at UNLV is home to graduate researchers advancing empirical software engineering — studying how codebases, forks, and teams change over time.'
---

<main id="top">

  <!-- ================= HERO ================= -->
  <section class="hero">
    <div class="wrap">
      <div class="eyebrow">Software Evolution (EVOL) Lab· Dept. of Computer Science, UNLV</div>
      <div class="hero-grid">
        <div>
          <h1>We study how software changes, then measure it.</h1>
          <p class="lede">EVOL Lab is home to graduate researchers advancing empirical software engineering at UNLV. We run large-scale studies of how codebases, forks, and teams evolve over time, and build tools that put that evidence to work. Mixed methods, open data, reproducible pipelines.</p>
          <div class="hero-ctas">
            <a class="btn btn-primary" href="#publications">Read our papers</a>
            <a class="btn btn-outline" href="join.html">Join the lab</a>
          </div>
        </div>
        <div class="figure">
          <div class="chart" aria-hidden="true">
            <div class="bar-col"><div class="bar" style="height:38%;"></div><span class="lbl">RQ1</span></div>
            <div class="bar-col"><div class="bar hi" style="height:82%;"></div><span class="lbl">RQ2</span></div>
            <div class="bar-col"><div class="bar" style="height:54%;"></div><span class="lbl">RQ3</span></div>
            <div class="bar-col"><div class="bar hi" style="height:71%;"></div><span class="lbl">RQ4</span></div>
            <div class="bar-col"><div class="bar" style="height:29%;"></div><span class="lbl">RQ5</span></div>
          </div>
          <p class="figure-cap"><b>Fig. 1</b> — Effect size by research question across our last five studies (illustrative). Highlighted bars mark statistically significant, practically meaningful findings.</p>
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
          <h2>What we investigate</h2>
        </div>
        <div class="section-note"></div>
      </div>
      <p class="lede-block">EVOL Lab sits within <strong>empirical software engineering</strong>, with a focus on how systems, and the communities that build them, change over time. We treat engineering practice as a phenomenon to be measured, not assumed — mining repositories, running controlled experiments with developers, and building tools that put those findings back into practitioners' hands.</p>
      <div class="rq-grid">
        <div class="rq-card">
          <span class="rq-id">RQ1</span>
          <h3>When projects fork and diverge, what gets lost — and what should be shared back?</h3>
          <p>Studying variant forks and software families to understand why teams diverge, what maintenance work gets duplicated, and where automated tooling could close the gap.</p>
        </div>
        <div class="rq-card">
          <span class="rq-id">RQ2</span>
          <h3>What do code and commit histories reveal about how teams actually collaborate?</h3>
          <p>Large-scale mining of open-source and industrial repositories to model review dynamics, technical debt accumulation, and knowledge diffusion across contributors.</p>
        </div>
        <div class="rq-card">
          <span class="rq-id">RQ3</span>
          <h3>Can tooling recommend the right code, at the right moment, and help developers integrate it?</h3>
          <p>Building and evaluating code recommenders — for fixes, refactorings, and tests — that go beyond retrieval to support the harder step of integration.</p>
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

      <p class="people-subhead mt-44">Alumni</p>
      <div class="people-grid">
        <div class="person">
          <div class="avatar" style="background:var(--link);">MT</div>
          <div>
            <p class="person-name">Marcus Tran</p>
            <p class="person-role">PhD '25 → Postdoc, ETH Zürich</p>
            <p class="person-note">Now working on program repair.</p>
          </div>
        </div>
        <div class="person">
          <div class="avatar" style="background:var(--diff);">LH</div>
          <div>
            <p class="person-name">Lena Hoffmann</p>
            <p class="person-role">MS '24 → Software Engineer, Google</p>
            <p class="person-note">Thesis on ecosystem-scale fork analysis.</p>
          </div>
        </div>
        <div class="person">
          <div class="avatar" style="background:var(--link);">OA</div>
          <div>
            <p class="person-name">Omar Al-Sayed</p>
            <p class="person-role">MS '23 → PhD student, UC Irvine</p>
            <p class="person-note">Continuing work on code review dynamics.</p>
          </div>
        </div>
      </div>
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

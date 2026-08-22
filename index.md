---
layout: evol
title: 'EVOL Lab — Software Evolution, UNLV'
description: 'EVOL Lab at UNLV develops evidence-driven methods and open tools that help developers reuse valuable software changes and collaborate dependably with AI coding agents.'
---

<main id="top">

  <!-- ================= HERO ================= -->
  <section class="hero">
    <div class="wrap">
      <div class="eyebrow">Software Evolution (EVOL) Lab· Dept. of Computer Science, UNLV</div>
      <div class="hero-grid">
        <div class="hero-copy">
          <h1>Helping developers understand, adapt, and evaluate software change.</h1>
            <p class="lede">
            EVOL Lab develops evidence-driven methods and open source tools for dependable
            software evolution. We investigate how valuable improvements can move
            across related software systems and how developers can work more
            reliably with large language models and coding agents. Across both
            directions, our goal is to preserve developer intent, account for the
            surrounding software context, and provide evidence that supports
            decisions about whether a change should be integrated.
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
  <section id="research">
    <div class="wrap">
      <div class="section-head">
        <div>
          <div class="section-tag">research</div>
          <h2>Two paths to dependable software</h2>
        </div>
        <div class="section-note">Evidence. Automation. Human oversight.</div>
      </div>

      <p class="lede-block">
        Software changes do not succeed merely because code was copied, generated,
        or applied without producing an error. A dependable change must express
        the right intent, fit the structure and behavior of its destination, and
        be supported by evidence that developers can examine. We study this
        challenge in two closely connected settings.
      </p>

      <div class="join-panels">
        <article class="join-panel">
          <span class="rq-id">Research Direction 1</span>
          <h3>Dependable Reuse Across Related Systems</h3>
          <p>
            Organizations often create software by copying and customizing an
            existing system. As the related systems evolve independently, an
            important fix, security update, or functional improvement made in one
            may never reach the others. Finding a potentially useful change is
            only the beginning: developers must determine where it belongs, adapt
            it to a different structure and context, and evaluate whether it still
            accomplishes its intended purpose.
          </p>
          <p>
            We develop methods that help developers <strong>discover, prioritize,
            align, adapt, and verify</strong> reusable changes. This research builds
            on PaReco, GACPD, MOVis, RePatch, and our emerging semantic-alignment
            and reusable-change-adaptation infrastructure. It is supported in part
            by <a href="https://www.nsf.gov/awardsearch/show-award?AWD_ID=2542438"
            target="_blank" rel="noopener noreferrer">NSF CAREER Award
            #2542438</a>.
          </p>
        </article>

        <article class="join-panel">
          <span class="rq-id">Research Direction 2</span>
          <h3>Dependable Developer–LLM Collaboration</h3>
          <p>
            Developers increasingly use large language models and coding agents
            to generate and modify code. Yet a prompt may omit relevant files,
            constraints, expected behavior, or other information needed to
            understand the task. A response can therefore look convincing while
            misunderstanding the developer's intent or failing to fit the
            repository in which it will be used.
          </p>
          <p>
            We study how prompt context, specificity, and verification information
            influence real pull-request outcomes. Building on this empirical
            foundation, we are investigating tools that recover missing intent
            from surrounding software artifacts, provide coding agents with
            repository-grounded context, and use PatchGate to help developers
            evaluate generated changes before they enter a repository.
          </p>
        </article>
      </div>

      <figure class="figure" style="margin:32px 0 0;">
        <img
          src="{{ '/assets/evol-research-pathways.png' | relative_url }}"
          alt="Two independent EVOL Lab research pathways. Reusable change integration progresses through discover, align, adapt, and verify. Developer–LLM collaboration progresses through interpret, recover intent, generate, and gate. Each pathway provides evidence that supports a developer's decision to integrate, revise, or reject a software change."
          loading="lazy"
          decoding="async"
        >
        <figcaption class="figure-cap">
          Both research directions combine automation with evidence and human
          oversight. The tools support the developer's decision; they do not
          replace it.
        </figcaption>
      </figure>
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

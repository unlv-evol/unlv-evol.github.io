---
layout: project-detail
title: 'Reuse and Maintenance Practices among Divergent Forks — EVOL Lab'
description: 'Detail page for the Reuse and Maintenance Practices among Divergent Forks project at EVOL Lab.'
order: 3
featured_home: true
home_media_class: project-card-media--navy
home_name: Reuse & Maintenance Practices among Divergent Forks
home_description: An ecosystem-scale study of software families across Android, .NET, and JavaScript, examining how divergent forks propagate code and maintain shared ancestry over time.
home_meta:
  - Ecosystem mining
  - EMSE 2022
card_media_class: project-card-media--navy
card_image: /assets/reuse_maintenance.jpeg
card_image_alt: Illustration for the Reuse and Maintenance Practices project
card_kicker: Ecosystem mining
card_name: Reuse & Maintenance Practices among Divergent Forks
card_description: An empirical study of software families within Android, .NET, and JavaScript ecosystems, focusing on code propagation and maintenance behavior.
card_pills:
  - Android/.NET/JS
  - Software families
  - EMSE 2022
card_footer: Studies code propagation in the wild
project_breadcrumb: EVOL Lab / Projects / Reuse and Maintenance Practices
project_status: Current project
project_name: Reuse and Maintenance Practices among Divergent Forks
project_pills:
  - Ecosystem mining
  - EMSE 2022
project_lead: This project studies software families that emerge when developers fork reusable systems for different customers, markets, or environments. It examines how those related variants actually maintain shared code over time inside major ecosystems.
project_links:
  - label: All projects
    href: index.html
  - label: Selected projects
    href: /#projects
    site_relative: true
  - label: Original project page
    href: https://johnxu21.github.io/evol/projects/
    external: true
figure_image: /assets/reuse_maintenance.jpeg
figure_alt: Project image for Reuse and Maintenance Practices among Divergent Forks
figure_caption: Illustrative ecosystem view of software families, code propagation paths, and maintenance relationships across related forked variants.
overview_paragraphs:
  - Fork-based reuse is widespread in software ecosystems, but relatively little is known about how those related systems maintain shared ancestry once they begin to diverge. This project identifies and studies software families maintained across Android, .NET, and JavaScript ecosystems to understand their reuse and maintenance practices.
  - The study mined 38 Android families, 526 .NET families, and 8,837 JavaScript families that existed both on official distribution platforms and on GitHub. It then analyzed their characteristics and code-propagation practices, showing that direct integration with Git outside GitHub pull requests was more common than expected and that cross-family integration remained limited overall.
focus_points:
  - Finding software families embedded inside major package ecosystems.
  - Measuring how code is propagated and maintained across divergent forks.
  - Comparing integration practices across Android, .NET, and JavaScript.
  - Providing empirical grounding for tooling that supports families rather than isolated repositories.
key_takeaways:
  - Shows that software families are abundant in real ecosystems, especially JavaScript.
  - Finds limited code integration across families despite shared ancestry.
  - Highlights the need for better maintenance support for ecosystem-scale reuse.
why_it_matters: Software reuse does not end when a fork is created. By understanding how families evolve in the wild, the lab can design tools and theories that reflect actual maintenance behavior instead of idealized workflows.
---

---
layout: project-detail
title: 'RePatch — EVOL Lab'
description: 'Detail page for the RePatch project at EVOL Lab.'
order: 5
featured_home: false
home_media_class: project-card-media--navy
home_name: RePatch
home_description: A refactoring-aware patch integration tool for structurally divergent Java forks.
home_meta:
  - Java
  - SCAM 2025
card_media_class: project-card-media--navy
card_image: /assets/repatch.jpg
card_image_alt: Illustration for the RePatch project
card_kicker: Patch integration tool
card_name: RePatch
card_description: A refactoring-aware patch integration tool that transfers bug-fix commits across structurally divergent Java forks by inverting and replaying refactorings.
card_pills:
  - Java
  - Refactoring-aware merge
  - SCAM 2025
card_footer: Targets divergent Java variants
project_breadcrumb: EVOL Lab / Projects / RePatch
project_status: Active repository
project_name: RePatch
project_pills:
  - Java
  - SCAM 2025
project_lead: RePatch is a refactoring-aware patch integration tool for structurally divergent Java forks. It automates bug-fix transfer across related codebases even when standard cherry-pick fails because of method moves, renames, or broader structural reorganization.
project_links:
  - label: All projects
    href: index.html
  - label: Selected projects
    href: /#projects
    site_relative: true
  - label: GitHub repository
    href: https://github.com/unlv-evol/RePatch
    external: true
figure_image: /assets/repatch.jpg
figure_alt: Project image for RePatch
figure_caption: Illustrative view of patch transfer across divergent Java variants, with structural alignment used to recover from cherry-pick failures.
overview_paragraphs:
  - RePatch begins from a familiar maintenance failure: a bug-fix commit exists in one variant but does not apply cleanly to another because the target has drifted structurally. Instead of giving up after a failed cherry-pick, RePatch detects refactorings, temporarily inverts them to restore alignment, applies the patch, and then replays the original transformations.
  - The approach is designed for long-lived Java variants that continue evolving independently. The repository includes the core integration pipeline, data models for conflict and file analysis, a database layer for result tracking, and a reproducibility package with sample and full evaluation data.
focus_points:
  - Applying bug-fix patches across structurally divergent Java forks.
  - Detecting refactorings that block standard cherry-pick integration.
  - Reducing manual effort during cross-variant synchronization.
  - Supporting reproducible evaluation of merge-conflict reduction.
key_takeaways:
  - Targets missed opportunity patches found between related Java variants.
  - Uses a two-phase alignment strategy built around inversion and replay of refactorings.
  - Ships with artifact support, Docker guidance, and analysis scripts for reproduction.
why_it_matters: Variant forks create hidden maintenance cost whenever shared bugs are fixed twice or propagated manually. RePatch turns refactoring-aware transfer into a practical research artifact for reducing those costs.
---

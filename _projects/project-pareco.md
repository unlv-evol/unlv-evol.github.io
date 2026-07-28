---
layout: project-detail
title: 'PaReco — EVOL Lab'
description: 'Detail page for the PaReco project at EVOL Lab.'
order: 1
featured_home: true
home_media_class: project-card-media--navy
home_name: PaReco
home_description: A clone-detection tool for mining missed opportunity patches and duplicated maintenance effort across variant forks, with a curated dataset spanning 364 source-to-target pairs.
home_meta:
  - Clone detection
  - FSE 2022
card_media_class: project-card-media--navy
card_image: /assets/pareco.jpeg
card_image_alt: Illustration for the PaReco project
card_kicker: Patch reuse analysis
card_name: PaReco
card_description: A clone-detection tool for identifying missed opportunity patches and duplicated maintenance work across variant forks, backed by a large curated dataset.
card_pills:
  - Clone detection
  - Missed patches
  - FSE 2022
card_footer: 364 variant pairs, 8,323 patches
project_breadcrumb: EVOL Lab / Projects / PaReco
project_status: Current project
project_name: PaReco
project_pills:
  - Clone detection
  - FSE 2022
project_lead: 'PaReco is a tool for mining cases of missed opportunity patches and duplicated maintenance effort across variant forks. It focuses on a common maintenance problem in forked repositories: fixes often land in one project but fail to propagate cleanly to related variants that still share the same bug.'
project_links:
  - label: All projects
    href: index.html
  - label: Selected projects
    href: /#projects
    site_relative: true
  - label: Original project page
    href: https://johnxu21.github.io/evol/projects/
    external: true
figure_image: /assets/pareco.jpeg
figure_alt: Project image for PaReco
figure_caption: Illustrative view of PaReco's patch-mining workflow across source and target variants, highlighting missed opportunities and duplicated maintenance.
overview_paragraphs:
  - Re-using whole repositories as a starting point for new projects often creates a variant fork that evolves in parallel with the original. Over time, common artifacts between the two are not always kept synchronized. PaReco addresses that gap by using clone detection to mine patch-level cases where a fix should have propagated but did not, or where developers manually reimplemented similar work on both sides.
  - The project produced a curated dataset from 364 source-to-target variant pairs and 8,323 patches, yielding 1,116 cases of effort duplication and 1,008 missed opportunities. The study reports strong classification performance and shows that, on average, missed patches were introduced in the source variant 52 weeks before appearing in the target context.
focus_points:
  - Identifying missed opportunity bug-fix patches across related repositories.
  - Measuring duplicated maintenance effort between source and target variants.
  - Using clone detection to recover patch relationships at scale.
  - Supporting backporting decisions across long-lived software variants.
key_takeaways:
  - 91% precision, 80% recall, 88% accuracy, and 85% F1-score in the reported evaluation.
  - Helps manage variability in time by revealing later releases that should be backported.
  - Provides concrete data for studying maintenance gaps in fork-based development.
why_it_matters: Forks are often maintained under tight time pressure, which makes cross-variant synchronization easy to miss. PaReco turns those hidden maintenance failures into something measurable and actionable for both researchers and practitioners.
---

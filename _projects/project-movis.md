---
layout: project-detail
title: 'MOVis — EVOL Lab'
description: 'Detail page for the MOVis project at EVOL Lab.'
order: 6
featured_home: false
home_media_class: project-card-media--maroon
home_name: MOVis
home_description: An interactive visual analytics system for localizing missed patches across software variants, combining a Qt GUI with the PaReco backend.
home_meta:
  - Qt / C++
  - FSE 2026 demo
card_media_class: project-card-media--maroon
card_image: /assets/project-movis.svg
card_image_alt: Illustration for the MOVis project
card_kicker: Visualization system
card_name: MOVis
card_description: An interactive visual analytics system for localizing missed patches across software variants, combining a Qt GUI with the PaReco backend.
card_pills:
  - Qt / C++
  - Visual analytics
  - FSE 2026 demo
card_footer: Explores variants, files, and patches visually
project_breadcrumb: EVOL Lab / Projects / MOVis
project_status: Active repository
project_name: MOVis
project_pills:
  - Qt / C++
  - FSE 2026 demo
project_lead: MOVis is an interactive visual analytics system for localizing missed patches across software variants. It combines a Qt-based interface with the PaReco backend so developers can explore variant relationships, drill down into files and commits, and reason about missed patches visually.
project_links:
  - label: All projects
    href: index.html
  - label: Selected projects
    href: /#projects
    site_relative: true
  - label: GitHub repository
    href: https://github.com/unlv-evol/MOVis
    external: true
figure_image: /assets/project-movis.png
figure_alt: Illustration showing interactive missed-patch visualization for MOVis
figure_caption: Illustrative view of MOVis linking software variants, patches, and file-level drill-downs inside an interactive visual workflow.
overview_paragraphs:
  - MOVis is the visualization counterpart to missed-patch analysis. Where mining tools recover candidates from related repositories, MOVis helps developers and researchers inspect those relationships through an interactive interface that highlights variants, patches, files, and commit-level details.
  - The artifact supports reproduction of an FSE 2026 tool demonstration paper and includes a Qt-based GUI, the PaReco analysis backend, scripts, Docker support, and development guidance for Linux, macOS, and Windows. It is designed to be self-contained enough for reproduction while still being extensible for new datasets and ranking logic.
focus_points:
  - Interactive localization of missed patches across software variants.
  - Visual exploration of patch, file, and commit relationships.
  - Integration of a Qt GUI with mining and analysis backends.
  - Reproducible demonstrations of software-variant maintenance workflows.
key_takeaways:
  - Combines a Qt/C++ interface with the PaReco backend for analysis and extraction.
  - Supports local and Docker-based execution on Linux, macOS, and Windows setups.
  - Focuses on exploratory navigation across variants, files, and missed patches.
why_it_matters: Missed-patch evidence is harder to act on when it stays trapped in tables or scripts. MOVis makes those relationships visible so developers can inspect, compare, and reason about synchronization opportunities much more directly.
---

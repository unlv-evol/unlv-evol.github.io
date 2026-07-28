---
layout: project-detail
title: 'PatchTrack — EVOL Lab'
description: 'Detail page for the PatchTrack project at EVOL Lab.'
order: 4
featured_home: true
home_media_class: project-card-media--maroon
home_name: PatchTrack
home_description: A replication package and analysis tool for studying how ChatGPT-generated patches are adopted, refined, or discarded inside real pull request workflows.
home_meta:
  - AI-assisted development
  - Patch adoption analysis
card_media_class: project-card-media--maroon
card_image: /assets/patchtrack.png
card_image_alt: Illustration for the PatchTrack project
card_kicker: AI pull request analysis
card_name: PatchTrack
card_description: A tool and replication package for classifying whether ChatGPT-suggested patches were applied, skipped, or transformed during pull request integration.
card_pills:
  - 338 pull requests
  - 645 AI snippets
  - MIT licensed
card_footer: Tracks real-world ChatGPT patch adoption
project_breadcrumb: EVOL Lab / Projects / PatchTrack
project_status: Active repository
project_name: PatchTrack
project_pills:
  - AI-assisted development
  - MIT licensed
project_lead: PatchTrack is a tool and replication package for analyzing how ChatGPT influences pull request outcomes. It classifies whether AI-generated patches are applied, partially integrated, or ignored, giving the lab a grounded way to study real AI-assisted development behavior.
project_links:
  - label: All projects
    href: index.html
  - label: Selected projects
    href: /#projects
    site_relative: true
  - label: GitHub repository
    href: https://github.com/unlv-evol/PatchTrack
    external: true
figure_image: /assets/patchtrack.png
figure_alt: Project image for PatchTrack
figure_caption: Illustrative view of pull request outcomes, patch classification, and integration trajectories for ChatGPT-generated code suggestions.
overview_paragraphs:
  - PatchTrack was built to answer a practical question about generative AI in software development: when developers mention ChatGPT in pull requests, how often do those suggestions actually make it into the final code, and in what form? The tool analyzes pull requests containing self-admitted ChatGPT usage and classifies suggested patches as applied, not applied, or not suggested.
  - The replication package reported 338 pull requests from 255 GitHub repositories, 645 AI-generated snippets, and 3,486 developer-authored patches. Its findings show that full adoption of ChatGPT output is rare, with a median integration rate of 25%, and that developers often treat AI output as a starting point for iterative refinement rather than as final code.
focus_points:
  - Classifying AI-suggested patches within pull request workflows.
  - Measuring how often ChatGPT code is integrated, transformed, or discarded.
  - Supporting reproducible notebook- and CLI-based analysis of adoption behavior.
  - Connecting AI-generated suggestions to developer decision-making in context.
key_takeaways:
  - Reveals that full ChatGPT patch adoption is uncommon in real pull requests.
  - Supports both notebook-based reproduction and CLI-based exploration.
  - Provides a concrete bridge between AI coding assistance and empirical software engineering evidence.
why_it_matters: Claims about AI coding tools often stop at benchmark quality. PatchTrack instead shows how those suggestions are negotiated inside collaborative development, which is the level where practical engineering impact is actually decided.
---

---
title: Project Trace
description: Quick trace of the Quartz note project and how this note system is organized.
tags:
  - project
  - quartz
  - reference
---

# Project Trace

This repository is a Quartz v4 digital garden. The active note system lives in `content/` and is now organized around a career transition into public-markets fund management.

## Repo Structure

- `content/`: all published personal notes
- `docs/`: Quartz documentation bundled with the repo
- `quartz/`: generator internals, components, plugins, and build pipeline
- `public/`: generated output from previous builds
- `package.json`: CLI scripts and dependencies
- `quartz.config.ts`: site configuration, theme, and enabled plugins

## Current Note Model

- Home page: [[index|Engineer to Fund Manager]]
- Transition planning: [[career-roadmap|Career Roadmap]]
- Skill diagnosis: [[skill-gap-map|Skill Gap Map]]
- Core investing domain: [[topics/finance|Finance]]
- Tech leverage for investing: [[topics/learn-tech|Quant & Research Tech]]
- Operating process: [[research-pipeline|Research Pipeline]]

## Working Rules

1. Add all new notes under `content/`
2. Use frontmatter for `title`, `description`, and `tags`
3. Use Quartz wikilinks to connect concept notes, templates, and live research
4. Keep generic software notes separate from investing-support tooling

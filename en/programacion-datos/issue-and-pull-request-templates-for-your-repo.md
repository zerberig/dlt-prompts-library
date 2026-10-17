---
title: "Issue and Pull Request Templates for Your Repo"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0043"
lang: en
type: text
category: "Coding, Vibe Coding & Data"
category_slug: "programacion-datos"
subcategory: "Dev teams"
level: "intermediate"
description: "Get YAML issue forms for bugs and features, a PR template, and labels so every report arrives complete."
tags: ["github", "pull requests", "issues", "templates", "open source"]
variables: ["your project", "project type", "who contributes"]
translation: "/es/programacion-datos/plantillas-de-issues-y-pull-requests-para-tu-repositorio"
---

Context: I maintain [your project] on GitHub, a [project type] project (internal, open source, library, app). We get contributions from [who contributes], and right now reports arrive incomplete or thin on details.
Goal: Make every issue and pull request include what we need to triage and review it without back-and-forth questions.
Deliverable: 1) A bug report issue form in YAML (.github/ISSUE_TEMPLATE/bug_report.yml) with steps to reproduce, expected vs. actual behavior, version and environment, and severity. 2) A feature request form. 3) The config.yml file to route general questions to another channel. 4) A PULL_REQUEST_TEMPLATE.md with change type, summary, related issue, how it was tested, and a checklist. 5) A proposed label set for type, priority, and status.
Criteria: Required fields only where they're truly needed, because long forms discourage contributions. Short helper text with examples. Valid syntax for GitHub issue forms.
Format: Each file in its own code block with its path as the title; the labels in a table with Name, Color, and Use.
If any essential information is missing, ask me up to 3 questions before you start.

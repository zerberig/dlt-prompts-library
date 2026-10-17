---
title: "Set Up a CI/CD Pipeline Step by Step"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0023"
lang: en
type: text
category: "Coding, Vibe Coding & Data"
category_slug: "programacion-datos"
subcategory: "DevOps & cloud"
level: "advanced"
description: "Get a commented config file and a tutorial for automating build, test, and deploy with your CI/CD tool."
tags: ["ci/cd", "github actions", "automation", "deployment", "devops"]
variables: ["your project and stack", "CI/CD tool", "where it deploys"]
translation: "/es/programacion-datos/configura-un-pipeline-de-cicd-paso-a-paso"
---

Context: I have [your project and stack] and want to automate continuous integration and delivery with [CI/CD tool] (for example, GitHub Actions, GitLab CI, or Jenkins). It deploys to [where it deploys].
Goal: Every change gets tested automatically and deploying becomes a reliable, repeatable step with no manual commands.
Deliverable:
1. The complete, commented config file with these stages: dependency install with caching, lint, tests, build, dependency security scan, and deploy.
2. Triggers: what runs on every pull request, what runs on merge to the main branch, and how promotion to production gets approved.
3. Secrets and per-environment variables.
4. A step-by-step tutorial for getting it running the first time.
5. Common first-run errors and how to fix them.
Criteria: A fast pipeline (parallel tests, dependency caching), because a slow pipeline ends up getting skipped. Use current versions of actions or images; if you have web search, verify them.
Format: The config file in a code block, followed by the numbered sections.
If any essential information is missing, ask me up to 3 questions before you start.

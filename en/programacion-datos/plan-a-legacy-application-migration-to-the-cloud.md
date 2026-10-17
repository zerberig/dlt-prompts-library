---
title: "Plan a Legacy Application Migration to the Cloud"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0052"
lang: en
type: text
category: "Coding, Vibe Coding & Data"
category_slug: "programacion-datos"
subcategory: "Architecture"
level: "advanced"
description: "Get a component assessment, target architecture, phased plan with rollback, cost estimates, and risks."
tags: ["cloud migration", "legacy systems", "modernization", "architecture", "cloud costs"]
variables: ["legacy application description", "current infrastructure", "cloud provider", "budget, timeline, team, or compliance constraints"]
translation: "/es/programacion-datos/plan-de-migracion-de-una-aplicacion-legada-a-la-nube"
---

Context: We run [legacy application description] (technology, age, database, and number of users) on [current infrastructure]. We want to move to [cloud provider] or whichever one you recommend. Our constraints: [budget, timeline, team, or compliance constraints].
Goal: Migrate with the lowest possible risk to operations, improving scalability and security, with costs we can predict.
Deliverable: 1) An initial assessment: which components to migrate and with which strategy (rehost, replatform, refactor, replace, retire, or retain), with the reason. 2) The target architecture with a Mermaid diagram. 3) A phased plan with estimated duration, criteria for moving between phases, and a rollback plan. 4) A data migration strategy with minimal downtime. 5) Security and compliance controls. 6) Current vs. target monthly cost estimates, with assumptions spelled out. 7) The top 8 risks with mitigations.
Criteria: Start with low-risk components to learn before moving anything critical. Point out what's worth modernizing now and what can wait until after the move. Use web search if you have it for current pricing and services, and flag as an estimate any cost you can't back up with a source.
Format: Numbered sections, with tables for the component assessment, costs, and risks.
If any essential information is missing, ask me up to 3 questions before you start.

---
title: "Choose an Architecture Style That Fits Your Business"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0032"
lang: en
type: text
category: "Coding, Vibe Coding & Data"
category_slug: "programacion-datos"
subcategory: "Architecture"
level: "advanced"
description: "Turn business requirements into quality attributes, compare styles and deployment options, and record the call in ADRs."
tags: ["software architecture", "adr", "microservices", "business requirements", "cloud"]
variables: ["system description", "type of business", "key requirements", "team, budget, or infrastructure constraints"]
translation: "/es/programacion-datos/elige-el-estilo-de-arquitectura-segun-tu-negocio"
---

Context: We're going to build [system description] for [type of business]. The most important business requirements are [key requirements] (for example: launch in 4 months, comply with data regulations, operate in several cities). We have these constraints: [team, budget, or infrastructure constraints], and we need to choose between cloud, on-premises, or a hybrid setup.
Goal: Make the foundational architecture decisions with clear arguments I can present to leadership and to the engineering team.
Deliverable: 1) The 4 to 6 priority quality attributes (scalability, reliability, security, cost, delivery speed, etc.) derived from the requirements, in order of importance. 2) A comparison of 2 or 3 viable architecture styles (for example: modular monolith, microservices, serverless) against those attributes. 3) A comparison of cloud, on-premises, and hybrid deployment. 4) The final recommendation and 3 architecture decision records (ADRs) with context, decision, alternatives, and consequences.
Criteria: Tie every recommendation to a specific business requirement, so the decision can be defended and revisited later. Be explicit about the costs and risks of the recommended option. Note which signals should trigger reconsidering the decision in the future.
Format: Comparison tables scored 1 to 5 with a one-line justification in the key cells; the ADRs in Markdown, each with its own heading.
If any essential information is missing, ask me up to 3 questions before you start.

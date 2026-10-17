---
title: "Feature Requirements With User Stories"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0046"
lang: en
type: text
category: "Coding, Vibe Coding & Data"
category_slug: "programacion-datos"
subcategory: "Technical docs"
level: "advanced"
description: "Get a doc with scope, user stories, Given/When/Then acceptance criteria, and measurable non-functional requirements."
tags: ["software requirements", "user stories", "acceptance criteria", "specification", "product"]
variables: ["feature name", "your product", "problem it solves and for whom", "existing notes"]
translation: "/es/programacion-datos/requisitos-de-una-funcionalidad-con-historias-de-usuario"
---

Context: We're about to build [feature name] for [your product]. It solves this problem: [problem it solves and for whom]. Notes, conversations, or sketches we already have: [existing notes].
Goal: A requirements document that aligns product, design, engineering, and QA before any code is written, to avoid rework.
Deliverable: 1) Summary and a measurable goal for the feature. 2) Scope: what's in and what's out. 3) Prioritized user stories in the "As a…, I want…, so that…" format. 4) Acceptance criteria for each story in Given/When/Then format, including edge and error cases. 5) Non-functional requirements with measurable values (performance, security, accessibility, compatibility). 6) Dependencies, assumptions, and open questions.
Criteria: Every requirement must be testable; replace vague words like "fast" or "easy" with concrete values. Separate what I gave you from what you're assuming, and flag the assumptions for the team to confirm. Write so someone who missed the meetings can follow it.
Format: A Markdown document with a heading per section, stories as a numbered list with MoSCoW priority, and the non-functional requirements in a table with Requirement, Metric, and Target value.
If any essential information is missing, ask me up to 3 questions before you start.

---
title: "Technical Spec and Documentation for a Library"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0051"
lang: en
type: text
category: "Coding, Vibe Coding & Data"
category_slug: "programacion-datos"
subcategory: "Technical docs"
level: "advanced"
description: "Get a design doc with the public API, design decisions, versioning, testing, and a draft README."
tags: ["technical spec", "api documentation", "libraries", "software design", "readme"]
variables: ["library purpose", "language", "who will use it", "initial requirements or notes"]
translation: "/es/programacion-datos/especificacion-tecnica-y-documentacion-de-una-libreria"
---

Context: We're going to build a library for [library purpose] in [language], aimed at [who will use it]. Here's what we know so far: [initial requirements or notes].
Goal: A design document the team can review before implementation that later becomes the foundation for the public docs.
Deliverable: 1) Purpose, scope, and what the library won't do. 2) Public API design: classes or functions, signatures, parameters, return values, errors it can raise, and a usage example for each. 3) Internal design decisions and rejected alternatives. 4) Compatibility, dependencies, and a semantic versioning policy. 5) Testing strategy. 6) A draft README with installation, quick start, and examples.
Criteria: Design the API from the user's point of view: clear names, sensible defaults, and few ways to do the same thing, because a public API is hard to change later. Examples must be runnable code, not pseudocode. Flag the open questions the team needs to decide.
Format: A Markdown document with numbered headings, signatures and examples in code blocks, and the API in a table with the columns Element, Signature, Description, and Errors.
If any essential information is missing, ask me up to 3 questions before you start.

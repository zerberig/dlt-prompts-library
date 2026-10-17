---
title: "Complete Test Plan for a New Feature"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0001"
lang: en
type: text
category: "Coding, Vibe Coding & Data"
category_slug: "programacion-datos"
subcategory: "Testing & QA"
level: "advanced"
description: "Get a test plan with scope, strategy, key test cases, environments, risks, and exit criteria for your release."
tags: ["test plan", "qa", "testing", "test cases", "release"]
variables: ["feature", "your product", "technical description and requirements", "launch date and team"]
translation: "/es/programacion-datos/plan-de-pruebas-completo-para-una-nueva-funcionalidad"
---

Context: We're about to ship [feature] in [your product]. Here's what it does and how it's built: [technical description and requirements]. Schedule and team constraints: [launch date and team].
Goal: I want a test plan the team can follow to decide, with data, whether the feature is ready for production.
Deliverable:
1. Scope: what gets tested and what's out of scope, and why.
2. Strategy: test types (unit, integration, end-to-end, performance, security, accessibility) and which ones to automate.
3. 15-25 key test cases, including error scenarios and edge cases.
4. Required environments and test data.
5. The most likely risks and failure scenarios, and how to detect them.
6. Entry and exit criteria, plus metrics to measure release quality.
Criteria: Prioritize by risk to users and to the business, because testing time is limited. Anyone who didn't write the code should be able to run each case.
Format: Numbered sections; test cases in a table with the columns ID, Scenario, Steps, Data, Expected result, and Priority.
If any essential information is missing, ask me up to 3 questions before you start.

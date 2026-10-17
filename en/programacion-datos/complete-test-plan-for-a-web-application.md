---
title: "Complete Test Plan for a Web Application"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0062"
lang: en
type: text
category: "Coding, Vibe Coding & Data"
category_slug: "programacion-datos"
subcategory: "Quality and security"
level: "advanced"
description: "Get a layered testing strategy, scenarios for critical flows, tools, entry and exit criteria, and CI integration."
tags: ["test plan", "qa", "test automation", "performance", "ci"]
variables: ["your web application", "critical flows", "current testing situation"]
translation: "/es/programacion-datos/plan-de-pruebas-completo-para-una-aplicacion-web"
---

Context: We're about to test [your web application] (what it does, stack, and main users). The most business-critical features are [critical flows]. Today we have [current testing situation] (for example: manual testing only, some unit tests, no CI).
Goal: A test plan covering functionality, performance, and security, prioritized by risk, that the team can actually execute.
Deliverable: 1) An overall strategy based on the testing pyramid: what to cover with unit, integration, end-to-end, performance, security, and accessibility tests, and why. 2) Test scenarios for each critical flow, including negative and edge cases. 3) Suggested tools for each test type based on my stack. 4) Required test environments and data. 5) Entry and exit criteria, plus quality metrics. 6) How to integrate it into the CI pipeline.
Criteria: Prioritize by risk: go deepest where a failure would do the most damage. Set performance targets with concrete values (for example, p95 response time at a given number of concurrent users). Be realistic about the effort of maintaining end-to-end tests.
Format: Numbered sections; the scenarios in a table with the columns ID, Flow, Test type, Steps, Expected result, and Priority.
If any essential information is missing, ask me up to 3 questions before you start.

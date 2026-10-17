---
title: "Performance Diagnosis and Optimization Plan"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0009"
lang: en
type: text
category: "Coding, Vibe Coding & Data"
category_slug: "programacion-datos"
subcategory: "Performance"
level: "advanced"
description: "Analyze your system's metrics and profiles to find bottlenecks and prioritize optimizations."
tags: ["performance", "optimization", "bottlenecks", "profiling", "load testing"]
variables: ["your product", "architecture and stack", "symptom", "metrics, profiles, or logs"]
translation: "/es/programacion-datos/diagnostico-de-rendimiento-y-plan-de-optimizacion"
---

Context: [your product] runs on [architecture and stack]. The symptom: [symptom] (for example, the API takes over 2 seconds with more than 500 concurrent users). Here's the data I have:
[metrics, profiles, or logs]
Goal: Find the real causes of the slowness or excessive resource use and decide what to optimize first.
Deliverable:
1. A reading of the data: what it says about CPU, memory, I/O, database, and network under different loads.
2. Likely bottlenecks, ranked by impact, with the evidence for each.
3. Proposed optimizations in code, database (indexes, queries, connections), and infrastructure (caching, scaling), with effort and expected impact.
4. Load tests and metrics to validate each change before and after.
5. Extra data I should collect if the diagnosis is inconclusive, and which tools to use.
Criteria: Base every conclusion on the data I gave you and separate what's proven from hypotheses, because optimizing blind usually just moves the bottleneck. Flag any percentage improvement you can't back up as an estimate.
Format: Numbered sections; optimizations in a table with the columns Change, Area, Impact, Effort, and How to measure it.
If any essential information is missing, ask me up to 3 questions before you start.

---
title: "Refactoring Plan for Hard-to-Maintain Code"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0057"
lang: en
type: text
category: "Coding, Vibe Coding & Data"
category_slug: "programacion-datos"
subcategory: "Code"
level: "advanced"
description: "Spot code smells, get a refactored example, and a staged plan to improve the codebase without stalling delivery."
tags: ["refactoring", "code smells", "maintainability", "technical debt", "clean code"]
variables: ["language and framework", "project size and age", "current problems", "representative code snippet"]
translation: "/es/programacion-datos/plan-de-refactorizacion-para-codigo-dificil-de-mantener"
---

Context: I work on a [language and framework] project that is [project size and age]. The problems that hurt us most are [current problems] (for example: huge classes, duplicated code, simple changes that break other parts, few tests). Here's a representative snippet:
[representative code snippet]
Goal: Improve maintainability and readability gradually, without halting feature delivery or breaking what already works.
Deliverable: 1) The code smells you find in the snippet and the right refactoring technique for each (extract method, introduce parameter object, replace conditional with polymorphism, etc.). 2) The refactored snippet as an example. 3) A staged refactoring plan for the whole project, prioritized by impact and risk. 4) Conventions and a folder structure the team can adopt. 5) Tools to catch problems automatically (linters, static analysis, complexity metrics).
Criteria: Every refactoring must preserve behavior; say which characterization tests to write before touching untested code. Prioritize the areas that change most often, because that's where the improvement pays off most.
Format: A findings table with the columns Problem, Location, Technique, and Priority; code in blocks, and the staged plan as a numbered list.
If any essential information is missing, ask me up to 3 questions before you start.

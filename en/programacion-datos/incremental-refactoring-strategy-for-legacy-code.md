---
title: "Incremental Refactoring Strategy for Legacy Code"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0024"
lang: en
type: text
category: "Coding, Vibe Coding & Data"
category_slug: "programacion-datos"
subcategory: "Code quality"
level: "advanced"
description: "Plan a staged refactor of a legacy system that keeps it working while improving maintainability and performance."
tags: ["refactoring", "legacy code", "technical debt", "maintainability", "performance"]
variables: ["your product or module", "current problems", "current test coverage", "constraints"]
translation: "/es/programacion-datos/refactorizacion-incremental-de-codigo-heredado"
---

Context: We need to refactor [your product or module]. Current problems: [current problems] (for example, slow and risky changes, recurring bugs, or poor performance). Current test coverage: [current test coverage]. Constraints: [constraints] (we can't pause new features, small team, a deadline).
Goal: Improve maintainability and performance without a full rewrite and without breaking what works today.
Deliverable:
1. Diagnosis: which parts to refactor first based on change frequency, bug count, and risk.
2. Safety net: characterization tests that lock in current behavior before touching the code.
3. A staged strategy (for example, the strangler fig pattern, extracting modules, or introducing interfaces), with small deliverables that can ship independently.
4. Performance improvements to include and how to measure them before and after.
5. Success metrics and how to explain the value of this work to the business.
Criteria: Every stage must leave the system working and in production, because long refactors on a separate branch rarely get finished. Point out when something is better left alone.
Format: Numbered sections; the stages in a table with Stage, Change, Risk, How to validate, and Estimated duration.
If any essential information is missing, ask me up to 3 questions before you start.

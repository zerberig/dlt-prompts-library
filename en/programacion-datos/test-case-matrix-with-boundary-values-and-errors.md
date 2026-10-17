---
title: "Test Case Matrix With Boundary Values and Errors"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0012"
lang: en
type: text
category: "Coding, Vibe Coding & Data"
category_slug: "programacion-datos"
subcategory: "Testing & QA"
level: "intermediate"
description: "Design test cases with partitions, boundary values, error paths, and a regression set for a function or feature."
tags: ["test cases", "boundary values", "regression", "qa", "testing"]
variables: ["function or feature", "spec or code", "recent changes"]
translation: "/es/programacion-datos/matriz-de-casos-de-prueba-con-valores-limite-y-errores"
---

Context: I need to test [function or feature]. Here's its spec or code:
[spec or code]
Recent changes that could break something: [recent changes].
Goal: Cover the scenarios that can actually fail, without hundreds of redundant cases.
Deliverable: 1) Equivalence partitions and boundary values for each input. 2) Test cases covering the happy path, boundaries, invalid input, error handling, permissions, and, where relevant, concurrency or performance. 3) A regression subset to run after every change. 4) Any gaps or ambiguities you find in the spec.
Criteria: Each case tests one thing and has a verifiable expected result. Prioritize by likelihood of failure and impact, so the team knows what to run first when time is short.
Format: A table with the columns ID, Type, Input or condition, Expected result, Priority, and Regression (yes/no).
If any essential information is missing, ask me up to 3 questions before you start.

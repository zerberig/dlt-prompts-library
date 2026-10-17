---
title: "Code Review With Prioritized Findings"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0002"
lang: en
type: text
category: "Coding, Vibe Coding & Data"
category_slug: "programacion-datos"
subcategory: "Code quality"
level: "intermediate"
description: "Get a review of your code covering correctness, readability, design patterns, performance, and security, with fixes."
tags: ["code review", "design patterns", "performance", "security", "best practices"]
variables: ["language and framework", "what this code does", "your team's standards", "your code"]
translation: "/es/programacion-datos/revision-de-codigo-con-hallazgos-priorizados"
---

Review this code the way a senior developer would before approving a pull request.
Context: It's written in [language and framework] and its job is to [what this code does]. We follow these standards: [your team's standards].
[your code]
Goal: I want to know what to fix before merging and what to learn for next time.
Deliverable: Findings on correctness, readability, use of design patterns, performance, and security. For each one: the snippet, the problem, why it matters, and the fix. At the end, 2 or 3 things the code does well.
Criteria: Order by real impact, starting with bugs and security risks, and leave style for last. Suggest a design pattern only if it simplifies the code, not for its own sake. If something depends on context you can't see, say so instead of guessing.
Format: A table with the columns Severity (critical, high, medium, low), Location, Problem, and Suggestion; below it, the corrected snippets in code blocks.

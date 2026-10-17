---
title: "Optimize a Code Snippet for Speed and Clarity"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0045"
lang: en
type: text
category: "Coding, Vibe Coding & Data"
category_slug: "programacion-datos"
subcategory: "Code"
level: "intermediate"
description: "Get a performance diagnosis, an improved version of your code, and a way to measure that the gain is real."
tags: ["optimization", "performance", "clean code", "complexity", "profiling"]
variables: ["language", "execution context", "profiling results", "your code"]
translation: "/es/programacion-datos/optimiza-tu-codigo-para-que-sea-eficiente-y-conciso"
---

Context: This [language] snippet runs in [execution context] (for example: a high-traffic endpoint, a data processing script, a function called inside a loop). Profiling data or measured timings, if I have them: [profiling results].
Code:
[your code]
Goal: Improve performance and simplify the code without changing its behavior.
Deliverable: 1) A short diagnosis: where the time or memory goes and the current complexity. 2) The complete improved version. 3) A list of changes with the expected impact of each. 4) How to measure the improvement with a simple benchmark, plus tests to confirm the output hasn't changed.
Criteria: Prioritize the highest-impact changes (algorithm and data structures, repeated queries or I/O) before micro-optimizations. Protect readability: if an optimization makes the code hard to maintain, present it as optional and explain the trade-off. Keep the original code's style. Point out which improvements need to be confirmed by measuring rather than assuming them.
Format: Numbered sections, code in blocks, and the change list as a table with the columns Change, Before, After, and Expected impact.
If any essential information is missing, ask me up to 3 questions before you start.

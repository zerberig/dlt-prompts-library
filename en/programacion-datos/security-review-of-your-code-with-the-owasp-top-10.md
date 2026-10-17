---
title: "Security Review of Your Code With the OWASP Top 10"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0030"
lang: en
type: text
category: "Coding, Vibe Coding & Data"
category_slug: "programacion-datos"
subcategory: "Quality and security"
level: "advanced"
description: "Find vulnerabilities in a code snippet, with severity, exploit scenario, fix, and tests for each finding."
tags: ["security", "owasp", "code review", "vulnerabilities", "appsec"]
variables: ["type of application", "language and framework", "what the code does", "your code"]
translation: "/es/programacion-datos/revision-de-seguridad-de-tu-codigo-con-owasp-top-10"
---

Context: Here's a code snippet from [type of application] written in [language and framework]. This part handles [what the code does] (for example: authentication, form handling, file uploads, database queries).
Code:
[your code]
Goal: Catch vulnerabilities before this goes to production and know what to fix first.
Deliverable: 1) A list of findings. 2) A fixed version of the affected parts. 3) Tests or abuse cases I can use to confirm each fix works.
Criteria: Check at least injection (SQL and command), XSS, broken access control and insecure direct object references, secrets handling, input validation, authentication and sessions, and risky dependencies; map each finding to its OWASP Top 10 category where it applies. For each finding, explain how it would be exploited in a realistic scenario, because that helps prioritize. Separate vulnerabilities confirmed in the code from risks that depend on configuration or code you can't see. If a part is fine, say so instead of inventing problems to fill the list.
Format: A table with the columns Severity (critical, high, medium, low), Finding, Line or function, OWASP category, How it's exploited, and Fix; then the fixed code in blocks, and the tests as bullets at the end.
If any essential information is missing, ask me up to 3 questions before you start.

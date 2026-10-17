---
title: "Deploy-Ready Serverless Function Boilerplate"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0010"
lang: en
type: text
category: "Coding, Vibe Coding & Data"
category_slug: "programacion-datos"
subcategory: "DevOps & cloud"
level: "intermediate"
description: "Generate a serverless function starter with dependencies, infrastructure as code, tests, and deployment steps."
tags: ["serverless", "aws lambda", "infrastructure as code", "cloud", "boilerplate"]
variables: ["provider and service", "language", "what the function should do", "trigger"]
translation: "/es/programacion-datos/funcion-serverless-base-lista-para-desplegar"
---

Context: I need a serverless function on [provider and service] (for example, AWS Lambda, Google Cloud Functions, or Azure Functions) written in [language]. It should [what the function should do] and is triggered by [trigger] (an HTTP request, a queue message, a new file, or a schedule).
Goal: A clean starting point I can deploy today and extend without restructuring.
Deliverable:
1. The project folder structure.
2. The handler with input validation, error handling, and structured logging.
3. The dependencies file.
4. An infrastructure-as-code template (for example, SAM, Terraform, or the provider's native tool) with least-privilege permissions.
5. A unit test and how to run the function locally.
6. Deployment commands and how to handle environment variables and secrets.
Criteria: Apply least privilege to permissions and never put secrets in the code, because those are the most common serverless security mistakes. Use runtimes and versions that are still supported; if you have web search, verify them.
Format: Each file in its own code block with its path as the heading, followed by a short explanation.

---
title: "Guide to Integrating a Third-Party API Into Your App"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0021"
lang: en
type: text
category: "Coding, Vibe Coding & Data"
category_slug: "programacion-datos"
subcategory: "Integrations"
level: "advanced"
description: "Integrate an external API step by step with auth, error handling, retries, rate limits, secrets, and tests."
tags: ["api", "integration", "authentication", "error handling", "backend"]
variables: ["third-party API", "your app and stack", "what you want the integration to achieve"]
translation: "/es/programacion-datos/guia-para-integrar-una-api-de-terceros-en-tu-aplicacion"
---

Context: I want to integrate [third-party API] into [your app and stack]. With this integration I want to [what you want the integration to achieve].
Goal: A robust integration that doesn't break when the external API fails or changes, and that's easy to maintain.
Deliverable:
1. Setup steps: credentials, sandbox and production environments, and where to store secrets.
2. Authentication (API keys, OAuth, or other) with sample code.
3. A client or module that isolates the integration from the rest of the app.
4. Error handling, timeouts, retries with exponential backoff, and rate limits.
5. Webhooks or syncing, if relevant, with signature validation.
6. Tests: unit tests with mocked responses and one test against the provider's sandbox.
7. Common problems and how to diagnose them.
Criteria: If you have web search, check the API's current official documentation and tell me what you couldn't confirm, because APIs change versions and limits often. Never put credentials in the code.
Format: Numbered sections with code blocks in my stack.
If any essential information is missing, ask me up to 3 questions before you start.

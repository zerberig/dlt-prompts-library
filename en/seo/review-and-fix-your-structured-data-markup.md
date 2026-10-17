---
title: "Review and Fix Your Structured Data Markup"
model: "ChatGPT · Claude · Gemini"
image: "seo.webp"
id: "SEO-0057"
lang: en
type: text
category: "SEO"
category_slug: "seo"
subcategory: "Technical SEO"
level: "intermediate"
description: "Paste your schema code and get errors, missing properties, and a corrected JSON-LD version ready to use."
tags: ["structured data", "schema", "json-ld", "rich results", "technical seo"]
variables: ["page type", "schema code", "page content"]
translation: "/es/seo/revisa-y-corrige-tu-marcado-de-datos-estructurados"
---

Context: This is a [page type] page (product, article, recipe, local business, event, etc.). Here is its current structured data markup: [schema code]. And here is the relevant visible content on the page: [page content].
Goal: I want the markup to be valid, consistent with what users see, and eligible for whatever rich results apply.
Deliverable: 1) Overall status: valid, with warnings, or with errors. 2) Syntax and data type errors (ISO 8601 dates, numeric prices, absolute URLs). 3) Missing required and recommended properties, with why they matter. 4) Markup data that doesn't match the visible content. 5) The full corrected version in JSON-LD.
Criteria: Mark up only information that appears on the page, because marking up hidden or invented content can trigger a manual action. If you have web search, confirm in Google's current documentation which rich results it still shows for this type. Recommend that I validate the final result with the Rich Results Test and the schema.org validator.
Format: A list of findings by category with their fix, followed by the final code block.
If any essential information is missing, ask me up to 3 questions before you start.

---
title: "Generate Schema JSON-LD Markup for an Article"
model: "ChatGPT · Claude · Gemini"
image: "seo.webp"
id: "SEO-0014"
lang: en
type: text
category: "SEO"
category_slug: "seo"
subcategory: "Technical SEO"
level: "intermediate"
description: "Get valid JSON-LD code for your blog article, ready to paste and test."
tags: ["schema", "json-ld", "structured data", "blog"]
variables: ["article details", "article content"]
translation: "/es/seo/genera-el-marcado-schema-json-ld-de-un-articulo"
---

Context: I need structured data for this article on my blog. Article details: [article details] (title, URL, author and profile, publish and update dates, main image, site name and logo). Content or summary: [article content].
Goal: I want search engines to understand who wrote the article, what it's about, and when it was updated, and for it to be eligible for any rich results that apply.
Deliverable: 1) The complete JSON-LD code using the best-fitting type (BlogPosting or Article) and, only if the content justifies it, one extra block (for example, BreadcrumbList or HowTo). 2) A list of the fields you left as "to complete". 3) Short instructions to add it and test it with the rich results test.
Criteria: Use only data that appears in the article; the markup must describe what visitors see on the page, because anything else can lead to manual actions. Valid JSON, no comments inside the code. If you have web search, confirm which properties are still recommended.
Format: The code in a code block, followed by the list and the instructions.
If any essential information is missing, ask me up to 3 questions before you start.

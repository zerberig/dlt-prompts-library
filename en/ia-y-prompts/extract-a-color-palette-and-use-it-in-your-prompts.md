---
title: "Extract a Color Palette and Use It in Your Prompts"
model: "ChatGPT · Claude · Gemini"
image: "ia-y-prompts.webp"
id: "IAP-0030"
lang: en
type: text
category: "AI & Prompt Generators"
category_slug: "ia-y-prompts"
subcategory: "Prompt engineering"
level: "intermediate"
description: "Analyze a reference image, pull its palette, and turn it into color descriptions that image models understand."
tags: ["color palette", "color theory", "reference image", "image prompts", "branding"]
variables: ["use of the palette", "subject of the new images"]
translation: "/es/ia-y-prompts/extrae-una-paleta-de-color-y-usala-en-tus-prompts"
---

Context: I'm going to upload a reference image whose palette I want to reuse for [use of the palette] (brand identity, illustration series, campaign).
Goal: Keep the same color mood in new images generated with Nano Banana 2, GPT Image 2, or Midjourney V8.
Deliverable: 1) A 5-7 color palette with approximate hex codes, a descriptive name (for example, "burnt terracotta" or "muted sage green"), a role (dominant, secondary, accent), and its approximate share of the image. 2) A read of the palette: temperature, contrast, saturation, and the emotion it conveys. 3) A reusable 1-2 sentence block describing the palette in natural language, to paste at the end of any image prompt. 4) Three sample prompts about [subject of the new images] that apply the palette.
Criteria: In the prompts, use descriptive color names and their role in the scene, because image models interpret that better than hex codes; the codes are for your design software. Mark the hex values as approximate.
Format: A palette table (Hex, Name, Role, Share), then short sections.
If any essential information is missing, ask me up to 3 questions before you start.

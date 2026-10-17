---
title: "Remove Objects From a Photo With AI Instructions"
model: "ChatGPT · Claude · Gemini"
image: "ia-y-prompts.webp"
id: "IAP-0031"
lang: en
type: text
category: "AI & Prompt Generators"
category_slug: "ia-y-prompts"
subcategory: "Photo editing"
level: "intermediate"
description: "Write inpainting instructions that remove distractions from a photo and fill the background believably."
tags: ["object removal", "inpainting", "ai editing", "nano banana 2", "retouching"]
variables: ["photo description", "objects to remove"]
translation: "/es/ia-y-prompts/quita-objetos-de-una-foto-con-instrucciones-de-ia"
---

Context: In this photo of [photo description] I want to remove [objects to remove] (people in the background, cables, trash, signs). I'll use Nano Banana 2 or GPT Image 2.
Goal: The area should be filled in believably and the rest of the photo should stay unchanged.
Deliverable: 1) A main instruction that locates each object with clear references (position, color, relative size), describes what should fill the space (continue the brick wall, the grass, the sky), and ends with "keep everything else the same (main people, framing, lighting, colors)". 2) A step-by-step version, one object per instruction, for when a single pass fails. 3) What to check in the result: orphaned shadows and reflections, repeated patterns, blurry edges, warped text. 4) When manual tools like content-aware fill, the healing brush, or the clone stamp are the better choice.
Criteria: If the photo serves as evidence, a document, or a listing for a product or property, remind me not to remove elements that change what it shows.
Format: Numbered sections; instructions in blocks.
If any essential information is missing, ask me up to 3 questions before you start.

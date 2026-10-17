---
title: "Character Sheet and Consistent AI Portraits"
model: "ChatGPT · Claude · Gemini"
image: "ia-y-prompts.webp"
id: "IAP-0006"
lang: en
type: text
category: "AI & Prompt Generators"
category_slug: "ia-y-prompts"
subcategory: "Image prompts"
level: "advanced"
description: "Build a character's visual sheet and portrait prompts that keep the same identity across different scenes."
tags: ["characters", "consistency", "portrait", "image prompts", "photorealism"]
variables: ["project", "character description"]
translation: "/es/ia-y-prompts/ficha-de-personaje-y-retratos-consistentes-con-ia"
---

Context: I'm creating a character for [project] (novel, brand campaign, comic, video). Here is the description: [character description] (approximate age, features, personality, profession, wardrobe).
Goal: Generate portraits of this character that read as the same person in every image.
Deliverable: 1) A fixed visual sheet: specific facial features, hairstyle, build, base wardrobe, palette, and one signature accessory. 2) A main portrait prompt on a plain neutral background to use as a reference. 3) Four scene prompts (at work, a quiet moment, action, emotional close-up) that repeat the sheet word for word and change only setting, expression, and light. 4) How to use the main portrait as a reference image in Nano Banana 2 or GPT Image 2 to keep the identity.
Criteria: Write each image prompt as one flowing paragraph (scene, subject, details, technique or camera and lighting, mood), not a keyword list, which current models handle worse; phrase exclusions positively and describe techniques instead of naming living artists, brands, or copyrighted characters. For photorealism, include lens and aperture, light type, and real skin and fabric textures. Define the character through specific traits rather than generic labels, to avoid stereotypes. For Midjourney V8, append only --ar and, when useful, --raw or --stylize.
Format: The sheet as a list; then the prompts numbered in blocks.
If any essential information is missing, ask me up to 3 questions before you start.

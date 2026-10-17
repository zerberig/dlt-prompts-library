---
title: "Prompts for High Dynamic Range Scenes"
model: "ChatGPT · Claude · Gemini"
image: "ia-y-prompts.webp"
id: "IAP-0032"
lang: en
type: text
category: "AI & Prompt Generators"
category_slug: "ia-y-prompts"
subcategory: "Image prompts"
level: "advanced"
description: "Generate prompts for high-contrast scenes that keep detail in highlights and shadows without an overcooked HDR look."
tags: ["high dynamic range", "hdr", "lighting", "image prompts", "photorealism"]
variables: ["scene", "use of the image"]
translation: "/es/ia-y-prompts/prompts-para-escenas-de-alto-rango-dinamico"
---

Context: I want to generate photorealistic images of [scene] for [use of the image]. The scene has extreme light contrast (for example, a dark interior with a sunlit window, sunset backlight, or a night street with bright signs).
Goal: Images with detail in both highlights and shadows that look natural, not oversaturated and haloed like old-school HDR.
Deliverable: 1) Three prompts with different lighting situations for the same scene. Each describes the main light source, which details should show in the shadows and bright areas, lens and aperture, and the tonal treatment (smooth transitions, unblown sky, blacks with detail). 2) An instruction for Nano Banana 2 or GPT Image 2 that recovers highlights and shadows in an uploaded real photo without changing its content. 3) If I shoot it myself, how to capture a bracketed series and blend it.
Criteria: Describe the result in photographic terms ("open shadows with detail", "sky with readable clouds") instead of asking for "HDR", because that word tends to trigger the overdone look. Write each image prompt as one flowing paragraph (scene, subject, details, technique or camera and lighting, mood), not a keyword list, which current models handle worse; phrase exclusions positively and describe techniques instead of naming living artists, brands, or copyrighted characters. For Midjourney V8, append only --ar and, when useful, --raw or --stylize.
Format: Prompts in numbered blocks, and sections 2 and 3 as short steps.
If any essential information is missing, ask me up to 3 questions before you start.

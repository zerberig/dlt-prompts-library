---
title: "Prompts para escenas de alto rango dinámico"
model: "ChatGPT · Claude · Gemini"
image: "ia-y-prompts.webp"
id: "IAP-0032"
lang: es
type: texto
category: "IA y generadores de prompts"
category_slug: "ia-y-prompts"
subcategory: "Prompts de imagen"
level: "avanzado"
description: "Genera prompts para escenas con contraste extremo de luz que conservan detalle en luces y sombras sin look HDR exagerado."
tags: ["alto rango dinámico", "hdr", "iluminación", "prompts de imagen", "fotorrealismo"]
variables: ["escena", "uso de la imagen"]
translation: "/en/ia-y-prompts/prompts-for-high-dynamic-range-scenes"
---

Contexto: Quiero generar imágenes fotorrealistas de [escena] para [uso de la imagen]. La escena tiene contraste extremo de luz (por ejemplo, interior oscuro con ventana soleada, contraluz al atardecer o calle nocturna con letreros brillantes).
Objetivo: Imágenes con detalle tanto en las luces como en las sombras, que se vean naturales y no con el aspecto HDR sobresaturado y con halos.
Entregable: 1) Tres prompts con situaciones de luz distintas para la misma escena. Cada uno describe la fuente de luz principal, qué detalles deben verse en sombras y zonas brillantes, lente y apertura, y el tratamiento tonal (transiciones suaves, cielo sin quemar, negros con detalle). 2) Una instrucción para Nano Banana 2 o GPT Image 2 que recupere luces y sombras en una foto real subida sin cambiar su contenido. 3) Si tomo la foto yo, cómo hacer una serie de exposiciones y combinarlas.
Criterios: Describe el resultado en términos fotográficos ("sombras abiertas con detalle", "cielo con nubes legibles") en lugar de pedir "HDR", porque esa palabra suele provocar el aspecto exagerado. Escribe cada prompt de imagen como un párrafo fluido (escena, sujeto, detalles, técnica o cámara e iluminación, ambiente), no como lista de palabras clave, que los modelos actuales interpretan peor; expresa las exclusiones en positivo y describe técnicas en vez de nombrar artistas vivos, marcas o personajes con derechos. Para Midjourney V8, agrega al final solo --ar y, si aplica, --raw o --stylize.
Formato: Prompts en bloques numerados y las secciones 2 y 3 en pasos breves.
Si te falta información esencial, hazme hasta 3 preguntas antes de empezar.

# DLT Prompts Library

Biblioteca curada de **2,578 prompts** en **34 categorías**, en español y en inglés.

Fuente de verdad para la sección `/prompts` del sitio web de DLT Media.

## Estructura

```text
categories.json            34 categorías: slug, nombre ES/EN, tipo y conteo
es/<categoria>/<slug>.md   un prompt por archivo, en español
en/<categoria>/<slug>.md   su gemelo en inglés (mismo `id`)
covers/<categoria>.webp    portada de cada categoría (1200×800)
images/                    galería de imágenes generadas con su prompt
```

| Tipo | Categorías | Prompts | Modelos |
|---|---|---|---|
| Texto | 19 | 1,428 | ChatGPT · Claude · Gemini |
| Imagen | 10 | 900 | Nano Banana 2 · GPT Image 2 · Midjourney V8 |
| Video | 5 | 250 | Veo 3.1 · Kling 3.0 |

## Formato de cada prompt

Frontmatter con valores en JSON y el prompt como cuerpo:

```md
---
title: "Estrategia SEO de 12 meses lista para presentar"
model: "ChatGPT · Claude · Gemini"
image: "seo.webp"
id: "SEO-0068"
lang: es
type: texto
category: "SEO y posicionamiento"
category_slug: "seo"
subcategory: "Estrategia SEO"
level: "avanzado"
description: "…"
tags: ["estrategia seo", "plan anual"]
variables: ["tu producto o negocio", "público objetivo"]
translation: "/en/seo/12-month-seo-strategy-ready-to-present"
---

Contexto: Tengo [tu producto o negocio] dirigido a [público objetivo]. …
```

- `variables` lista, en orden, cada `[texto entre corchetes]` del prompt. El sitio las convierte en campos que el usuario llena antes de copiar; el orden es el mismo en ES y EN.
- Los prompts de imagen traen `aspect_ratio` y `mj_params`; los de video, `aspect_ratio` y `duration`.
- `level`: básico, intermedio o avanzado (beginner, intermediate, advanced en EN).

## Uso

El sitio clona este repo en build time (`npm run sync-prompts`) y genera un índice
ligero para búsqueda más un JSON por prompt con ambos idiomas.

Editar un prompt aquí → el sitio lo refleja en el siguiente build/deploy.
Si agregas una categoría, súmala a `categories.json` y agrega su portada en `covers/`.

## Licencia

Contenido propietario — DLT Media © 2026.

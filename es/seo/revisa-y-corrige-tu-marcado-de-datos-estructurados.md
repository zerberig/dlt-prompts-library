---
title: "Revisa y corrige tu marcado de datos estructurados"
model: "ChatGPT · Claude · Gemini"
image: "seo.webp"
id: "SEO-0057"
lang: es
type: texto
category: "SEO y posicionamiento"
category_slug: "seo"
subcategory: "SEO técnico"
level: "intermedio"
description: "Pega tu código schema y recibe errores, propiedades faltantes y una versión corregida en JSON-LD lista para usar."
tags: ["datos estructurados", "schema", "json-ld", "resultados enriquecidos", "seo técnico"]
variables: ["tipo de página", "código schema", "contenido de la página"]
translation: "/en/seo/review-and-fix-your-structured-data-markup"
---

Contexto: Esta página es de tipo [tipo de página] (producto, artículo, receta, negocio local, evento, etc.). Este es su marcado de datos estructurados actual: [código schema]. Y este es el contenido visible relevante de la página: [contenido de la página].
Objetivo: Quiero que el marcado sea válido, coherente con lo que ve el usuario y elegible para los resultados enriquecidos que apliquen.
Entregable: 1) Estado general: válido, con advertencias o con errores. 2) Errores de sintaxis y de tipos de datos (fechas en ISO 8601, precios numéricos, URLs absolutas). 3) Propiedades obligatorias y recomendadas que faltan, con por qué importan. 4) Datos del marcado que no coinciden con el contenido visible. 5) La versión corregida completa en JSON-LD.
Criterios: Marca solo información que aparece en la página, porque marcar contenido oculto o inventado puede generar una acción manual. Si tienes búsqueda web, confirma en la documentación actual de Google qué resultados enriquecidos sigue mostrando para este tipo. Recomiéndame validar el resultado final con la Prueba de resultados enriquecidos y el validador de schema.org.
Formato: Lista de hallazgos por categoría con su corrección, seguida del bloque de código final.
Si te falta información esencial, hazme hasta 3 preguntas antes de empezar.

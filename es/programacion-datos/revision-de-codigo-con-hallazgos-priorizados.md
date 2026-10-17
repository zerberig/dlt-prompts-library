---
title: "Revisión de código con hallazgos priorizados"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0002"
lang: es
type: texto
category: "Programación, vibe coding y datos"
category_slug: "programacion-datos"
subcategory: "Calidad de código"
level: "intermedio"
description: "Recibe una revisión de tu código sobre correctitud, legibilidad, patrones de diseño, rendimiento y seguridad, con correcciones."
tags: ["code review", "revisión de código", "patrones de diseño", "rendimiento", "seguridad"]
variables: ["lenguaje y framework", "qué hace este código", "estándares de tu equipo", "tu código"]
translation: "/en/programacion-datos/code-review-with-prioritized-findings"
---

Revisa este código como lo haría un desarrollador sénior antes de aprobar un pull request.
Contexto: Está escrito en [lenguaje y framework] y su función es [qué hace este código]. Seguimos estos estándares: [estándares de tu equipo].
[tu código]
Objetivo: Quiero saber qué corregir antes de fusionarlo y qué aprender para el siguiente.
Entregable: Hallazgos sobre correctitud, legibilidad, uso de patrones de diseño, rendimiento y seguridad. Para cada uno: el fragmento, el problema, por qué importa y la corrección. Al final, 2 o 3 cosas que el código hace bien.
Criterios: Ordena por impacto real, empezando por errores y riesgos de seguridad, y deja el estilo al final. Sugiere un patrón de diseño solo si simplifica el código, no por aplicarlo. Si algo depende de contexto que no ves, dilo en vez de suponer.
Formato: Tabla con las columnas Severidad (crítica, alta, media, baja), Ubicación, Problema y Sugerencia; debajo, los fragmentos corregidos en bloques de código.

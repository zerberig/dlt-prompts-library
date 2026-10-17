---
title: "Matriz de casos de prueba con valores límite y errores"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0012"
lang: es
type: texto
category: "Programación, vibe coding y datos"
category_slug: "programacion-datos"
subcategory: "Testing y QA"
level: "intermedio"
description: "Diseña casos de prueba con particiones, valores límite, errores y un set de regresión para una función o funcionalidad."
tags: ["casos de prueba", "valores límite", "regresión", "qa", "testing"]
variables: ["función o funcionalidad", "especificación o código", "cambios recientes"]
translation: "/en/programacion-datos/test-case-matrix-with-boundary-values-and-errors"
---

Contexto: Necesito probar [función o funcionalidad]. Esta es su especificación o su código:
[especificación o código]
Cambios recientes que podrían romper algo: [cambios recientes].
Objetivo: Cubrir los escenarios que de verdad pueden fallar, sin cientos de casos redundantes.
Entregable: 1) Las particiones de equivalencia y los valores límite de cada entrada. 2) Casos de prueba que cubran el camino feliz, límites, entradas inválidas, manejo de errores, permisos y, si aplica, concurrencia o rendimiento. 3) Un subconjunto de regresión para correr después de cada cambio. 4) Huecos o ambigüedades que encuentres en la especificación.
Criterios: Cada caso prueba una sola cosa y tiene un resultado esperado verificable. Prioriza por probabilidad de falla e impacto, porque así el equipo sabe qué ejecutar primero si hay poco tiempo.
Formato: Tabla con las columnas ID, Tipo, Entrada o condición, Resultado esperado, Prioridad y Regresión (sí/no).
Si te falta información esencial, hazme hasta 3 preguntas antes de empezar.

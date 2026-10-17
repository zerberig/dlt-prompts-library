---
title: "Plantillas de issues y pull requests para tu repositorio"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0043"
lang: es
type: texto
category: "Programación, vibe coding y datos"
category_slug: "programacion-datos"
subcategory: "Equipos de desarrollo"
level: "intermedio"
description: "Obtén formularios YAML para bugs y funciones, plantilla de PR y etiquetas para que cada reporte llegue completo."
tags: ["github", "pull requests", "issues", "plantillas", "open source"]
variables: ["tu proyecto", "tipo de proyecto", "quién contribuye"]
translation: "/en/programacion-datos/issue-and-pull-request-templates-for-your-repo"
---

Contexto: Mantengo [tu proyecto] en GitHub, un proyecto [tipo de proyecto] (interno, open source, librería, app). Recibimos contribuciones de [quién contribuye] y hoy los reportes llegan incompletos o con poca información.
Objetivo: Que cada issue y cada pull request traiga lo necesario para clasificarlo y revisarlo sin ir y venir con preguntas.
Entregable: 1) Un formulario de issue para reporte de bug en YAML (.github/ISSUE_TEMPLATE/bug_report.yml) con pasos para reproducir, comportamiento esperado y actual, versión y entorno, y severidad. 2) Un formulario para solicitar funciones. 3) El archivo config.yml para dirigir las preguntas generales a otro canal. 4) Un PULL_REQUEST_TEMPLATE.md con tipo de cambio, resumen, issue relacionado, cómo se probó y checklist. 5) Una propuesta de etiquetas para tipo, prioridad y estado.
Criterios: Campos obligatorios solo donde de verdad hacen falta, porque los formularios largos desaniman a contribuir. Textos de ayuda breves con ejemplos. Sintaxis válida para los formularios de issues de GitHub.
Formato: Cada archivo en su propio bloque de código con la ruta como título; las etiquetas en una tabla con Nombre, Color y Uso.
Si te falta información esencial, hazme hasta 3 preguntas antes de empezar.

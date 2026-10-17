---
title: "Guía de calidad de código para tu equipo"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0007"
lang: es
type: texto
category: "Programación, vibe coding y datos"
category_slug: "programacion-datos"
subcategory: "Calidad de código"
level: "intermedio"
description: "Crea una guía de buenas prácticas, una checklist de revisión y un plan de análisis estático para elevar la calidad."
tags: ["calidad de código", "buenas prácticas", "checklist", "análisis estático", "mantenibilidad"]
variables: ["tu producto", "stack y tamaño del equipo", "problemas frecuentes"]
translation: "/en/programacion-datos/code-quality-playbook-for-your-team"
---

Contexto: Mantenemos [tu producto] con [stack y tamaño del equipo]. Los problemas que más se repiten en el código son: [problemas frecuentes] (por ejemplo, funciones enormes, pocas pruebas o errores que regresan).
Objetivo: Acordar prácticas de calidad que el equipo realmente aplique en su día a día y que reduzcan errores y tiempo de mantenimiento.
Entregable:
1. Entre 10 y 12 prácticas priorizadas, cada una con por qué importa y un ejemplo breve de antes y después.
2. Una checklist de revisión de código de máximo 15 puntos (calidad, mantenibilidad, pruebas, seguridad).
3. Herramientas de análisis estático, formateo y cobertura para nuestro stack, y en qué punto del flujo correrlas (editor, pre-commit, CI).
4. Un plan de adopción gradual de 4 semanas.
Criterios: Prioriza lo que ataca los problemas que mencioné y automatiza todo lo posible, porque las reglas que dependen de la memoria se olvidan. Si tienes búsqueda web, verifica que las herramientas recomendadas sigan mantenidas.
Formato: Secciones numeradas; la checklist como lista de casillas lista para pegar en la plantilla de pull request.
Si te falta información esencial, hazme hasta 3 preguntas antes de empezar.

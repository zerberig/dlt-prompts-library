---
title: "Plan de refactorización para código difícil de mantener"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0057"
lang: es
type: texto
category: "Programación, vibe coding y datos"
category_slug: "programacion-datos"
subcategory: "Código"
level: "avanzado"
description: "Detecta code smells, recibe un ejemplo refactorizado y un plan por etapas para mejorar el código sin frenar entregas."
tags: ["refactorización", "code smells", "mantenibilidad", "deuda técnica", "código limpio"]
variables: ["lenguaje y framework", "tamaño y antigüedad del proyecto", "problemas actuales", "fragmento de código representativo"]
translation: "/en/programacion-datos/refactoring-plan-for-hard-to-maintain-code"
---

Contexto: Trabajo en un proyecto en [lenguaje y framework] de [tamaño y antigüedad del proyecto]. Los problemas que más nos afectan son [problemas actuales] (por ejemplo: clases enormes, código duplicado, cambios simples que rompen otras partes, pocas pruebas). Te comparto un fragmento representativo:
[fragmento de código representativo]
Objetivo: Mejorar la mantenibilidad y la legibilidad de forma gradual, sin detener la entrega de funcionalidades ni romper lo que ya funciona.
Entregable: 1) Los code smells que detectas en el fragmento y la técnica de refactorización adecuada para cada uno (extraer método, introducir objeto de parámetros, reemplazar condicional con polimorfismo, etc.). 2) El fragmento refactorizado como ejemplo. 3) Un plan de refactorización por etapas para todo el proyecto, priorizado por impacto y riesgo. 4) Convenciones y una estructura de carpetas que el equipo pueda adoptar. 5) Herramientas para detectar problemas automáticamente (linters, análisis estático, métricas de complejidad).
Criterios: Cada refactorización debe conservar el comportamiento; indica qué pruebas de caracterización escribir antes de tocar código que no tiene pruebas. Prioriza las zonas que cambian con más frecuencia, porque ahí la mejora rinde más.
Formato: Tabla de hallazgos con columnas Problema, Ubicación, Técnica y Prioridad; el código en bloques y el plan por etapas en lista numerada.
Si te falta información esencial, hazme hasta 3 preguntas antes de empezar.

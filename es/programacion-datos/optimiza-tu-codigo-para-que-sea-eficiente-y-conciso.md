---
title: "Optimiza tu código para que sea eficiente y conciso"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0045"
lang: es
type: texto
category: "Programación, vibe coding y datos"
category_slug: "programacion-datos"
subcategory: "Código"
level: "intermedio"
description: "Recibe un diagnóstico de rendimiento, la versión mejorada del código y cómo medir que la mejora es real."
tags: ["optimización", "rendimiento", "código limpio", "complejidad", "profiling"]
variables: ["lenguaje", "contexto de ejecución", "resultados de profiling", "tu código"]
translation: "/en/programacion-datos/optimize-a-code-snippet-for-speed-and-clarity"
---

Contexto: Este fragmento en [lenguaje] se ejecuta en [contexto de ejecución] (por ejemplo: un endpoint con mucho tráfico, un script de procesamiento de datos, una función que se llama dentro de un ciclo). Datos de profiling o tiempos medidos, si los tengo: [resultados de profiling].
Código:
[tu código]
Objetivo: Mejorar el rendimiento y simplificar el código sin cambiar su comportamiento.
Entregable: 1) Diagnóstico breve: dónde se va el tiempo o la memoria y la complejidad actual. 2) La versión mejorada completa. 3) Lista de cambios con el impacto esperado de cada uno. 4) Cómo medir la mejora con un benchmark sencillo y pruebas para confirmar que el resultado no cambió.
Criterios: Prioriza los cambios de mayor impacto (algoritmo y estructuras de datos, consultas o E/S repetidas) antes que las micro-optimizaciones. Cuida la legibilidad: si una optimización vuelve el código difícil de mantener, preséntala como opcional y explica el costo. Conserva el estilo del código original. Indica qué mejoras hay que confirmar midiendo en lugar de darlas por hechas.
Formato: Secciones numeradas, código en bloques y la lista de cambios en tabla con columnas Cambio, Antes, Después e Impacto esperado.
Si te falta información esencial, hazme hasta 3 preguntas antes de empezar.

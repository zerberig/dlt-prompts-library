---
title: "Diagnóstico de rendimiento y plan de optimización"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0009"
lang: es
type: texto
category: "Programación, vibe coding y datos"
category_slug: "programacion-datos"
subcategory: "Rendimiento"
level: "avanzado"
description: "Analiza métricas y perfiles de tu sistema para encontrar cuellos de botella y priorizar optimizaciones."
tags: ["rendimiento", "optimización", "cuellos de botella", "profiling", "pruebas de carga"]
variables: ["tu producto", "arquitectura y stack", "síntoma", "métricas, perfiles o logs"]
translation: "/en/programacion-datos/performance-diagnosis-and-optimization-plan"
---

Contexto: [tu producto] corre sobre [arquitectura y stack]. El síntoma: [síntoma] (por ejemplo, la API tarda más de 2 segundos con más de 500 usuarios simultáneos). Estos son los datos que tengo:
[métricas, perfiles o logs]
Objetivo: Encontrar las causas reales de la lentitud o del consumo excesivo de recursos y decidir qué optimizar primero.
Entregable:
1. Lectura de los datos: qué indican sobre CPU, memoria, entrada/salida, base de datos y red bajo distintas cargas.
2. Cuellos de botella probables, ordenados por impacto, con la evidencia de cada uno.
3. Optimizaciones propuestas en código, base de datos (índices, consultas, conexiones) e infraestructura (caché, escalado), con esfuerzo e impacto esperado.
4. Pruebas de carga y métricas para validar cada cambio antes y después.
5. Datos adicionales que debería recolectar si el diagnóstico no es concluyente, y con qué herramientas.
Criterios: Basa cada conclusión en los datos que te di y separa lo comprobado de las hipótesis, porque optimizar a ciegas suele mover el cuello de botella sin resolverlo. Marca como estimación cualquier mejora porcentual que no puedas respaldar.
Formato: Secciones numeradas; las optimizaciones en una tabla con las columnas Cambio, Área, Impacto, Esfuerzo y Cómo medirlo.
Si te falta información esencial, hazme hasta 3 preguntas antes de empezar.

---
title: "Plan para un modelo de mantenimiento predictivo"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0019"
lang: es
type: texto
category: "Programación, vibe coding y datos"
category_slug: "programacion-datos"
subcategory: "Ciencia de datos"
level: "avanzado"
description: "Diseña paso a paso un modelo que predice fallas de equipo con datos de sensores, desde los datos hasta la puesta en marcha."
tags: ["mantenimiento predictivo", "machine learning", "sensores", "ciencia de datos", "industria"]
variables: ["tipo de equipo", "datos de sensores disponibles", "historial de fallas", "herramientas del equipo"]
translation: "/en/programacion-datos/plan-for-a-predictive-maintenance-model"
---

Contexto: Queremos predecir fallas en [tipo de equipo] antes de que ocurran. Datos de sensores disponibles: [datos de sensores disponibles] (por ejemplo, temperatura, vibración, presión o corriente, y su frecuencia de muestreo). Historial de fallas y mantenimiento: [historial de fallas]. Herramientas del equipo: [herramientas del equipo].
Objetivo: Un plan de proyecto realista para pasar de los datos crudos a alertas útiles para el área de mantenimiento.
Entregable:
1. Definición del problema: qué predecir (falla en las próximas N horas, vida útil restante o anomalía) y por qué, según mis datos.
2. Preparación de datos: limpieza, sincronización de sensores, manejo de faltantes y cómo etiquetar las fallas.
3. Ingeniería de variables: ventanas de tiempo, estadísticas móviles, tendencias y variables del dominio.
4. Modelos candidatos, desde una línea base simple hasta modelos más complejos, y cuándo conviene cada uno.
5. Validación: separación temporal de los datos, métricas (recall, precisión, tiempo de anticipación) y costo de las falsas alarmas frente a las fallas no detectadas.
6. Puesta en marcha: cómo llegan las alertas al equipo de mantenimiento, monitoreo del modelo y reentrenamiento.
7. Riesgos y qué hacer si hay pocas fallas registradas.
Criterios: Empieza por lo más simple que pueda funcionar, porque en mantenimiento la confianza de los técnicos importa tanto como la precisión. Evita fugas de información del futuro en la validación.
Formato: Secciones numeradas con viñetas y un ejemplo breve de código en Python para la ingeniería de variables.
Si te falta información esencial, hazme hasta 3 preguntas antes de empezar.

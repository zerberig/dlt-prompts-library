---
title: "Refactorización incremental de código heredado"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0024"
lang: es
type: texto
category: "Programación, vibe coding y datos"
category_slug: "programacion-datos"
subcategory: "Calidad de código"
level: "avanzado"
description: "Planea por etapas la refactorización de un sistema heredado, sin romper funcionalidad y mejorando mantenibilidad y rendimiento."
tags: ["refactorización", "código heredado", "deuda técnica", "mantenibilidad", "rendimiento"]
variables: ["tu producto o módulo", "problemas actuales", "cobertura de pruebas actual", "restricciones"]
translation: "/en/programacion-datos/incremental-refactoring-strategy-for-legacy-code"
---

Contexto: Necesitamos refactorizar [tu producto o módulo]. Problemas actuales: [problemas actuales] (por ejemplo, cambios lentos y riesgosos, errores recurrentes o bajo rendimiento). Cobertura de pruebas actual: [cobertura de pruebas actual]. Restricciones: [restricciones] (no podemos detener nuevas funciones, equipo pequeño, fecha límite).
Objetivo: Mejorar la mantenibilidad y el rendimiento sin una reescritura total y sin romper lo que hoy funciona.
Entregable:
1. Diagnóstico: qué partes refactorizar primero según frecuencia de cambios, número de errores y riesgo.
2. Red de seguridad: pruebas de caracterización para fijar el comportamiento actual antes de tocar el código.
3. Estrategia por etapas (por ejemplo, patrón strangler fig, extracción de módulos o introducción de interfaces), con entregables pequeños que se puedan liberar por separado.
4. Mejoras de rendimiento a incluir y cómo medirlas antes y después.
5. Métricas de éxito y cómo explicarle a negocio el valor de este trabajo.
Criterios: Cada etapa debe dejar el sistema funcionando y en producción, porque las refactorizaciones largas en una rama aparte rara vez se terminan. Señala cuándo conviene no refactorizar algo.
Formato: Secciones numeradas; las etapas en una tabla con Etapa, Cambio, Riesgo, Cómo validarlo y Duración estimada.
Si te falta información esencial, hazme hasta 3 preguntas antes de empezar.

---
title: "Arquitectura escalable y tolerante a fallos"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0005"
lang: es
type: texto
category: "Programación, vibe coding y datos"
category_slug: "programacion-datos"
subcategory: "Arquitectura"
level: "avanzado"
description: "Diseña una arquitectura con estimación de carga, escalado, caché, particionado y manejo de fallas, con sus compromisos."
tags: ["arquitectura de software", "escalabilidad", "alta disponibilidad", "tolerancia a fallos", "sistemas distribuidos"]
variables: ["tu producto", "carga esperada", "requisitos clave", "stack o restricciones"]
translation: "/en/programacion-datos/scalable-fault-tolerant-software-architecture"
---

Contexto: Estoy diseñando la arquitectura de [tu producto]. Carga esperada hoy y en 2 años: [carga esperada]. Requisitos clave: [requisitos clave] (disponibilidad, latencia, seguridad, cumplimiento). Stack o restricciones: [stack o restricciones].
Objetivo: Una arquitectura que aguante el crecimiento y siga funcionando cuando falle una pieza, sin pagar de más por una escala que todavía no necesito.
Entregable:
1. Estimación rápida de capacidad (solicitudes por segundo, almacenamiento, ancho de banda) con los supuestos explícitos.
2. Dos opciones de arquitectura, una más simple y otra para mayor escala, con componentes y flujo de datos.
3. Decisiones de escalabilidad: balanceo de carga, caché, particionado de datos, colas y procesamiento asíncrono.
4. Análisis de fallas: qué pasa si cae cada componente crítico, cómo se detecta y cómo se recupera.
5. Recomendación final y en qué momento convendría pasar a la siguiente etapa.
Criterios: Justifica cada decisión con su compromiso (costo, complejidad, consistencia), porque no existe una arquitectura correcta sin contexto. Marca como estimación cualquier cifra de capacidad o costo que no puedas respaldar.
Formato: Secciones numeradas, una tabla comparativa de las dos opciones y un diagrama en Mermaid de la opción recomendada.
Si te falta información esencial, hazme hasta 3 preguntas antes de empezar.

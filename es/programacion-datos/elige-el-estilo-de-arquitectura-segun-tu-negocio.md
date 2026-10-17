---
title: "Elige el estilo de arquitectura según tu negocio"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0032"
lang: es
type: texto
category: "Programación, vibe coding y datos"
category_slug: "programacion-datos"
subcategory: "Arquitectura"
level: "avanzado"
description: "Traduce tus requisitos de negocio en atributos de calidad, compara estilos y despliegues y documenta la decisión en ADR."
tags: ["arquitectura de software", "adr", "microservicios", "requisitos de negocio", "nube"]
variables: ["descripción del sistema", "tipo de negocio", "requisitos clave", "restricciones de equipo, presupuesto o infraestructura"]
translation: "/en/programacion-datos/choose-an-architecture-style-that-fits-your-business"
---

Contexto: Vamos a construir [descripción del sistema] para [tipo de negocio]. Los requisitos de negocio más importantes son [requisitos clave] (por ejemplo: lanzar en 4 meses, cumplir normativa de datos, operar en varias ciudades). Tenemos estas restricciones: [restricciones de equipo, presupuesto o infraestructura], y debemos decidir entre nube, servidores propios o un esquema híbrido.
Objetivo: Tomar las decisiones de arquitectura de fondo con argumentos claros que pueda presentar a dirección y al equipo técnico.
Entregable: 1) Los 4 a 6 atributos de calidad prioritarios (escalabilidad, confiabilidad, seguridad, costo, velocidad de entrega, etc.) derivados de los requisitos, en orden de importancia. 2) Comparación de 2 o 3 estilos de arquitectura viables (por ejemplo: monolito modular, microservicios, serverless) contra esos atributos. 3) Comparación de despliegue en nube, local e híbrido. 4) La recomendación final y 3 registros de decisión de arquitectura (ADR) con contexto, decisión, alternativas y consecuencias.
Criterios: Conecta cada recomendación con un requisito de negocio concreto, porque así la decisión se puede defender y revisar después. Sé explícito con los costos y riesgos de la opción recomendada. Indica qué señales harían reconsiderar la decisión en el futuro.
Formato: Tablas comparativas con calificación del 1 al 5 y una línea de justificación en las celdas clave; los ADR en Markdown, cada uno con su encabezado.
Si te falta información esencial, hazme hasta 3 preguntas antes de empezar.

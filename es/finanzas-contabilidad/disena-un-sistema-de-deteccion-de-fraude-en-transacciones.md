---
title: "Diseña un sistema de detección de fraude en transacciones"
model: "ChatGPT · Claude · Gemini"
image: "finanzas-contabilidad.webp"
id: "FIN-0038"
lang: es
type: texto
category: "Finanzas y contabilidad"
category_slug: "finanzas-contabilidad"
subcategory: "Producto fintech"
level: "avanzado"
description: "Obtén la arquitectura de un sistema de detección de fraude: fuentes de datos, reglas, modelos, alertas y métricas."
tags: ["detección de fraude", "transacciones", "machine learning", "riesgo", "arquitectura"]
variables: ["nombre de tu empresa", "industria", "volumen mensual de transacciones", "cómo lo detectan hoy", "tipos de fraude frecuentes"]
translation: "/en/finanzas-contabilidad/design-a-transaction-fraud-detection-system"
---

Contexto: [nombre de tu empresa] es una empresa de [industria] que procesa alrededor de [volumen mensual de transacciones]. Hoy el fraude se detecta con [cómo lo detectan hoy] y los tipos de fraude que más nos afectan son: [tipos de fraude frecuentes].
Objetivo: Quiero un sistema por capas que detecte más fraude sin bloquear a clientes legítimos, porque cada falso positivo nos cuesta ventas y confianza.
Entregable: 1) Fuentes de datos a integrar (transacción, cuenta, dispositivo, ubicación, comportamiento, listas internas) y qué señal aporta cada una. 2) Arquitectura por capas: reglas en tiempo real, modelo de puntuación de riesgo, revisión manual y retroalimentación. 3) Diez reglas iniciales concretas para mi tipo de negocio. 4) El enfoque de modelado: variables candidatas, cómo etiquetar casos, cómo manejar el desbalance de clases y cada cuánto reentrenar. 5) Flujo de alertas y casos con tiempos de respuesta. 6) Métricas: tasa de detección, falsos positivos, pérdidas evitadas, tiempo de revisión. 7) Consideraciones de privacidad y cumplimiento.
Criterios: Empieza por lo que se puede implementar en 90 días y deja lo avanzado para una segunda fase. Justifica cada umbral o regla con la señal de riesgo que busca. Señala qué requisitos regulatorios y de protección de datos debo verificar con mi equipo legal.
Formato: Secciones numeradas, las reglas en una tabla con las columnas Regla, Señal, Acción y Riesgo de falso positivo, y un plan por fases al final.
Si te falta información esencial, hazme hasta 3 preguntas antes de empezar.

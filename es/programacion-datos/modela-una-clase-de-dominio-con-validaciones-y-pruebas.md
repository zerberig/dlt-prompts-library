---
title: "Modela una clase de dominio con validaciones y pruebas"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0067"
lang: es
type: texto
category: "Programación, vibe coding y datos"
category_slug: "programacion-datos"
subcategory: "Fundamentos"
level: "intermedio"
description: "Practica diseño orientado a objetos con diagrama de clases, implementación encapsulada, pruebas y extensiones."
tags: ["programación orientada a objetos", "clases", "pruebas unitarias", "diseño de software", "práctica de código"]
variables: ["lenguaje", "entidad o sistema"]
translation: "/en/programacion-datos/model-a-domain-class-with-validation-and-tests"
---

Contexto: Estoy practicando diseño orientado a objetos en [lenguaje]. Quiero modelar [entidad o sistema] (por ejemplo: una cuenta bancaria con depósitos, retiros y consulta de saldo).
Objetivo: Una implementación de referencia que muestre buenas prácticas de diseño, no solo código que funcione.
Entregable: 1) Un diagrama de clases en Mermaid con atributos, métodos y relaciones. 2) La implementación completa con encapsulamiento (atributos privados y validaciones en los métodos) y manejo de errores con excepciones o resultados explícitos (por ejemplo: un retiro mayor al saldo o un monto negativo). 3) Un programa breve de ejemplo que use la clase. 4) Pruebas unitarias para los casos normales y de error. 5) 2 extensiones sugeridas para seguir practicando (por ejemplo: historial de movimientos, tipos de cuenta con herencia o composición).
Criterios: Usa tipos adecuados para el dominio (para dinero, un tipo decimal en lugar de punto flotante, porque evita errores de redondeo). Código idiomático del lenguaje, con nombres claros y comentarios solo donde aporten. Explica brevemente cada decisión de diseño.
Formato: Secciones numeradas, con el diagrama, el código y las pruebas en bloques separados.

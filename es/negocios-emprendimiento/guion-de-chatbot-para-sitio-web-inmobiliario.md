---
title: "Guion de chatbot para sitio web inmobiliario"
model: "ChatGPT · Claude · Gemini"
image: "negocios-emprendimiento.webp"
id: "NEG-0040"
lang: es
type: texto
category: "Negocios y emprendimiento"
category_slug: "negocios-emprendimiento"
subcategory: "Bienes raíces"
level: "avanzado"
description: "Diseña los flujos de un chatbot que responde dudas frecuentes y califica prospectos para tu inmobiliaria."
tags: ["chatbot", "inmobiliaria", "prospectos", "atención al cliente", "sitio web"]
variables: ["nombre de tu inmobiliaria", "tipo de propiedades", "ciudad o zona"]
translation: "/en/negocios-emprendimiento/chatbot-script-for-a-real-estate-website"
---

Contexto: Tengo [nombre de tu inmobiliaria], que vende y renta [tipo de propiedades] en [ciudad o zona]. Quiero un asistente de chat en mi sitio web que atienda a los visitantes, también fuera de horario.
Objetivo: Resolver dudas frecuentes al instante y convertir a los visitantes interesados en prospectos calificados que mi equipo pueda contactar.
Entregable: 1) Mensaje de bienvenida y menú inicial. 2) Flujos de conversación para comprar, rentar, vender una propiedad y dudas generales. 3) Preguntas de calificación (presupuesto, zona, plazo, forma de pago) en el orden en que conviene hacerlas. 4) 10 preguntas frecuentes sobre el proceso de compra con respuestas breves. 5) Reglas para pasar la conversación a un asesor humano y un mensaje de cierre que pida datos de contacto con consentimiento.
Criterios: Tono cordial y breve, máximo 2-3 oraciones por mensaje, porque en un chat los bloques largos se abandonan. El bot no da asesoría legal ni fiscal ni promete precios o plusvalías; en esos casos ofrece hablar con un asesor. Las respuestas sobre trámites deben ser generales y aclarar que los requisitos varían según el país.
Formato: Cada flujo como diálogo con etiquetas Bot y Usuario, con las ramas indicadas como "Si el usuario responde…".
Si te falta información esencial, hazme hasta 3 preguntas antes de empezar.

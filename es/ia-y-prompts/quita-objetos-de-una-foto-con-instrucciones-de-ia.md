---
title: "Quita objetos de una foto con instrucciones de IA"
model: "ChatGPT · Claude · Gemini"
image: "ia-y-prompts.webp"
id: "IAP-0031"
lang: es
type: texto
category: "IA y generadores de prompts"
category_slug: "ia-y-prompts"
subcategory: "Edición de fotos"
level: "intermedio"
description: "Escribe instrucciones de inpainting que eliminan distracciones de una foto y rellenan el fondo de forma creíble."
tags: ["eliminar objetos", "inpainting", "edición con ia", "nano banana 2", "retoque"]
variables: ["descripción de la foto", "objetos a eliminar"]
translation: "/en/ia-y-prompts/remove-objects-from-a-photo-with-ai-instructions"
---

Contexto: En esta foto de [descripción de la foto] quiero quitar [objetos a eliminar] (personas al fondo, cables, basura, letreros). Usaré Nano Banana 2 o GPT Image 2.
Objetivo: Que el área quede rellena de forma creíble y que el resto de la foto no cambie.
Entregable: 1) Una instrucción principal que ubique cada objeto con referencias claras (posición, color, tamaño relativo), describa con qué debe rellenarse el espacio (continuar la pared de ladrillo, el pasto, el cielo) y termine con "mantén todo lo demás igual (personas principales, encuadre, iluminación, colores)". 2) Una versión dividida en pasos, un objeto por instrucción, para cuando la pasada única falle. 3) Qué revisar en el resultado: sombras y reflejos huérfanos, patrones repetidos, bordes borrosos, texto deformado. 4) Cuándo conviene usar herramientas manuales como relleno según contenido, pincel corrector o tampón de clonar.
Criterios: Si la foto se usa como evidencia, documento o anuncio de un producto o inmueble, recuérdame no eliminar elementos que cambien lo que muestra.
Formato: Secciones numeradas; instrucciones en bloques.
Si te falta información esencial, hazme hasta 3 preguntas antes de empezar.

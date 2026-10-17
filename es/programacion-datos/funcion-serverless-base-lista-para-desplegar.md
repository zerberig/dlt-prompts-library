---
title: "Función serverless base lista para desplegar"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0010"
lang: es
type: texto
category: "Programación, vibe coding y datos"
category_slug: "programacion-datos"
subcategory: "DevOps y nube"
level: "intermedio"
description: "Genera el código base de una función serverless con dependencias, infraestructura como código, pruebas y despliegue."
tags: ["serverless", "aws lambda", "infraestructura como código", "nube", "boilerplate"]
variables: ["proveedor y servicio", "lenguaje", "qué debe hacer la función", "disparador"]
translation: "/en/programacion-datos/deploy-ready-serverless-function-boilerplate"
---

Contexto: Necesito una función serverless en [proveedor y servicio] (por ejemplo, AWS Lambda, Google Cloud Functions o Azure Functions) escrita en [lenguaje]. Debe [qué debe hacer la función] y se activa con [disparador] (petición HTTP, mensaje en una cola, archivo nuevo o un horario).
Objetivo: Tener una base limpia que pueda desplegar hoy y extender sin rehacer la estructura.
Entregable:
1. Estructura de carpetas del proyecto.
2. El handler con validación de la entrada, manejo de errores y logs estructurados.
3. Archivo de dependencias.
4. Plantilla de infraestructura como código (por ejemplo, SAM, Terraform o la herramienta nativa del proveedor) con permisos mínimos.
5. Una prueba unitaria y cómo probar la función en local.
6. Comandos para desplegar y cómo manejar variables de entorno y secretos.
Criterios: Aplica el principio de mínimo privilegio en los permisos y nunca pongas secretos en el código, porque son los errores de seguridad más comunes en serverless. Usa runtimes y versiones con soporte vigente; si tienes búsqueda web, verifícalos.
Formato: Cada archivo en su propio bloque de código con su ruta como título, y una explicación breve después de cada uno.

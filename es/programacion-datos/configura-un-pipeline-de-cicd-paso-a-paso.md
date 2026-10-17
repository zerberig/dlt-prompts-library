---
title: "Configura un pipeline de CI/CD paso a paso"
model: "ChatGPT · Claude · Gemini"
image: "programacion-datos.webp"
id: "DEV-0023"
lang: es
type: texto
category: "Programación, vibe coding y datos"
category_slug: "programacion-datos"
subcategory: "DevOps y nube"
level: "avanzado"
description: "Obtén el archivo de configuración comentado y un tutorial para automatizar build, pruebas y despliegue con tu herramienta."
tags: ["ci/cd", "github actions", "automatización", "despliegue", "devops"]
variables: ["tu proyecto y stack", "herramienta de CI/CD", "dónde se despliega"]
translation: "/en/programacion-datos/set-up-a-cicd-pipeline-step-by-step"
---

Contexto: Tengo [tu proyecto y stack] y quiero automatizar su integración y entrega continuas con [herramienta de CI/CD] (por ejemplo, GitHub Actions, GitLab CI o Jenkins). Se despliega en [dónde se despliega].
Objetivo: Que cada cambio se pruebe solo y que desplegar sea un paso confiable y repetible, sin comandos manuales.
Entregable:
1. El archivo de configuración completo y comentado, con estas etapas: instalación de dependencias con caché, lint, pruebas, build, análisis de seguridad de dependencias y despliegue.
2. Disparadores: qué corre en cada pull request, qué corre al fusionar a la rama principal y cómo se aprueba el paso a producción.
3. Manejo de secretos y variables por entorno.
4. Tutorial paso a paso para ponerlo a funcionar por primera vez.
5. Errores comunes en la primera ejecución y cómo resolverlos.
Criterios: Un pipeline rápido (pruebas en paralelo, caché de dependencias), porque un pipeline lento termina por saltarse. Usa versiones vigentes de las acciones o imágenes; si tienes búsqueda web, verifícalas.
Formato: El archivo de configuración en un bloque de código y después las secciones numeradas.
Si te falta información esencial, hazme hasta 3 preguntas antes de empezar.

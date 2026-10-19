# 📚 Entrenador Interactivo RCAA2

Una herramienta web diseñada para estudiantes y profesionales de bibliotecología que permite practicar la catalogación descriptiva y la puntuación prescrita ISBD para monografías impresas, 
basándose en las **Reglas de Catalogación Angloamericanas (2ª edición, revisión de 2002, actualización de 2003)**.

## Objetivo del Proyecto
El estudio de la catalogación suele ser frustrante al principio por la rigurosidad de los espacios y signos de puntuación. 
Este proyecto funciona como un "validador estricto" en tiempo real que evalúa el asiento bibliográfico a medida que se tipea, marcando errores conceptuales, de sintaxis y el uso correcto de mayúsculas (Apéndice A).

## Características
- **División por Áreas ISBD:** Entradas separadas para Título/Mención de responsabilidad, Edición, Publicación, Descripción física, Serie e ISBN.
- **Validación en Tiempo Real:** Motor de Reglas basado en Expresiones Regulares (Regex) que detecta errores comunes
  (ej. espacios faltantes antes de un punto y coma, uso incorrecto de decimales en centímetros, omisión de la barra diagonal).
- **Vista Previa Unificada:** Genera una ficha catalográfica tradicional con tipografía monoespaciada de forma dinámica.
- **Casos de Prueba:** Incluye botones para cargar un ejemplo perfecto y un caso lleno de trampas comunes de examen.

## Tecnologías Utilizadas
- **Frontend:** HTML5, CSS3, Vanilla JavaScript (sin frameworks).
- **Lógica de Validación:** JavaScript nativo (Regex y manipulación del DOM).
- **Despliegue (Hosting):** Cloudflare Pages (Serverless).
-  **Herramientas de Desarrollo:** Gemini (generación de Expresiones Regulares y refactorización de código).

## Autoras
Desarrollado y mantenido por:
- **Sofía Escudero (data engineer y estudiante de Ciencias de Datos IFTS N°18)** - [GitHub](https://github.com/SofiaEscudero13)
- **Silvina Carreño (docente y estudiante de Bibliotecología IFTS N°13)** - [LinkedIn](https://www.linkedin.com/in/silvina-antonella-carreno/)

---
*Herramienta de código abierto creada para facilitar la práctica en la cursada de Catalogación.*

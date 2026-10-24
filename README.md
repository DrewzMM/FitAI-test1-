# FIT·AI

Prototipo de una aplicación web que recomienda microciclos de entrenamiento personalizados según el objetivo, el nivel de condición física y la disponibilidad del usuario. Interfaz inspirada en plataformas de streaming.

Desarrollado como parte de una investigación sobre el uso de inteligencia artificial generativa en la planificación automatizada de microciclos de entrenamiento.

## Funcionalidades

- Onboarding en 4 pasos: objetivo, nivel, disponibilidad y nombre
- Generación de un microciclo semanal personalizado
- Detalle de cada sesión: ejercicios, series, repeticiones y descansos
- Consejo técnico por sesión
- Marcado de sesiones completadas

## Cómo usarlo

1. Descarga o clona este repositorio
2. Abre el archivo `index.html` en tu navegador

No requiere instalación.

## Sobre la IA

El prototipo está diseñado para llamar a la API de Anthropic (Claude) y generar el plan. Para que esto funcione fuera de Claude se necesita una API key y un pequeño servidor que la proteja (nunca se debe escribir la clave directamente en `index.html`).

Mientras no esté configurada, la aplicación muestra un plan de respaldo predefinido para que la interfaz siga funcionando.

## Tecnologías

HTML, CSS y JavaScript puro.

## Estado del proyecto

Prototipo en desarrollo. Pendiente: integración segura de la API y almacenamiento de datos de los participantes del estudio.

## Autor

DrewzMM

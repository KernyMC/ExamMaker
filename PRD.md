# Documento de Requisitos del Producto (PRD)

## Nombre del Proyecto
Exam Maker

## Descripción General
Exam Maker es una aplicación web interactiva diseñada para la creación, gestión y simulación de exámenes tipo test. Permite a los usuarios cargar, visualizar y responder preguntas de opción múltiple, facilitando la preparación de exámenes y la autoevaluación.

## Público Objetivo
- Estudiantes que desean practicar para exámenes.
- Profesores que necesitan generar y administrar exámenes.
- Cualquier persona interesada en crear o resolver cuestionarios de opción múltiple.

## Funcionalidades Principales
- **Carga de Exámenes:** Permite cargar archivos de preguntas en formato .txt (Aiken) o .docx.
- **Visualización de Preguntas:** Muestra las preguntas en dos vistas: tipo Moodle (una por una) y tipo lista (todas a la vez).
- **Randomización:** Opción para randomizar el orden de las preguntas y las opciones de respuesta.
- **Selección de Dificultad:** Permite seleccionar subconjuntos de preguntas según dificultad (ultrafácil, fácil, medio, difícil, ultrahardcore).
- **Navegación y Respuesta:** Navegador de preguntas, retroalimentación inmediata tras responder, y visualización de la respuesta correcta.
- **Calificación Automática:** Muestra la puntuación y el porcentaje de aciertos, indicando si el usuario ha aprobado.
- **Modo Oscuro:** Alternancia entre modo claro y oscuro para mejor experiencia visual.
- **Soporte para Exámenes Antiguos:** Carga de exámenes previos para práctica adicional.

## Requisitos Técnicos
- Frontend en HTML, CSS y JavaScript puro.
- Compatible con archivos de texto plano y Word (.docx).
- Interfaz responsiva y amigable.

## Formato de Preguntas Soportado
- Formato Aiken (pregunta, opciones A-D, línea de respuesta con "ANSWER: X").

## Objetivo del Producto
Facilitar la preparación y simulación de exámenes de opción múltiple de manera sencilla, rápida y personalizable, tanto para estudiantes como para docentes. 
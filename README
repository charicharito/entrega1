# Checkpoint 1 — Agente Gestor de Tareas del Área de Innovación

Coderhouse "AI Automation Avanzado" — Módulo 1: Fundamentos de Agentes Autónomos

## Descripción

Agente autónomo construido en n8n que recibe solicitudes de tareas por chat (lenguaje natural desestructurado),
extrae los campos obligatorios (Nombre, Responsable, Fecha límite), pregunta si falta información antes de
registrar, y crea la tarea directamente en una base de Notion. Incluye notificación automática por Gmail
como capa de observabilidad.

## Stack técnico

- **Orquestación:** n8n
- **Modelo:** OpenRouter (modelos gratuitos)
- **Herramienta:** Notion (creación de páginas en base de datos)
- **Observabilidad:** Gmail
- **Memoria:** Simple Memory (buffer window) para sostener el flujo de preguntas/respuestas

## Evidencia de funcionamiento

**Flujo completo en n8n:**
![Flujo completo en n8n](Captura de pantalla 1.png)

**Prueba en chat — pregunta por dato faltante:**
![Prueba en chat](Captura de pantalla 2.png)

**Tarea registrada en Notion:**
![Tarea registrada en Notion](Captura de pantalla 3.png)

**Notificación recibida por Gmail:**
![Notificación por Gmail](Captura de pantalla 4.png)

## Archivo del checkpoint

`checkpoint1_nombre_apellido.json` — exportación completa del flujo de n8n.

# SIMM - Sistema Inteligente de Monitoreo Médico 🏥🤖
> **Tecnología que cuida vidas.** Un ecosistema inteligente (Web y Móvil) diseñado para mejorar la adherencia terapéutica y transformar el seguimiento médico mediante Inteligencia Artificial.

---

## 📄 Descripción del Proyecto
[cite_start]En la actualidad, el cumplimiento de los tratamientos médicos es un factor crítico para la salud de las personas[cite: 367]. [cite_start]Sin embargo, un alto porcentaje de pacientes olvida, desorganiza o abandona sus indicaciones debido a la falta de un seguimiento continuo o por la complejidad de sus rutinas[cite: 368].

[cite_start]**SIMM** aborda esta problemática mediante una solución multiplataforma (Web y Mobile) adaptada a las necesidades de cada usuario, permitiendo gestionar y dar un monitoreo personalizado sobre tres pilares fundamentales[cite: 369, 370]:
1. **Medicación 💊** (Horarios, dosis y alertas de reabastecimiento).
2. **Dietas 🍏** (Regímenes alimenticios indicados por especialistas).
3. **Terapias 🧘‍♂️** (Ejercicios físicos o de rehabilitación asistida).

[cite_start]A través de la integración de **Inteligencia Artificial**, la aplicación analiza patrones de comportamiento para corregir errores que llevan al abandono del tratamiento, ofreciendo recomendaciones dinámicas y reportes predictivos para optimizar la salud del paciente[cite: 375, 376].

---

## 🎯 Objetivos de la Plataforma
* [cite_start]**Misión:** Mejorar la calidad de vida de los pacientes mediante herramientas innovadoras que fomenten el cumplimiento estricto de sus tratamientos médicos[cite: 371].
* [cite_start]**Visión:** Ser la solución líder en el monitoreo clínico digital, uniendo la medicina y la inteligencia artificial para asegurar mejores resultados clínicos y reforzar la atención en salud[cite: 372, 375].

---

## 👥 Segmentos Objetivo
[cite_start]El sistema está diseñado bajo un enfoque colaborativo enfocado en tres roles de usuario principales[cite: 211]:
* [cite_start]**Pacientes (Crónicos y Postoperatorios):** Quienes buscan automatizar la gestión de sus horarios y mejorar su proceso de recuperación de forma autónoma[cite: 188, 213].
* [cite_start]**Médicos de Cabecera / Especialistas:** Profesionales que requieren visibilidad en tiempo real del progreso, umbrales de dolor, alertas de complicaciones e historial de adherencia fuera de la consulta tradicional[cite: 162, 163, 195].
* [cite_start]**Cuidadores (Formales e Informales):** Familiares o personal de apoyo técnico que supervisan la correcta administración de pastilleros y alertas en pacientes dependientes[cite: 83, 84, 201].

---

## 📑 Especificación de Requisitos y Arquitectura Ágil
[cite_start]El desarrollo de SIMM se ha estructurado utilizando metodologías ágiles y **Lean UX**, organizando el backlog de producto en épicas funcionales enfocadas en resultados de valor inmediato[cite: 331, 353, 355]:

### [cite_start]Épicas del Sistema (Epics) [cite: 353]
* [cite_start]**EP01:** Gestión y Confirmación de Tratamientos en Tiempo Real[cite: 5].
* [cite_start]**EP02:** Gestión Clínica Avanzada para Médicos[cite: 5].
* [cite_start]**EP03:** Historial Médico, Métricas de Evolución y Reportes Dinámicos[cite: 5].
* [cite_start]**EP04:** Monitoreo Nutricional y Actividades Físicas Complementarias[cite: 5].
* [cite_start]**EP05:** Alertas Automatizadas e Inteligencia Artificial Predictiva[cite: 5].

---

## 🗓️ Plan de Trabajo (Agile Product Roadmap)
[cite_start]El ciclo de desarrollo está estimado con una velocidad de equipo de **15 Story Points por Sprint**, completando el núcleo del MVP a través de **4 Sprints de 2 semanas cada uno**[cite: 238, 239, 240]:

### [cite_start]🚀 Sprint 1: Gestión Base y Registro Core de Tratamientos 
> [cite_start]*Permitir el registro de medicamentos, modificaciones de tratamiento por el especialista clínico y activación de alarmas con evidencias fotográficas/tomas.* 
* [cite_start]**US03:** Registrar los medicamentos y dosis prescritos (1 SP)[cite: 6].
* [cite_start]**US04:** Actualizar o modificar el tratamiento prescrito (1 SP)[cite: 6].
* [cite_start]**US01:** Confirmar la toma de medicamentos en el horario indicado (1 SP)[cite: 6].
* [cite_start]**US08:** Registrar dieta y actividades físicas indicadas (1 SP)[cite: 5].

### [cite_start]📊 Sprint 2: Visualización de Progreso, Reportes y Comunicación 
> [cite_start]*Módulos de visualización para que médicos y cuidadores monitoreen múltiples pacientes en simultáneo mediante dashboards interactivos, chat síncrono y exportación de archivos PDF.* 
* [cite_start]**US06:** Visualizar la evolución/progreso del tratamiento mediante gráficos (3 SP)[cite: 6].
* [cite_start]**US07:** Monitorear varios pacientes simultáneamente mediante paneles de control (3 SP)[cite: 6].
* [cite_start]**US12:** Módulo de mensajería in-app fuera de consulta (3 SP)[cite: 6].
* [cite_start]**US15:** Generación y exportación de reportes clínicos detallados en formato PDF (3 SP).

### [cite_start]🔔 Sprint 3: Recordatorios Inteligentes e Integración con IA 
> [cite_start]*Despliegue de notificaciones push automatizadas y ejecución del motor de IA para procesar patrones de conducta y formular sugerencias de mejora adaptativa.* 
* [cite_start]**US02:** Recibir recordatorios automatizados de medicación y terapias físicas (1 SP)[cite: 6].
* [cite_start]**US05:** Consultar el historial completo de cumplimiento con filtros avanzados (3 SP)[cite: 6].
* [cite_start]**US13:** Recibir recomendaciones personalizadas generadas por el motor de IA (8 SP)[cite: 6].

### [cite_start]🚨 Sprint 4: Gestión de Alertas Críticas y Control de Calidad Clínica 
> [cite_start]*Automatización del envío de alarmas críticas en caso de omisiones o efectos adversos, además de la interfaz de validación médica para la aprobación de consejos generados por IA.* 
* [cite_start]**US09:** Notificar de forma inmediata el incumplimiento al médico/cuidador asignado (2 SP)[cite: 6].
* [cite_start]**US10:** Envío de alertas tempranas sobre complicaciones o efectos secundarios (2 SP)[cite: 6].
* [cite_start]**US11:** Coordinación y agendamiento de citas médicas y controles virtuales (5 SP)[cite: 6].
* [cite_start]**US14:** Panel médico de verificación y aprobación de sugerencias de IA (8 SP)[cite: 6].

---

## 🛠️ Tecnologías y Conceptos Clave Evaluados
* [cite_start]**Frontend & Mobile:** Prototipado UX/UI mediante Wireframes de alta fidelidad para garantizar accesibilidad en adultos mayores y pacientes con limitaciones motrices[cite: 203, 361].
* [cite_start]**Backend:** Arquitectura orientada a servicios RESTful y sincronización bidireccional en tiempo real utilizando **WebSockets** (Mensajería instantánea).
* [cite_start]**Cloud & Alertas:** Servicios de mensajería en la nube (ej. Firebase Cloud Messaging) coordinados con procesos asíncronos programados (*cron jobs*).
* [cite_start]**IA & Analítica de Datos:** Algoritmos de Machine Learning para la detección de anomalías y patrones recurrentes de incumplimiento.

---

## [cite_start]👥 Equipo de Desarrollo (UPC - Ingeniería de Requisitos) [cite: 1]
Este proyecto ha sido desarrollado colaborativamente por un equipo multidisciplinario de la **Facultad de Ingeniería de la Universidad Peruana de Ciencias Aplicadas**:

* [cite_start]**Edward Martin Gonzales Piña** (Ciencias de la Computación) - Desarrollo de algoritmos, diseño arquitectónico del backend y lógica de negocio[cite: 1, 2].
* [cite_start]**Karina Elena Che Rueda** (Ingeniería de Sistemas de la Información) - Análisis funcional, metodologías de requerimientos y planificación ágil del tiempo[cite: 1, 3].
* [cite_start]**Sebastián Brayan Sarango Cassana** (Ingeniería de Software) - Estructura de software escalable, patrones de diseño de sistemas y comunicación ágil[cite: 1, 4].
* [cite_start]**Jesús Alberto Bayona Jara** (Ingeniería de Sistemas) - Desarrollo web moderno, lógica algorítmica, análisis de seguridad y encriptación de datos sensibles[cite: 1, 5].
* [cite_start]**Joshua Emanuel Rojas Velásquez** (Ingeniería de Software) - Prototipado funcional, codificación robusta y control proactivo de entregas de software[cite: 1, 6].
* [cite_start]**Frank Rodríguez Inocente** (Ingeniería de Software) - Validación técnica, aseguramiento de criterios de aceptación y especificación del Roadmap[cite: 1, 7].

---
[cite_start]_Desarrollado como proyecto académico en el ciclo 2026-10 bajo la supervisión de la docente Mónica Rosario Priale De La Peña._ [cite: 1]

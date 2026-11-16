# 2º DAW

Repositorio índice de mi segundo curso de **Desarrollo de Aplicaciones Web** (CPIFP Los Enlaces, curso 2025-2026, ciclo finalizado). Aquí están enlazados, por asignatura, todos los ejercicios y proyectos que hice durante el curso, además del proyecto intermodular y las prácticas en empresa.

## Contenido

- [Desarrollo Web en Entorno Servidor](#desarrollo-web-en-entorno-servidor)
- [Desarrollo Web en Entorno Cliente](#desarrollo-web-en-entorno-cliente)
- [Despliegue de Aplicaciones Web](#despliegue-de-aplicaciones-web)
- [Proyecto Intermodular — Nexus](#proyecto-intermodular--nexus)
- [Prácticas en empresa — Campus Digital](#prácticas-en-empresa--campus-digital)

## Desarrollo Web en Entorno Servidor

| Repositorio | Descripción |
|---|---|
| [2daw_php](https://github.com/rsvisu/2daw_php) | Ejercicios de PHP con su teoría en Markdown y entorno Docker. Desplegados en [php2daw.page.gd](https://php2daw.page.gd/). |
| [laraideas](https://github.com/rsvisu/laraideas) | Proyecto de práctica con Laravel: gestión de ideas con autenticación, paginación, traducciones (es/en/fr), modo oscuro y confirmaciones con SweetAlert. |
| [laravue](https://github.com/rsvisu/laravue) | Proyecto de práctica integrando Vue en Laravel: login y registro en modales. |

## Desarrollo Web en Entorno Cliente

| Repositorio | Descripción |
|---|---|
| [2daw_js](https://github.com/rsvisu/2daw_js) | Ejercicios de JavaScript. Visibles en funcionamiento en [js2daw.page.gd](https://js2daw.page.gd/). |

## Despliegue de Aplicaciones Web

| Repositorio | Descripción |
|---|---|
| [2daw_php](https://github.com/rsvisu/2daw_php#github-actions) | GitHub Action que despliega automáticamente los ejercicios por FTP a InfinityFree en cada push, con su explicación paso a paso. |

## Proyecto Intermodular — Nexus

Asistente conversacional con IA para la web del CPIFP Los Enlaces. Responde a las dudas de los visitantes usando **RAG** sobre la documentación del centro (ciclos, información general…) y se gestiona desde un panel de administración.

| Repositorio | Descripción |
|---|---|
| [PI_NexusBackend](https://github.com/rsvisu/PI_NexusBackend) | API REST en Express 5 (Node 24) con LangChain + OpenAI para el RAG y Supabase como base de datos, auth y storage. Rate limiting, validación y tests. |
| [PI_NexusWidget](https://github.com/rsvisu/PI_NexusWidget) | Widget de chat en Vue 3 + Pinia que se incrusta en la web del centro con una sola etiqueta `<script>`, aislado con Shadow DOM. |
| [PI_NexusDashboard](https://github.com/rsvisu/PI_NexusDashboard) | Panel de administración en Vue 3: conversaciones, base de conocimiento del RAG, feedback de usuarios y configuración del asistente. |

## Prácticas en empresa — Campus Digital

Prácticas de marzo a junio de 2026 en el **Campus Digital** (FP Virtual de Aragón). El diario completo y el detalle de cada proyecto están en [CampusDigital](https://github.com/rsvisu/CampusDigital).

| Repositorio | Descripción |
|---|---|
| [CampusDigital](https://github.com/rsvisu/CampusDigital) | Repositorio central de las prácticas: proyectos, diario semanal y anexo de repositorios. |
| [Nueva_Documentacion](https://github.com/FPVirtual/Nueva_Documentacion) | Documentación interna con Astro + Starlight, sincronización de contenido desde otro repositorio, Docker, Nginx y auto-deploy con GitHub Actions. |
| [fp-virtual-gestion-docentes](https://github.com/FPVirtual/fp-virtual-gestion-docentes) | Aplicación Laravel + Vue para la gestión del profesorado de FP virtual, integrada con la API REST de Moodle para el alta automática de docentes. |
| [CD_AprendizajeVue](https://github.com/rsvisu/CD_AprendizajeVue) | Ejercicios del curso *Learn Vue 3 Step by Step* (Laracasts): Options API y Composition API. |
| [CD_DocumentacionPrueba](https://github.com/rsvisu/CD_DocumentacionPrueba) | Documentación de prueba hecha con Starlight. |

---
*Este repositorio actúa como índice. Haz clic en los enlaces para ver el código fuente.*

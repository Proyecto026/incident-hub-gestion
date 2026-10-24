# IT Incident Hub — Gestión del Proyecto DevOps

## Descripción

IT Incident Hub es un sistema web de gestión de incidentes tecnológicos, desarrollado como proyecto académico de Ingeniería en Sistemas.

La aplicación permite administrar incidentes mediante una arquitectura que utiliza React, Node.js, Express y PostgreSQL.

Este repositorio de GitHub se utiliza para la **planificación, seguimiento de actividades, gestión de sprints y registro de deudas técnicas**.

El código fuente y los procesos de integración continua están alojados en GitLab.

## Herramientas utilizadas

| Herramienta | Función |
|---|---|
| GitHub Issues | Gestión de actividades y deudas técnicas |
| GitHub Projects | Tablero de seguimiento |
| GitLab | Repositorio del código fuente y Merge Requests |
| GitLab CI/CD | Pruebas, compilación, auditoría y generación de artefactos |
| Docker | Ejecución de PostgreSQL y del Runner autohospedado |
| React | Interfaz web |
| Node.js y Express | Backend y API REST |
| PostgreSQL | Base de datos |

## Organización de los sprints

### Sprint 1 — Configuración inicial

- Preparación del proyecto.
- Desarrollo del backend.
- Configuración de PostgreSQL.
- Implementación inicial del frontend.
- Configuración de pruebas.

**Estado:** Completado.

### Sprint 2 — Integración continua y seguridad

- Ejecución de pruebas automatizadas.
- Validación de la compilación del frontend.
- Configuración de GitLab CI/CD.
- Auditoría de dependencias.
- Corrección de vulnerabilidades.
- Documentación de deudas técnicas.

**Estado:** Completado.

### Sprint 3 — Versionado y entrega

- Implementación de versionado semántico.
- Publicación de artefactos ZIP.
- Configuración del Runner autohospedado.
- Validaciones simuladas DEV, QA y PROD.
- Documentación de seguridad y release.

**Estado:** Completado.

## Deudas técnicas

| Deuda | Descripción | Estado |
|---|---|---|
| DT-01 | Vulnerabilidades en dependencias | Resuelta |
| DT-02 | Documentación README desactualizada | Resuelta |
| DT-03 | Mejorar cobertura de pruebas | Pendiente |
| DT-04 | Implementar despliegues reales | Pendiente |
| DT-05 | Mejorar verificación y trazabilidad de artefactos | Pendiente |

Se documentaron cinco deudas técnicas, de las cuales dos fueron resueltas.

## Resultados de integración continua

- 27 pruebas automatizadas del backend aprobadas.
- Compilación del frontend validada.
- Auditoría de dependencias incorporada al pipeline.
- Runner autohospedado configurado y validado.
- Artefacto de la versión `v1.0.0` generado.
- Pipeline con validaciones DEV, QA y PROD.

**Nota:** Las etapas DEV, QA y PROD representan validaciones y promoción simulada del artefacto, no despliegues reales en servidores independientes.

## Repositorios y evidencias

**Código fuente y CI/CD en GitLab:**

https://gitlab.com/jrodasr18/incident-hub

**Merge Requests del proyecto:**

https://gitlab.com/jrodasr18/incident-hub/-/merge_requests

**Pipelines:**

https://gitlab.com/jrodasr18/incident-hub/-/pipelines

**Documentación de evidencias:**

https://gitlab.com/jrodasr18/incident-hub/-/blob/main/docs/evidencias.md

**Documentación de lanzamiento:**

https://gitlab.com/jrodasr18/incident-hub/-/blob/main/docs/release.md

**GitHub Issues:**

https://github.com/Proyecto026/incident-hub-gestion/issues

## Alcance de la implementación

GitHub se utiliza para la gestión de tareas y la planificación. GitLab se utiliza para el repositorio principal, la revisión del código y la automatización CI/CD.

La implementación actual no incluye ejecuciones de GitHub Actions ni Azure Pipelines. Estas funcionalidades no deben considerarse realizadas únicamente por existir pipelines equivalentes en GitLab.

## Conclusión

IT Incident Hub integra prácticas de desarrollo de software, control de versiones, pruebas automatizadas, seguridad, documentación, gestión de actividades e integración continua.

El proyecto presenta una implementación funcional y documentada, junto con un registro de mejoras técnicas pendientes.

# Productividad App

Aplicación web para organizar proyectos, tareas y procesos repetibles mediante plantillas.

## Funcionalidades (MVP)

- Registro e inicio de sesión de usuarios
- Proyectos para agrupar tareas
- Tareas con prioridad, fecha límite y estado
- Tablero Kanban (Pendiente → En progreso → Completada)
- Checklist de pasos dentro de cada tarea
- Plantillas de procesos reutilizables
- Dashboard con tareas vencidas, del día y avance por proyecto

## Stack tecnológico

- **Frontend:** React + TypeScript (Vite)
- **Backend:** Node.js + Express + TypeScript
- **Base de datos:** PostgreSQL + Prisma
- **Pruebas:** Vitest, Supertest, Playwright
- **DevOps:** Docker, GitHub Actions

## Arquitectura

- Cliente-servidor con API REST
- Backend en capas (routes → controllers → services → repositories) organizado por módulos
- Frontend organizado por funcionalidades

## Convenciones

- Ramas: `main` (producción), `develop` (integración), `feature/*` (funcionalidades)
- Commits: [Conventional Commits](https://www.conventionalcommits.org/es/)
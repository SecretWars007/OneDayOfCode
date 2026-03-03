# OneDayOfCode
Repositorio para cumplir el primer día del desafió GIT - GITHUB de ALURA LATAM
# QAMS – Quality Assurance Management System

QAMS (Quality Assurance Management System) es un sistema de **gestión de la calidad** desarrollado en .NET, orientado al seguimiento de procesos, no conformidades, acciones correctivas y documentación asociada a un sistema de gestión (por ejemplo, basado en normas ISO).

Este proyecto forma parte de mi ruta de aprendizaje como desarrollador full‑stack, con énfasis en backend .NET, buenas prácticas de arquitectura, pruebas y automatización.

## Características principales

- Registro y seguimiento de no conformidades e incidencias.
- Gestión de acciones correctivas y preventivas.
- Administración de documentos y evidencias de calidad.
- Gestión de usuarios y roles (administrador, auditor, responsable de proceso, etc.).
- API lista para integrarse con otros sistemas o frontends (web/móvil).

## Tecnologías utilizadas

- Plataforma: `.NET` (por ejemplo .NET 6/7/8).
- Lenguaje: `C#`.
- Framework web: `ASP.NET Core` (Web API / MVC).
- Base de datos: (por ejemplo) `SQL Server` / `PostgreSQL` usando `Entity Framework Core`.
- Autenticación/autorización: JWT / Identity (si aplica).
- Pruebas: xUnit / NUnit / MSTest (si aplica).
- Contenedores: Docker (opcional, si se incluye configuración).

> Ajusta esta lista según la configuración real de tu proyecto.

## Arquitectura

El sistema sigue una arquitectura por capas/módulos, separando responsabilidades por dominio:

- `Domain` – Entidades, interfaces y lógica de negocio principal.
- `Application` – Casos de uso, DTOs, servicios de aplicación.
- `Infrastructure` – Persistencia, configuración de base de datos, servicios externos.
- `API` / `Web` – Endpoints HTTP, controladores, manejo de requests/responses.

En el dominio de calidad se contemplan módulos como:

- `Users` – Gestión de usuarios, roles y autenticación.
- `NonConformities` – Registro y seguimiento de no conformidades.
- `Actions` – Acciones correctivas y preventivas.
- `Documents` – Gestión de documentos y evidencias.
- `Audits` – Planificación y registro de auditorías (si aplica).

## Requisitos previos

- SDK de .NET instalado (por ejemplo .NET 6, 7 u 8).
- Motor de base de datos (SQL Server, PostgreSQL, etc.).
- Git (para clonar el repositorio).
- Docker (opcional, si usas contenedores).

## Instalación

```bash
# Clonar el repositorio
git clone https://github.com/SecretWars007/QAMS.git
cd QAMS


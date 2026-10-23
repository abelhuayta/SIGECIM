# SIGECIM - Clínica Privada «Salud Integral» 🏥

**SIGECIM** es una plataforma centralizada de gestión ambulatoria diseñada para automatizar el registro de pacientes, la programación de agendas médicas y la reserva o cancelación de citas en tiempo real. 

A diferencia del flujo manual fragmentado, este producto garantiza integridad transaccional, trazabilidad clínica y disponibilidad continua para maximizar el valor operativo desde el primer Sprint.

## 🎯 Alcance del Sprint 1 (MVP)
Este repositorio contiene el incremento funcional del núcleo transaccional de SIGECIM, incluyendo:
- Autenticación segura de usuarios (JWT y encriptación bcrypt).
- Control de acceso basado en roles (Middleware RBAC para Admin, Médico y Paciente).
- Catálogo clínico: Configuración de oferta de especialidades y alta de médicos.
- Motor de búsqueda dinámica de disponibilidad horaria.
- Transacción ACID para reserva de citas médicas con bloqueo de concurrencia.

## 🛠 Arquitectura y Tecnologías
- **Base de Datos:** Motor SQL (Modelo relacional de pacientes, médicos y citas).
- **Backend:** API REST (Rutas seguras e integraciones CRUD).
- **Frontend / UI:** Formularios reactivos e interfaces validadas.
- **Control de Versiones:** GitHub (Flujo basado en Pull Requests y ramas de features).

## 👥 Equipo Scrum
- **Abel Alexander Huayta Choquepata** - Product Owner / Developer
- **Fernando Jonathan Barra Quispe** - Scrum Master / Developer
- **Jesús Francisco Silva Pino** - Developer (Arquitectura / BD)
- **Rodrigo Anderson Gutiérrez Anco** - Developer (Backend / API)

## 📌 Ramas de Desarrollo Activas (WIP)
- `main`: Código estable y validado (DoD al 100%).
- `feature/hu01-registro-pacientes`: Desarrollo de API REST /api/pacientes.
- `feature/hu02-login-jwt`: Implementación de seguridad y sesiones.
- `feature/hu03-medicos`: Módulo de vinculación CMP y especialidades.
- `feature/hu10-rbac`: Guardias de rutas y validación de menús.

> **Nota Académica:** Proyecto desarrollado para la asignatura de Organización y Métodos / Procesos de Software (UNSA - 2026).

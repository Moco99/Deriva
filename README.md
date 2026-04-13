# 🦈 DERIVA

> **El océano de conocimiento para la manada del ITVer.**
> Una plataforma colaborativa diseñada para conectar estudiantes, facilitar asesorías académicas y fomentar el apoyo mutuo mediante un sistema de gamificación.

[![Deploy en Vercel](https://img.shields.io/badge/Deploy-Vercel-black?logo=vercel)](#)
[![Backend en Railway](https://img.shields.io/badge/Backend-Railway-purple?logo=railway)](#)
[![Base de Datos](https://img.shields.io/badge/Database-Supabase-green?logo=supabase)](#)
[![Frontend en React](https://img.shields.io/badge/Frontend-React-20232A?logo=react&logoColor=61DAFB)](#)
[![Backend en NestJS](https://img.shields.io/badge/Backend-NestJS-E0234E?logo=nestjs&logoColor=white)](#)
[![ORM con Prisma](https://img.shields.io/badge/ORM-Prisma-2D3748?logo=prisma&logoColor=white)](#)

---

## 📸 Vistazo a la Plataforma

| Login Institucional | Tablero de Solicitudes (Feed) |
| :---: | :---: |
| ![Login](./assets/deriva_login.png)` <br>  | ![Feed](./assets/deriva_feed.png)` <br> |

| Chat en Tiempo Real | Perfil y Reputación |
| :---: | :---: |
| ![Chat](./assets/deriva_chat.png)` <br>  | ![Perfil](./assets/deriva_profile.png)` <br>  |

---

## 🌊 ¿Qué es Deriva?

[cite_start]Deriva nace de la necesidad de centralizar el apoyo académico dentro del Instituto Tecnológico de Veracruz. [cite_start]Permite a los estudiantes publicar dudas específicas de sus materias [cite: 40, 42] [cite_start]y conectar con compañeros que tienen el conocimiento para ayudarlos[cite: 53], todo bajo un ecosistema seguro y exclusivo para la institución.

### ✨ Características Principales

* [cite_start]**🔒 Acceso Exclusivo:** Validación de identidad mediante correo con dominio institucional para garantizar la seguridad de la comunidad[cite: 109, 112].
* [cite_start]**🤝 Match Académico:** Sistema de publicación de solicitudes de ayuda y ofertas de tutoría, con filtros por materia y semestre[cite: 40, 48].
* [cite_start]**💬 Comunicación Inmediata:** Chat integrado en tiempo real mediante WebSockets para coordinar las asesorías de forma privada[cite: 59, 61].
* [cite_start]**🏆 Sistema de Reputación:** Los usuarios ganan **Créditos Tiburón** al completar tutorías exitosamente [cite: 72][cite_start], promoviendo la participación activa[cite: 68].
* [cite_start]**🧠 Asistencia con Inteligencia Artificial:** Recomendación automática de tutores basada en el contenido de las solicitudes [cite: 80, 86] [cite_start]y clasificación inteligente de publicaciones[cite: 87, 93].

---

## 🛠️ Stack Tecnológico

El proyecto está construido bajo una arquitectura cliente-servidor escalable:

**Frontend (Web)**
* **Framework:** Next.js (App Router) / React
* **Estilos:** Tailwind CSS (Diseño oscuro, *Glassmorphism*)
* **Hosting:** Vercel

**Backend & API**
* **Entorno:** Node.js
* **Tiempo Real:** Socket.io (WebSockets)
* **Hosting:** Railway

**Base de Datos & Almacenamiento**
* **Proveedor:** Supabase (PostgreSQL)

---

## 👥 El Equipo (Scrum)

[cite_start]Este proyecto fue desarrollado para la asignatura de Ingeniería de Software [cite: 11] [cite_start]aplicando la metodología ágil Scrum[cite: 122]:

* [cite_start]**Arturo Báez:** Product Owner / Lead Backend Developer, Lead Frontend Developer, Backend Developer [cite: 124, 130]
* [cite_start]**Uriel Flores:** Scrum Master / Database Administrator [cite: 126, 132]
* [cite_start]**Leonardo Ortiz:** Frontend Developer [cite: 131, 128]

---

## 🚀 Instalación Local

Si deseas correr este proyecto en tu entorno local:

1. Clona el repositorio:
   ```bash
   git clone [https://github.com/tu-usuario/deriva.git](https://github.com/tu-usuario/deriva.git)
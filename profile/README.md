# Nostos

**Nostos** es una aplicación que permite a los usuarios crear álbumes de viaje en forma de globos 3D, almacenando fotos y videos de sus experiencias. Los álbumes pueden ser personales, compartidos o públicos, y cuentan con funcionalidades sociales como likes, seguidores y notificaciones en tiempo real. La aplicación está diseñada para ser usada principalmente en dispositivos móviles, pero también contará con una versión web.

---

## 🎯 Nuestros Objetivos

- **Experiencia inmersiva:** Crear una interfaz visual innovadora con globos 3D.
- **Optimización y escalabilidad:** Arquitectura basada en microservicios.
- **Seguridad avanzada:** Autenticación JWT y control de permisos.
- **Interacción social:** Likes, seguidores y notificaciones en tiempo real.
- **Automatización del despliegue:** CI/CD con GitHub Actions y Docker.

---

## 🌐 Tecnologías Usadas

### Backend y Microservicios
- Lenguajes: Go, Node.js
- Contenedores: Docker + Docker Compose.
- API Gateway: Traefik.
- Seguridad: Vault (HashiCorp), JWT.
- Base de Datos: PostgreSQL.
- Cache: Redis.
- Almacenamiento de Medios: MinIO (compatible con S3).
- Notificaciones: NATS / MQTT (Mosquitto) "Pendiente de decidir".
- CI/CD: GitHub Actions.
- Infraestructura: Raspberry Pi 5 con Cloudflare Tunnel.
- Monitoreo: Prometheus, Grafana, Loki.

### App
- Lenguajes: React Native
- Monitoreo: Prometheus, Grafana, Loki.

### Landing Page
- Lenguajes: Astro
- Contenedores: Docker + Docker Compose.
- API Gateway: Traefik.
- Almacenamiento de Medios: MinIO (compatible con S3).
- CI/CD: GitHub Actions.
- Infraestructura: Raspberry Pi 5 con Cloudflare Tunnel.
- Monitoreo: Prometheus, Grafana, Loki.

---

## 📈 Diagramas

- **Arquitectura General:** Diagrama de la infraestructura del sistema.
![Sin titulo-2025-05-07-2301(1)](https://github.com/user-attachments/assets/82a88b9d-6668-4a50-bd3a-5a5d1d4a1d9a)


- **Casos de Uso:** Interacciones principales de los usuarios con la aplicación.
![image](https://github.com/user-attachments/assets/d0dd7e47-ef97-4290-9bca-daca02a25a64)

- **Base de Datos:** Esquema de PostgreSQL con relaciones entre entidades.

![image](https://github.com/user-attachments/assets/7118e3a3-01ef-40c6-b4dc-d55d867a92cd)

---
Aquí tienes un ejemplo de cómo podrías incluir esta información en un archivo README en español:

---

## 🌐 URLs de los Servicios de la Aplicación

La aplicación está compuesta por varios servicios, cada uno accesible a través de las siguientes URLs:

* **Servicio de Autenticación**
  `auth.nostos-globe.me`

* **Servicio de Perfil de Usuario**
  `profile.nostos-globe.me`

* **Servicio de Gestión de Viajes**
  `trips.nostos-globe.me`

* **Servicio de Álbumes de Fotos**
  `albums.nostos-globe.me`

* **Servicio de Acciones del Usuario**
  `actions.nostos-globe.me`

---

## 🖥️ Página Web y Landing Page

La versión web de **Nostos** complementa la aplicación móvil permitiendo la gestión de álbumes y la exploración de contenido. Además, la landing page proporciona información sobre la aplicación, descargas y comunidad.

- **Web App:** [https://app.nostos-globe.me](https://app.nostos-globe.me) *No disponible
- **Landing Page:** [https://nostos-globe.me](https://nostos-globe.me)

---

## 💭 Mockup y Diseño

Los mockups y diseños UX/UI pueden consultarse en:
[Figma](https://www.figma.com/design/dQzP9PxhQrfF7ZerZCRAfM/Nostos?node-id=0-1&t=iKaFaeeLMzz7InOQ-1)


![Mockup](https://github.com/user-attachments/assets/a2c627b4-371c-4e7d-8cee-864645080190)

---

## 🎨 Paleta de Colores

- **Azul Profundo:** `#a7c7e7`
- **Cian Vibrante:** `#b3d9d9`
- **Verde Acuático:** `#b8e0b1`
- **Naranja Suave:** `#f7e1a5`
- **Gris Claro:** `#f6f6f4`

---

## 👀 Logo

![Logo de Nostos](./assets/logo.png)

---

## 🔗 Funcionalidades Web y Móvil

- **Autenticación Segura:** Registro, login y gestión de sesiones.
- **Exploración de Contenido:** Navegación por álbumes públicos y recomendados.
- **Creación de Álbumes:** Agregar fotos, videos y gestionar configuraciones.
- **Interacción Social:** Likes, seguidores y comentarios.
- **Notificaciones en Tiempo Real:** Seguimiento de actividad relevante.
- **Dashboard Personal:** Administración de perfil y preferencias.

---

## 📂 Repositorios

La organización Nostos cuenta con los siguientes repositorios:

App: Código fuente de la aplicación en React Native (móvil y web en un solo repositorio).

Config: Archivos de configuración necesarios para Docker Compose y la infraestructura de los contenedores.

Landing Page: Código de la Landing Page y promoción de la aplicación.

Auth Service: Gestión de autenticación, JWT y seguridad.

Profile Service: Manejo de perfiles, seguidores y datos de usuario.

Album Service: Creación y administración de álbumes de viaje.

Action Service: Registro y optimización de likes y favoritos.

Email Service: Envio de emails.

---
## 📌 Project Roadmap

Este es el roadmap actual basado en los issues de Linear.

| Issue ID | Title | Description | Status | Priority | Phase | Due Date |
|----------|------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------|----------|---------------------------------|---------|
| PRO-1 | Choose technologies | _Sin descripción_ | Backlog | No priority | N/A | N/A |
| PRO-2 | Branding | _Sin descripción_ | Backlog | No priority | N/A | N/A |
| PRO-3 | Think functionalities | _Sin descripción_ | Backlog | No priority | N/A | N/A |
| PRO-4 | Define Pages | Cuando este issue esté completo, se crearán issues individuales para cada página definida, detallando su contenido. | Backlog | No priority | N/A | N/A |
| PRO-8 | Conduct Market Research on Existing Apps | Investigación y análisis de aplicaciones de diarios de viaje existentes para identificar características, fortalezas, debilidades y puntos problemáticos de los usuarios. | Done | High | Phase 1: Planning and Requirements Analysis | N/A |
| PRO-10 | List common features and unique offerings in competitor apps. | _Sin descripción_ | Done | Low | Phase 1: Planning and Requirements Analysis | N/A |
| PRO-11 | Define Functional and Non-Functional Requirements | Recopilar requisitos detallados para la aplicación, cubriendo aspectos funcionales y no funcionales como rendimiento, seguridad y escalabilidad. | Done | Medium | Phase 1: Planning and Requirements Analysis | N/A |
| PRO-12 | Define Extra Key Features | _Sin descripción_ | Done | Medium | Phase 1: Planning and Requirements Analysis | N/A |
| PRO-14 | Select Technology Stack | Investigación y selección del mejor stack tecnológico para frontend, backend y bases de datos. | Done | Urgent | Phase 1: Planning and Requirements Analysis | N/A |
| PRO-15 | Branding of the App | _Sin descripción_ | Done | Medium | Phase 1: Planning and Requirements Analysis | N/A |
| PRO-16 | Choose a name for the app | Selección de un nombre para la aplicación que refleje su propósito, funcionalidad y audiencia objetivo. | Done | Low | Phase 1: Planning and Requirements Analysis | N/A |
| PRO-17 | Create an image of the idea | Crear una imagen o animación breve de cada idea previamente descrita, mostrando la apariencia de la aplicación y su relación con el usuario. | Done | Medium | Phase 1: Planning and Requirements Analysis | N/A |
| PRO-18 | Class Diagram | Creación del diagrama de clases para definir las entidades, sus atributos y métodos, asegurando una estructura clara del sistema. | Done | No priority | Phase 2: Design and Architecture | N/A |
| PRO-19 | Resumed Abstraction of the idea | Resumir y definir los términos clave que explican el propósito del proyecto. | Done | No priority | Phase 2: Design and Architecture | N/A |
| PRO-20 | Sequence Diagram | Creación del diagrama de secuencia para visualizar interacciones entre objetos y eventos en el sistema. | Done | No priority | Phase 2: Design and Architecture | N/A |
| PRO-21 | Case Diagrams | Creación de diagramas de casos de uso para ilustrar la interacción del usuario con el sistema. | Done | No priority | Phase 2: Design and Architecture | N/A |
| PRO-22 | PMBOK | Aplicación y revisión de PMBOK en la documentación del proyecto. | Done | No priority | Phase 2: Design and Architecture | N/A |
| PRO-23 | Mockup - Screens | Diseño visual de la interfaz de usuario en forma de mockups. | In Progress | No priority | Phase 2: Design and Architecture | N/A |
| PRO-24 | Screen - Get Started | _Sin descripción_ | Done | No priority | Phase 2: Design and Architecture | N/A |
| PRO-25 | Screen - Sign Up | _Sin descripción_ | Done | No priority | Phase 2: Design and Architecture | N/A |
| PRO-26 | Screen - Log In | _Sin descripción_ | Done | No priority | Phase 2: Design and Architecture | N/A |
| PRO-27 | Screen - Home/Notifications | _Sin descripción_ | Done | No priority | Phase 2: Design and Architecture | N/A |
| PRO-28 | Screen - Explore/Photo View | _Sin descripción_ | In Progress | No priority | Phase 2: Design and Architecture | N/A |
| PRO-29 | Screen - Add | _Sin descripción_ | In Progress | No priority | Phase 2: Design and Architecture | N/A |
| PRO-30 | Screen - Globe View/Card View/Photo View | _Sin descripción_ | In Progress | No priority | Phase 2: Design and Architecture | N/A |

---

🔹 **Estado de las tareas**:
- ✅ **Done**: Completado
- 🚧 **In Progress**: En desarrollo
- ⏳ **Backlog**: Pendiente
- ❌ **Canceled**: Cancelado

📅 **Última actualización**: 2025-02-21

---

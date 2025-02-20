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
- Mensajería: NATS / MQTT (Mosquitto).
- CI/CD: GitHub Actions, Watchtower.
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
- CI/CD: GitHub Actions, Watchtower.
- Infraestructura: Raspberry Pi 5 con Cloudflare Tunnel.
- Monitoreo: Prometheus, Grafana, Loki.

---

## 📈 Diagramas

- **Arquitectura General:** Diagrama de la infraestructura del sistema.
- **Casos de Uso:** Interacciones principales de los usuarios con la aplicación.
- **Base de Datos:** Esquema de PostgreSQL con relaciones entre entidades.

_Se pueden consultar en la carpeta `docs/diagrams`._

---

## 🖥️ Página Web y Landing Page

La versión web de **Nostos** complementa la aplicación móvil permitiendo la gestión de álbumes y la exploración de contenido. Además, la landing page proporciona información sobre la aplicación, descargas y comunidad.

- **Web App:** [https://app.nostos-globe.me](https://app.nostos-globe.me)
- **Landing Page:** [https://nostos-globe.me](https://nostos-globe.me)

---

## 💭 Mockup y Diseño

Los mockups y diseños UX/UI pueden consultarse en:
[Figma](https://www.figma.com/design/dQzP9PxhQrfF7ZerZCRAfM/Nostos?node-id=0-1&t=iKaFaeeLMzz7InOQ-1)


![Mockup](https://github.com/user-attachments/assets/a2c627b4-371c-4e7d-8cee-864645080190)

---

## 🎨 Paleta de Colores

- **Azul Profundo:** `#003f5c`
- **Cian Vibrante:** `#2f4b7c`
- **Verde Acuático:** `#a05195`
- **Naranja Suave:** `#d45087`
- **Gris Claro:** `#f95d6a`

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

User Service: Manejo de perfiles, seguidores y datos de usuario.

Album Service: Creación y administración de álbumes de viaje.

Likes Service: Registro y optimización de likes.

Notification Service: Envío de notificaciones en tiempo real.

---
## 📍 Roadmap / Trello / Gantt

Para seguimiento del desarrollo:

- **Roadmap del Proyecto:** [Trello](https://trello.com/b/NostosRoadmap)
- **Diagrama de Gantt:** En la carpeta `docs/roadmap`.

---


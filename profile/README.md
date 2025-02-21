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
![image](https://github.com/user-attachments/assets/34d2ad62-3a41-412d-92af-74b5d7f3e4ef)

- **Casos de Uso:** Interacciones principales de los usuarios con la aplicación.
![image](https://github.com/user-attachments/assets/d0dd7e47-ef97-4290-9bca-daca02a25a64)

- **Base de Datos:** Esquema de PostgreSQL con relaciones entre entidades.

![image](https://github.com/user-attachments/assets/7118e3a3-01ef-40c6-b4dc-d55d867a92cd)

---

## 🖥️ Página Web y Landing Page

La versión web de **Nostos** complementa la aplicación móvil permitiendo la gestión de álbumes y la exploración de contenido. Además, la landing page proporciona información sobre la aplicación, descargas y comunidad.

- **Web App:** [https://app.nostos-globe.me](https://app.nostos-globe.me)
- **Landing Page:** [https://nostos-globe.me](https://nostos-globe.me)

Ninguna esta disponible actualmente

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

User Service: Manejo de perfiles, seguidores y datos de usuario.

Album Service: Creación y administración de álbumes de viaje.

Likes Service: Registro y optimización de likes.

Notification Service: Envío de notificaciones en tiempo real.

---
## 📍 Roadmap / Trello / Gantt

Para seguimiento del desarrollo:

- **Roadmap del Proyecto:** [Roadmap_de_Issues__Filtrados_.csv](https://github.com/user-attachments/files/18912806/Roadmap_de_Issues__Filtrados_.csv)
- **Diagrama de Gantt:** En la carpeta `docs/roadmap`.
# 📌 Project Roadmap

Este es el roadmap actual basado en los issues de Linear.

| Issue ID | Title | Status  | Priority | Phase |
|----------|-------------------------------|---------|----------|----------------------|
{% for index, row in roadmap_filtered_df.iterrows() %}
| {{ row["Issue ID"] }} | {{ row["Title"] }} | {{ row["Status"] }} | {{ row["Priority"] }} | {{ row["Phase"] or 'N/A' }} |
{% endfor %}

---

🔹 **Estado de las tareas**:
- ✅ **Done**: Completado
- 🚧 **In Progress**: En desarrollo
- ⏳ **Backlog**: Pendiente
- ❌ **Canceled**: Cancelado

📅 **Última actualización**: {{ fecha_actual }}

---

_Si quieres contribuir o sugerir cambios, revisa los issues abiertos en nuestro [repositorio](https://github.com/tu-organizacion/tu-repo/issues)._

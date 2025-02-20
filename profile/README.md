# Nostos - Aplicación de Álbumes de Viaje 3D

Bienvenido al repositorio central de la organización **Nostos**, donde se gestionan todos los repositorios del proyecto, incluyendo la aplicación móvil, la versión web, los microservicios backend, la configuración de contenedores y la landing page.

---

## 📚 Explicación de la Idea del Proyecto

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
- Lenguajes: Go, Node.js (según el servicio).
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
[Figma](https://www.figma.com/file/NostosMockup) _(Ejemplo, actualizar según corresponda)._

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

## 📍 Roadmap / Trello / Gantt

Para seguimiento del desarrollo:

- **Roadmap del Proyecto:** [Trello](https://trello.com/b/NostosRoadmap)
- **Diagrama de Gantt:** En la carpeta `docs/roadmap`.

---

Este README centraliza toda la información clave de **Nostos**, sirviendo como referencia para desarrolladores y colaboradores del proyecto.


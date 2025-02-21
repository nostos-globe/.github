[Roadmap_de_Issues__Filtrados_.csv](https://github.com/user-attachments/files/18912806/Roadmap_de_Issues__Filtrados_.csv)# Nostos

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

- **Roadmap del Proyecto:** [Trello](https://trello.com/b/NostosRoadmap)
- **Diagrama de Gantt:** En la carpeta `docs/roadmap`.
[Uploading Roadmap_de_Issues__Fi,Issue ID,Title,Description,Status,Priority,Phase,Due Date
0,PRO-1,Choose technologies,"## **Tecnologías sugeridas:**

1. **Aplicación :**
2. **Backend y almacenamiento :**
3. **Visualización de datos :**
4. **Seguridad :**",Backlog,No priority,,
1,PRO-2,Branding,,Backlog,No priority,,
2,PRO-3,Think funcionalities,,Backlog,No priority,,
3,PRO-4,Define Pages,"When this issue is completed, an issue will be created for each page defined, where the content of each page will be outlined.",Backlog,No priority,,
4,PRO-8,Conduct Market Research on Existing Apps,"Research and analyze existing travel diary apps in the market to identify features, strengths, weaknesses, and user pain points. ",Done,High,Phase 1: Planning and Requirements Analysis,
5,PRO-10,List common features and unique offerings in competitor apps.,,Done,Low,Phase 1: Planning and Requirements Analysis,
6,PRO-11,Define Functional and Non-Functional Requirements,"Gather detailed requirements for the app, covering both functional (what the app does) and non-functional (performance, security, scalability) aspects",Done,Medium,Phase 1: Planning and Requirements Analysis,
7,PRO-12,Define Extra Key Features,"List and define the key features to be implemented in the  app based on research and stakeholder input.

Features Categories:

* Essential/Personal/Coop features:
  * Saving and organizing multimedia content by date/location/people.
  * Multimedia content according to location and its representation on the globe.
  * View the memories in the globe with an filter option, by date, season, localization, friends, personalized category.
  * Capacity to create different ""profiles of globes"" with different filters applicated, for load only the wanted content.
  * Representation of those contents on a globe view, personals or shared with people.
  * Friends ""Feed"" for sharing memories betwen your close circle.
* Social Features:
  * Exploring page, exploring globes or memories from other people  (random or popular).
  * Liking, commenting, sharing posts.

* Extra:
  * Downloading the content.",Done,Medium,Phase 1: Planning and Requirements Analysis,
8,PRO-14,Select Technology Stack,"Research and select the best technology stack (frontend, backend, databases, mobile platforms) for building the financial app.",Done,Urgent,Phase 1: Planning and Requirements Analysis,
9,PRO-15,Branding of the App,"### 1\. **Define the Company Name:**

The company name should be concise, memorable, and reflect the values or services that the brand provides. It should resonate with your target audience and be easy to pronounce and spell. For example, **EcoVibe Solutions** communicates a modern, eco-friendly approach to problem-solving, combining innovation with sustainability.

### 2\. **Define the Domain and Website Name:**

The domain and website name should be a direct representation of your company name or brand. It must be simple, easy to remember, and should ideally match the company name to avoid confusion. Additionally, check that the domain is available and not already in use. For instance, **www.ecovibesolutions.com** aligns perfectly with the brand name and ensures consistency online.

### 3\. **Define the Slogan:**

The slogan should be a short, catchy phrase that encapsulates your company’s mission and vision. It needs to convey your unique value proposition in an engaging way and leave a lasting impression. For example, **“Innovating for a greener future”** highlights the company’s commitment to sustainable innovation while being concise and memorable.

### 4\. **Define the Logo or Logos:**

The logo should be simple, versatile, and easily recognizable. It should visually represent the core values of your company and be scalable for different mediums, whether online or in print. For instance, **EcoVibe Solutions** might use a logo that combines nature-inspired elements (like leaves) with modern, clean lines to represent both sustainability and innovation.

### 5\. **Define the Colors for Your Brand Palette:**

The color palette should reflect the personality and values of your brand. Choose colors that complement each other and are consistent across all marketing materials. For example, a palette could include **green** for sustainability, **blue** for trust and calm, **gray** for professionalism, and **yellow** for energy and positivity, creating a balanced and cohesive visual identity.

### 6\. **Define the Fonts for Your Brand:**

The fonts should be chosen to ensure readability, and each font should serve a specific purpose. Select a bold font for the company name, an elegant one for the slogan, and a simple one for body text. For example, **Montserrat Bold** could be used for the company name, **Lora Italic** for the slogan, and **Roboto Regular** for body text, maintaining consistency and professionalism throughout.

### 7\. **Define the Style Guide Rules:**

The style guide rules provide consistency in the use of visual and written elements across all platforms and materials. Rules should cover logo usage, color guidelines, typography, image styles, and tone of voice. For example, **always use the logo in its original form, maintain a clear space around it, and adhere to the brand’s color palette** to ensure that the brand is represented consistently and professionally across all touchpoints.",Done,Medium,Phase 1: Planning and Requirements Analysis,
10,PRO-16,Choose a name for the app,"Select a name for the app that reflects its purpose, functionality, and target audience. This process involves brainstorming, considering branding, and ensuring the name is memorable.",Done,Low,Phase 1: Planning and Requirements Analysis,
11,PRO-17,Create an image of the idea,Create an image or a small animation of each idea previously outlined that clearly shows what the appearance of your application will be and its relationship with the user and their environment,Done,Medium,Phase 1: Planning and Requirements Analysis,
43,PRO-18,Class Diagram,"Creation of the class diagram, which involves defining and visualizing the system's classes, their attributes, methods, and relationships. This diagram will serve as a foundational design tool for the development process, ensuring a clear structure and understanding of how the components interact within the system.",Done,No priority,Phase 2: Design and Architecture,
44,PRO-19,Resumed Abstraction of the idea,"In the document, briefly summarize and use key terms to define the project's purpose.",Done,No priority,Phase 2: Design and Architecture,
45,PRO-20,Sequence Diagram,"Creation of the sequence diagram, which involves visualizing the interactions between objects or components in the system over time. This diagram will highlight the order of messages or events exchanged, helping to clarify the flow of processes and ensuring a better understanding of how different parts of the system communicate during specific scenarios.",Done,No priority,Phase 2: Design and Architecture,
46,PRO-21,Case Diagrams,"Creation of use case diagrams, which involves identifying and illustrating the system’s key interactions with users or other systems. This diagram will depict the various use cases, actors, and their relationships, providing a clear representation of functional requirements and helping to define the system’s behavior from the user's perspective.",Done,No priority,Phase 2: Design and Architecture,
47,PRO-22,PMBOK,Review and apply PMBOK (Project Management Body of Knowledge) in the document.,Done,No priority,Phase 2: Design and Architecture,
48,PRO-23,Mockup - Screens,"Design the screen view of the mockup, creating a visual representation of the user interface for a specific view or page",In Progress,No priority,Phase 2: Design and Architecture,
49,PRO-24,Screen - Get Started,"Design the screen view of the mockup:

* Get Started",Done,No priority,Phase 2: Design and Architecture,
50,PRO-25,Screen - Sign Up,"Design the screen view of the mockup:

* Sign up",Done,No priority,Phase 2: Design and Architecture,
51,PRO-26,Screen - Log In,"Design the screen view of the mockup:

* Log in",Done,No priority,Phase 2: Design and Architecture,
52,PRO-27,Screen - Home/Notifications,"Design the screen view of the mockup:

* User's home
* Notifications",Done,No priority,Phase 2: Design and Architecture,
53,PRO-28,Screen - Explore/Photo View,"Design the screen view of the mockup:

* Exploring Page
* Pics viewer",In Progress,No priority,Phase 2: Design and Architecture,
54,PRO-29,Screen - Add,"Design the screen view of the mockup:

* Adding Post ",In Progress,No priority,Phase 2: Design and Architecture,
55,PRO-30,Screen - Globe View/Card View/ Photo View,"Design the screen view of the mockup:

* Globe View
* Card View
* Photo view",In Progress,No priority,Phase 2: Design and Architecture,
56,PRO-31,Screen - Profile/Profile Liked/ Profile Tiktok/ Settings,"Diseño de las Screens de:

* Perfil
* Perfiles Gustados
* Ajustes de Aplicación",In Progress,No priority,Phase 2: Design and Architecture,
57,PRO-32,BDD - Diagrama relación - entidad,"Create the entity-relationship diagram (ERD) for the database, which involves defining the entities, their attributes, and the relationships between them.",Done,No priority,Phase 2: Design and Architecture,
58,PRO-33,UI Design and Layout Creation,"Following the mockup design and create the layout for the frontend interface, ensuring a user-friendly experience with clear navigation and visual consistency. This includes selecting colors, fonts, and overall design elements",Backlog,No priority,Phase 3: Frontend Development,
59,PRO-34,Responsive Design Implementation,"Implement responsive design techniques to ensure the frontend adapts seamlessly to different screen sizes, devices, and orientations, providing a consistent user experience across platforms.",Backlog,No priority,Phase 3: Frontend Development,
60,PRO-35,Integration of Frontend with Backend,"Integrate the frontend with backend APIs and services, ensuring smooth data flow and proper display of information. This includes implementing dynamic elements and ensuring real-time updates when necessary.",Backlog,No priority,Phase 3: Frontend Development,
61,PRO-36,Frontend Performance Optimization,"Optimize the frontend code for performance, including reducing page load times, optimizing assets (images, scripts), and improving overall responsiveness of the interface.",Backlog,No priority,Phase 3: Frontend Development,
62,PRO-37,User Interface Testing and Debugging,"Test the user interface for usability, responsiveness, and cross-browser compatibility. Identify and fix any issues or bugs in the frontend to ensure a seamless user experience.",Backlog,No priority,Phase 3: Frontend Development,
63,PRO-38,UI/UX Review and Iteration,Conduct UI/UX reviews based on feedback and make necessary iterations to improve the user experience. Focus on enhancing visual appeal and optimizing ease of use.,Backlog,No priority,Phase 3: Frontend Development,
ltrados_.csv…]()

---


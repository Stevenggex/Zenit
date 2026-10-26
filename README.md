# 🛡️ Zenit — Sistema de Gestión de Activos de Información y Evaluación de Riesgos de Ciberseguridad

> **Asignatura:** Diseño de Interfaces  
> **Institución:** Escuela Politécnica Nacional (EPN) — Escuela de Formación de Tecnólogos (ESFOT)  
> **Carrera:** Tecnología en Desarrollo de Software  
> **Docente:** Ing. Byron Loarte  
> **Período:** 2026-A  

---

## 📌 Visión General del Proyecto

**AssetShield** es una plataforma web enterprise orientada a medianas y grandes empresas que buscan centralizar, controlar y auditar la seguridad de su infraestructura tecnológica. 

El sistema resuelve tres grandes problemáticas de las organizaciones:
1. **Falta de visibilidad y centralización:** Inventario disperso e informal de equipos y servicios.
2. **Evaluación de riesgos empírica:** Ausencia de un estándar claro para priorizar qué fallas corregir primero.
3. **Falta de herramientas de auditoría rápida:** Procesos manuales y no consolidados para auditar claves, backups y formularios web.

Nuestra solución proporciona un **módulo CRUD de activos**, un **motor de cálculo de riesgo dinámico** basado en una **Matriz 5x5** ($\text{Nivel de Riesgo} = \text{Impacto} \times \text{Probabilidad}$), un **sistema de clasificación por semáforo** (Verde, Amarillo, Rojo), y **herramientas integradas de auditoría** con exportación ejecutiva a reportes en **PDF**.

---

## 🚀 Demo y Enlaces de Producción

* 🌐 **URL de Producción:** [https://assetshield-epn.netlify.app/](https://assetshield-epn.netlify.app/)
* 📦 **Repositorio en GitHub:https://github.com/Stevenggex/Zenit
* 📋 **Tablero Scrum en Jira (Proyecto ZEN):https://epn-team-dwx6xqzj.atlassian.net/jira/software/projects/ZEN/boards/35/backlog
---

## 👥 Equipo de Trabajo y Roles (Scrum Team - Grupo 5)

| Integrante | Rol Scrum / Especialidad | Módulo a Cargo |
| :--- | :--- | :--- |
| **Steven Gallo** | Scrum Master & Lead Full-Stack | Motor de Cálculo de Riesgo y Matriz 5x5 |
| **Lindsay Silva** | Frontend & UX/UI Lead | Layout Global, Hero/About & Dashboard Visual |
| **Luis Valladares** | Backend Developer | Módulo de Reportes & Exportación PDF |
| **Danny Salcedo** | Full-Stack Developer | Gestión de Activos (CRUD) |
| **Byron Valencia** | Full-Stack & Ciberseguridad QA | Catálogo de Vulnerabilidades y Evaluación |

---

## 🛠️ Tecnologías y Metodología

### Frontend & Diseño
* **HTML5 Semántico:** Contenedores estructurados (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`).
* **CSS3 Responsive (Mobile-First):** Estilos base construidos para smartphones (375px) con escalabilidad vía Media Queries para Tablets (768px) y Desktops (1440px).
* **UI/UX Design Systems:** Figma, Wireframes & Mockups multidispositivo (Smartwatch, Mobile, Tablet, Desktop, TV).

### Metodología & Herramientas
* **Agile / Scrum:** Gestión de historias de usuario, sprints y entregables mediante Jira Software.
* **Control de Versiones & CI/CD:** Git, GitHub y despliegue automatizado en Netlify.



## 📂 Estructura del Proyecto

```text
Zenit/
├── index.html                # Página principal (Hero & About Sections)
├── README.md                 # Documentación técnica del proyecto
├── .gitignore                # Exclusiones de control de versiones
│
├── css/
│   ├── normalize.css         # Reset de estilos universales
│   └── styles.css            # Hoja de estilos Mobile-First y Media Queries
│
├── js/
│   └── main.js               # Scripts de interacción (Menú Mobile, eventos)
│
└── assets/
    ├── img/                  # Logotipos, ilustraciones y recursos gráficos
    └── icons/                # Favicon e íconos de la interfaz
=======
# 🛡️ AssetShield — Sistema de Gestión de Activos de Información y Evaluación de Riesgos de Ciberseguridad

> **Asignatura:** Diseño de Interfaces  
> **Institución:** Escuela Politécnica Nacional (EPN) — Escuela de Formación de Tecnólogos (ESFOT)  
> **Carrera:** Tecnología en Desarrollo de Software  
> **Docente:** Ing. Byron Loarte  
> **Período:** 2026-A  

---

## 📌 Visión General del Proyecto

**AssetShield** es una plataforma web enterprise orientada a medianas y grandes empresas que buscan centralizar, controlar y auditar la seguridad de su infraestructura tecnológica. 

El sistema resuelve tres grandes problemáticas de las organizaciones:
1. **Falta de visibilidad y centralización:** Inventario disperso e informal de equipos y servicios.
2. **Evaluación de riesgos empírica:** Ausencia de un estándar claro para priorizar qué fallas corregir primero.
3. **Falta de herramientas de auditoría rápida:** Procesos manuales y no consolidados para auditar claves, backups y formularios web.

Nuestra solución proporciona un **módulo CRUD de activos**, un **motor de cálculo de riesgo dinámico** basado en una **Matriz 5x5** ($\text{Nivel de Riesgo} = \text{Impacto} \times \text{Probabilidad}$), un **sistema de clasificación por semáforo** (Verde, Amarillo, Rojo), y **herramientas integradas de auditoría** con exportación ejecutiva a reportes en **PDF**.

---

## 🚀 Demo y Enlaces de Producción

* 🌐 **URL de Producción:** [https://assetshield-epn.netlify.app/](https://assetshield-epn.netlify.app/)
* 📦 **Repositorio en GitHub:https://github.com/Stevenggex/Zenit
* 📋 **Tablero Scrum en Jira (Proyecto ZEN):https://epn-team-dwx6xqzj.atlassian.net/jira/software/projects/ZEN/boards/35/backlog
---

## 👥 Equipo de Trabajo y Roles (Scrum Team - Grupo 5)

| Integrante | Rol Scrum / Especialidad | Módulo a Cargo |
| :--- | :--- | :--- |
| **Steven Gallo** | Scrum Master & Lead Full-Stack | Motor de Cálculo de Riesgo y Matriz 5x5 |
| **Lindsay Silva** | Frontend & UX/UI Lead | Layout Global, Hero/About & Dashboard Visual |
| **Luis Valladares** | Backend Developer | Módulo de Reportes & Exportación PDF |
| **Danny Salcedo** | Full-Stack Developer | Gestión de Activos (CRUD) |
| **Byron Valencia** | Full-Stack & Ciberseguridad QA | Catálogo de Vulnerabilidades y Evaluación |

---

## 🛠️ Tecnologías y Metodología

### Frontend & Diseño
* **HTML5 Semántico:** Contenedores estructurados (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`).
* **CSS3 Responsive (Mobile-First):** Estilos base construidos para smartphones (375px) con escalabilidad vía Media Queries para Tablets (768px) y Desktops (1440px).
* **UI/UX Design Systems:** Figma, Wireframes & Mockups multidispositivo (Smartwatch, Mobile, Tablet, Desktop, TV).

### Metodología & Herramientas
* **Agile / Scrum:** Gestión de historias de usuario, sprints y entregables mediante Jira Software.
* **Control de Versiones & CI/CD:** Git, GitHub y despliegue automatizado en Netlify.



## 📂 Estructura del Proyecto

```text
AssetShield-Web/
├── index.html                # Página principal (Hero & About Sections)
├── README.md                 # Documentación técnica del proyecto
├── .gitignore                # Exclusiones de control de versiones
│
├── css/
│   ├── normalize.css         # Reset de estilos universales
│   └── styles.css            # Hoja de estilos Mobile-First y Media Queries
│
├── js/
│   └── main.js               # Scripts de interacción (Menú Mobile, eventos)
│
└── assets/
    ├── img/                  # Logotipos, ilustraciones y recursos gráficos
    └── icons/                # Favicon e íconos de la interfaz
>>>>>>> 8b96ff4 (feat: agregado de los logos en fondo claro y oscuro en formato svg)

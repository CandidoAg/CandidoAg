# ¡Hola! Soy Candido 👋 

### 🚀 Senior Fullstack Engineer | Distributed Systems & Local AI Architectures

Actualmente enfocado en el diseño de sistemas distribuidos, arquitecturas distribuidas de alta disponibilidad y soluciones offline-first con IA local integrada. Mi enfoque profesional combina la **robustez corporativa y asincronía del backend** con la **agilidad de interfaces modernas y reactivas** en web y mobile.

---

### 🛠️ Mi Stack Tecnológico

| Categoría | Tecnologías Principales | Ecosistema, DevOps & Ops |
| :--- | :--- | :--- |
| **Backend & Messaging** | ![.NET 8](https://img.shields.io/badge/.NET_8-512BD4?style=flat-square&logo=dotnet&logoColor=white) ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white) ![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white) ![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white) | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![EF Core](https://img.shields.io/badge/EF_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) |
| **AI & Background Workers**| ![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white) ![Hangfire](https://img.shields.io/badge/Hangfire-FF5722?style=flat-square&logo=fluentd&logoColor=white) ![Llama 3](https://img.shields.io/badge/Llama_3-6A5ACD?style=flat-square&logo=meta&logoColor=white) | ![Snyk](https://img.shields.io/badge/Snyk-70057C?style=flat-square&logo=snyk&logoColor=white) ![TruffleHog](https://img.shields.io/badge/TruffleHog-Black?style=flat-square) |
| **Frontend & Web** | ![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Astro](https://img.shields.io/badge/Astro-BC52EE?style=flat-square&logo=astro&logoColor=white) ![Tailwind CSS v4](https://img.shields.io/badge/Tailwind_CSS_v4-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) | ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![pnpm](https://img.shields.io/badge/pnpm-F69220?style=flat-square&logo=pnpm&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) |
| **Mobile Development** | ![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black) ![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white) | ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black) |

---

### 🏗️ Proyectos de Ingeniería Destacados

#### [⏳ ChronosNote](https://github.com/CandidoAg/ChronosNote)
> **AI-Powered Offline-First Workspace con Orquestación Asíncrona**
* **Arquitectura Clean Backend:** Diseñado en capas desacopladas con **.NET 8 Web API** y persistencia relacional aislada mediante **EF Core + SQLite**.
* **Seguridad & Multi-tenancy:** Control de accesos estricto mediante **JWT Authentication**, aislando consultas de datos a nivel de base de datos a través de claims de identidad personalizados para mitigar filtraciones cruzadas.
* **Frontend Reactivo:** Editor basado en **TipTap** integrado sobre **React 19 + TypeScript + Tailwind CSS v4** mediante una estrategia de empaquetado optimizada con **pnpm monorepo**.
* **Automation (CI):** Pipeline nativa en **GitHub Actions** encargada del linting automatizado, verificación de compilaciones cruzadas y generación en caliente de artefactos estáticos listos para producción.

#### [🛡️ AXON-OS](https://github.com/CandidoAg/AXON-OS)
> **Orquestador de Agentes Declarativos con Human-in-the-Loop**
* **Arquitectura de IA:** Sistema distribuido de microservicios (Planner/Worker) que descompone misiones complejas en grafos JSON ejecutables mediante **Ollama (Llama3)**.
* **Orquestación & Control:** Implementación de flujo *Human-in-the-Loop* para validación de misiones y registro de herramientas (*Tool Registry*) extensible.
* **Visualización Dinámica:** Dashboard avanzado con **React Flow** para el monitoreo en tiempo real de la ejecución de grafos y estados del sistema.
* **Seguridad (DevSecOps):** Pipeline de CI/CD integrado con **TruffleHog** para detección de secretos y **Snyk** para escaneo de vulnerabilidades SCA/SAST.

#### [🕹️ RetroVault](https://github.com/CandidoAg/retrovault) 
> **Ecosistema de E-commerce y Panel de Administración**
* **Arquitectura:** Implementación estricta de **Arquitectura Hexagonal** y **Domain-Driven Design (DDD)**.
* **Sistemas Distribuidos:** Orquestación de microservicios asíncronos mediante el **Saga Pattern con Apache Kafka**, garantizando consistencia eventual en procesos de stock y pagos.
* **Tooling:** Gestión eficiente de monorepo con **Turborepo** y **pnpm**.

#### [📝 NoteStack](https://github.com/CandidoAg/app-notas) | [🚀 Candido Stack](https://github.com/CandidoAg/candido-stack)
> **Proyectos Mobile y Web Performance Showcase**
* **NoteStack:** App multiplataforma con **Expo Router** blindada bajo principios OWASP mitigando vulnerabilidades de acceso no autorizado tipo **IDOR**.
* **Candido Stack:** Portfolio ultra optimizado con **Astro** (arquitectura de islas) y procesamiento dinámico de imágenes con **Sharp**.
  
---

### 📊 GitHub Metrics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=CandidoAg&show_icons=true&theme=dark&hide_border=true&count_private=true" alt="Candido's GitHub Stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=CandidoAg&layout=compact&theme=dark&hide_border=true&langs_count=6" alt="Top Languages" width="48%" />
</div>

---

### 📫 Contacto
* **Portfolio:** [candido-stack](https://candido-stack.vercel.app/)
* **LinkedIn:** [Cándido Aguilar](https://www.linkedin.com/in/c%C3%A1ndido-aguilar-7164ab193/)
* **Email:** [candido.aguilar.cano@gmail.com](mailto:candido.aguilar.cano@gmail.com)

---

<div align="center">

*“El código limpio es el resultado de un aprendizaje constante.”*

</div>

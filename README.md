<div align="center">

# ¡Hola! Soy Alejandro Larco 👋

**Desarrollador de Software | Full-Stack, RAG & IA Aplicada | Arquitecturas Híbridas & DevOps**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alejandro-larco-03297b42a/)
[![Portafolio](https://img.shields.io/badge/Portafolio-00f2fe?style=flat&logo=googlechrome&logoColor=black)](https://alej673.github.io)
[![Ubicación](https://img.shields.io/badge/Quito-Ecuador-4ade80?style=flat&logo=googlemaps&logoColor=white)](#)

</div>

Desarrollador de software radicado en Quito, Ecuador, enfocado en construir sistemas de punta a punta, integrar modelos de lenguaje (LLMs) y desplegar infraestructura resiliente. Diseño arquitecturas completas: desde ERPs en producción contenerizados con Docker y bases de datos relacionales hasta asistentes de IA con arquitectura híbrida local/nube, memoria vectorial (RAG), flujos agénticos, microservicios en Go y lógica de juego en Unreal Engine 5.

---

### 🛠️ Mi Stack Tecnológico

**Lenguajes & Bases de Datos**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![PHP](https://img.shields.io/badge/PHP_8.3-777BB4?style=flat&logo=php&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript_ES6-F7DF1E?style=flat&logo=javascript&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL_8.4-4479A1?style=flat&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)

**Backend, Frontend & Infraestructura (DevOps)**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel_13-FF2D20?style=flat&logo=laravel&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux_VPS-FCC624?style=flat&logo=linux&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Tauri](https://img.shields.io/badge/Tauri-24C8D8?style=flat&logo=tauri&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap_5-7952B3?style=flat&logo=bootstrap&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

**IA, RAG & Motores Gráficos**

![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white)
![Gemini API](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat)
![Whisper](https://img.shields.io/badge/Faster--Whisper-412991?style=flat&logo=openai&logoColor=white)
![Edge-TTS](https://img.shields.io/badge/Edge--TTS-00A4EF?style=flat)
![Unreal Engine 5](https://img.shields.io/badge/Unreal_Engine_5-0E1128?style=flat&logo=unrealengine&logoColor=white)

---

### 🚀 Proyectos destacados

#### 1. [L-IA: Asistente Híbrido (Local/Nube)](https://github.com/Alej673/L-IA)
Asistente de IA con un enrutador de consultas que balancea el procesamiento entre modelos locales (Gemma 2 en una GPU de 6 GB) y la nube (Gemini) según la intención, la presencia de código y los tokens estimados. Redujo su tiempo hasta el primer token de **9,13 s a 0,47 s (−94%)**. Incluye 2 documentos técnicos (38 páginas) y demo en video.
- **Técnicas:** memoria vectorial RAG en CPU (ChromaDB) con citación de fuentes, flujo agéntico con *tool calling* y Tool Manager de tres niveles de riesgo con confirmación humana, microservicios locales en Go (búsqueda paralela de archivos con goroutines, telemetría del sistema y lectura de Git), streaming SSE, multi-sesión en SQLite y voz local (Vosk, Faster-Whisper, Edge-TTS).
- **Stack:** Python, FastAPI, Go, Ollama, Gemini API, ChromaDB, Tauri, React.

#### 2. [Sistema ERP & Cotizador BTO — Arte Titi_Val](https://github.com/Alej673/sistema-bastones) 🌐 *[En Producción: artetitival.com](https://artetitival.com)*
Plataforma E-Commerce *Built-to-Order* y núcleo ERP para manufactura a medida desplegada en producción sobre un VPS Linux (Netcup) con 3 contenedores Docker aislados. Conecta la captación comercial pública con el control de inventario (Kardex en unidad mínima), motor de costeo fraccional reactivo y módulo de despacho resiliente.
- **Técnicas & DevOps:** patrón MVC, transacciones ACID con bloqueo de fila, *Single Source of Truth* (reglas de negocio centralizadas en BD), *UI Freeze* post-guardado, RBAC (`super_admin`, `admin`, `cliente`), despliegue automatizado vía script CI/CD (`deploy.sh`), proxy inverso Nginx con SSL (Let's Encrypt), validado bajo estrés con **k6 (200 usuarios concurrentes, 100% éxito)** y **Lighthouse (100/100 Best Practices, 92/100 SEO)**. Incluye 2 documentos de ingeniería (v2.0 y Adenda v2.1).
- **Stack:** PHP 8.3, Laravel 13, MySQL 8.4, Docker, Nginx, JavaScript ES6 (Vite), Bootstrap 5.

#### 3. [Demo UE5: IA Táctica y Shooter](https://github.com/Alej673/MyProject1)
Simulación táctica que aísla las lógicas base de la estética visual. El núcleo de percepción sensorial (cono de visión y oído) alimenta un Behavior Tree modular.
- **Técnicas:** arquitectura híbrida C++/Blueprint, POO, SOLID, físicas Chaos (ragdolls paramétricos con optimización de Rigid Body Sleep), balística hitscan con cobertura procedural.
- **Stack:** C++, Unreal Engine 5, Blueprints.

---

### 📫 Cómo contactarme

- **LinkedIn:** [Alejandro Larco](https://www.linkedin.com/in/alejandro-larco-03297b42a/)
- **Portafolio web:** [alej673.github.io](https://alej673.github.io)
- **Ubicación:** Quito, Ecuador 📍

> *"El buen código no solo resuelve el problema, también explica cómo lo resolvió."*

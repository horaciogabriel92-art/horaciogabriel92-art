# Hola, soy Horacio Gabriel!

Bienvenido a mi perfil. Soy un tipo curioso, apasionado por la intersección entre la **Inteligencia Artificial y la Automatización de Procesos**.

---

### 🚀 Actualmente Explorando & Aprendiendo

Mi enfoque actual está en la creación de soluciones escalables que integran **modelos de lenguaje (LLMs)** con **flujos de trabajo autónomos**.

-   **Agentes Autónomos & Sistemas Multi-Agente (Swarms)**: Diseño arquitecturas donde múltiples agentes colaboran para resolver tareas complejas, utilizando herramientas como **n8n** y **LangChain**.
-   **IA Generativa Local & Cloud**: Implementación e integración de modelos avanzados (**Gemini**, **Ollama**, **Bedrock**, **Llama**) para procesamiento de lenguaje natural y toma de decisiones automatizada.
-   **Python & Data Engineering**: Desarrollo de scripts robustos para auditoría y limpieza de datos, automatización de reportes y estructuración de pipelines de información.
-   **Visión Computacional & Realidad Aumentada**: Experimentación con interfaces naturales, tracking de manos y simulaciones físicas (fluidos) integradas en tiempo real.
-   **Desarrollo Full Stack Moderno**: Construcción de aplicaciones web interactivas y seguras, con foco en **React** y arquitecturas sin servidor.
-   **Seguridad & Autenticación**: Implementación de sistemas de login seguro (OAuth) y protección de rutas en aplicaciones web.

---

### 🛠️ Tech Stack & Herramientas

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white" />
  <img src="https://img.shields.io/badge/n8n-FF6584?style=for-the-badge&logo=n8n&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" />
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=google-gemini&logoColor=white" />
</p>

---

### 🤖 Workflow Architecture

```mermaid
graph TD;
    User([Usuario]) -->|Solicitud| API_Gateway[API Gateway / Webhook];
    API_Gateway --> Orchestrator{Agente Orquestador};
    Orchestrator -->|RAG Query| VectorDB[(Vector Database)];
    Orchestrator -->|Tool Call| ExternalAPI[External Services API];
    Orchestrator -->|Refinamiento| LLM[LLM (Gemini/Llama)];
    LLM -->|Respuesta| Orchestrator;
    Orchestrator -->|Resultado Final| User;
    style Orchestrator fill:#f9f,stroke:#333,stroke-width:2px;
    style LLM fill:#bbf,stroke:#333,stroke-width:2px;
```

---
gh skyline --year 2026

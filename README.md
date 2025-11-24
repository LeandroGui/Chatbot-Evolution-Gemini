# 🚀 Chatbot Evolution: De Scripts a Agentes Autónomos (Gemini 2.5 + LangGraph)

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Gemini](https://img.shields.io/badge/AI-Gemini%202.5%20Flash-orange)
![LangGraph](https://img.shields.io/badge/Architecture-LangGraph-purple)
![Pydantic](https://img.shields.io/badge/Data-Pydantic-red)

Este proyecto es un caso de estudio técnico que demuestra la evolución en asistentes conversacionales. A través de tres paradigmas, resolvemos el mismo problema de negocio (gestión de reservas) con tecnologías crecientemente avanzadas.

## 🧬 Las 3 Fases del Proyecto

### 1. 🏛️ Fase Determinista (Enfoque Tradicional)
Implementación basada en **Máquinas de Estados** y **Regex**.
- **Enfoque:** Imperativo.
- **Limitación:** Fragilidad ante inputs no previstos por el programador.

### 2. 🧠 Fase Semántica (IA Generativa)
Implementación con **Gemini 2.5 Flash** y **Pydantic**.
- **Enfoque:** Extracción de entidades (NER) mediante LLMs.
- **Limitación:** El modelo "alucina" acciones; no tiene conexión real con el sistema (Base de Datos).

### 3. 🤖 Fase Agéntica (LangGraph)
Implementación de un **Agente ReAct** autónomo.
- **Enfoque:** Cognitivo (Razonamiento + Acción).
- **Tecnologías:** LangGraph, LangChain, Google GenAI SDK.
- **Highlights Técnicos:**
    - **Inyección de Prompt:** Configuración robusta del comportamiento del sistema.
    - **Parseo Multimodal:** Función personalizada para normalizar respuestas complejas de Gemini 2.5.
    - **Tool Calling:** Capacidad real para consultar disponibilidad y escribir en la base de datos.

## 🛠️ Instalación y Uso

### Opción A: Google Colab (Recomendado)
El notebook está diseñado para ejecutarse en la nube. Requiere configurar la `GOOGLE_API_KEY` en los "Secretos" de Colab.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1YLPflLqQvF3cpSNwbJ92m3SLE13DUU_t?usp=sharing)

### Opción B: Local
1. Clona el repositorio:
   ```bash
   git clone https://github.com/LeandroGui/Chatbot-Evolution-Gemini.git
2.  Instala dependencias:
    ```bash
    pip install -r requirements.txt
    ```
3.  Configura tu variable de entorno `GOOGLE_API_KEY`.


✒️ Autor
Leandro - Desarrollador & Entusiasta de IA

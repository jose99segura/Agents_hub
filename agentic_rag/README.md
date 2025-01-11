# Agentic RAG con CrewAI 🤖

Sistema inteligente de búsqueda y respuesta que utiliza CrewAI para procesar documentación local y realizar búsquedas web cuando sea necesario, todo impulsado por Llama 3.2 ejecutándose localmente.

## Características principales

- Búsqueda inteligente en documentos locales
- Fallback automático a búsqueda web cuando no encuentra respuestas en la documentación local
- Procesamiento local utilizando Llama 3.2
- Sistema de agentes coordinados mediante CrewAI
- Respuestas contextuales y precisas

## Requisitos previos

- Python 3.8 o superior
- GPU compatible (recomendado para mejor rendimiento)
- Acceso a internet para búsquedas web
- API Key de Serper (obtener en [https://serper.dev/](https://serper.dev/))

## Instalación

1. Clona el repositorio
```bash
git clone [URL_DEL_REPOSITORIO]
cd agentic-rag-crewai
```

2. Instala las dependencias
```bash
pip install -r requirements.txt
```

3. Descarga el modelo Llama 3.2 en Ollama

4. Obten la API de Serper y guardala en tu .env

## Uso

1. Ejecuta la aplicación
```bash
streamlit run app_llama3.2.py
```

3. Realiza tus consultas y obtén respuestas basadas en tu documentación local o búsquedas web


## Contacto

Desarrollado por [Saúl Gómez Jiménez](https://www.linkedin.com/in/saul-gomez-jimenez-47b30328b/)


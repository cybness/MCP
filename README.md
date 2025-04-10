﻿# Proyecto de Sistema Tolerante a Fallos con MCP
 ![image](https://github.com/user-attachments/assets/27a449af-4e3b-4ecc-8371-7abeac0de22e)


Este proyecto implementa un sistema distribuido y tolerante a fallos utilizando **Model Context Protocol (MCP)** y la librería **Pydantic AI**. El sistema permite gestionar conexiones a servidores MCP y ejecutar herramientas dentro de un entorno modular, desacoplado y resiliente a fallos, permitiendo la recuperación segura de errores. Los servidores MCP se añaden a un Json, de forma similar a como se haría en Claude o cursor.

## Tecnologías Utilizadas

- **MCP (Model Context Protocol)**: Protocolo diseñado para la gestión de herramientas distribuidas que soporta tolerancia a fallos de forma nativa. Utilizado para conectar y ejecutar herramientas de forma modular en servidores.
  
- **Pydantic AI**: Librería utilizada para integrar herramientas MCP con modelos de inteligencia artificial en un entorno controlado y de fácil uso.

- **Python**: Lenguaje de programación principal utilizado para implementar la lógica del sistema.

- **Asincronía (Asyncio)**: Uso de operaciones asíncronas para manejar conexiones y recursos de manera eficiente, permitiendo la comunicación y gestión en tiempo real sin bloqueos.

- **Dotenv**: Para la gestión de variables de entorno como las claves de API y configuraciones específicas del sistema.

## Requisitos

Antes de ejecutar el proyecto, asegúrate de tener los siguientes requisitos instalados:

- Python 3.8 o superior
- Node.js (para ejecutar comandos de MCP)
- Librerías de Python:
  - `pydantic_ai`
  - `mcp`
  - `rich`
  - `dotenv`

## Configura las Variables de entorno con el modelo de IA a emplear, con Ollama la APIKEY es opcional
 
```bash
PROVIDER=Ollama
BASE_URL=http://localhost:11434/v1
MODEL_CHOICE=llama3.2:latest

Puedes instalar las dependencias necesarias utilizando `pip`:


```bash
pip install -r requirements.txt




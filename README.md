# AI Transparency Toolkit

🧰 Herramienta open-source para auditar sesgos en modelos de IA generativa

AI Transparency Toolkit es un proyecto de código abierto diseñado para analizar, visualizar y comparar los sesgos presentes en modelos de lenguaje e imagen como GPT, Claude o Stable Diffusion.

## ✨ Características principales

- Carga masiva de prompts y ejecución en múltiples modelos
- Comparación visual y textual de respuestas
- Detección de sesgos de género, raza, ideología, etc.
- Seguimiento histórico de versiones de modelos
- Dashboard interactivo y exportable

## 🧱 Tecnologías

- Backend: Python + FastAPI
- Frontend: React + TailwindCSS
- DB: PostgreSQL o SQLite
- Contenedores: Docker

## 📦 Estructura

```bash
backend/     # APIs y lógica de análisis
frontend/    # Interfaz de usuario
data/        # Resultados y prompts
docs/        # Documentación

# Ruta RAG - Log Personal JMED

## Environment
| Software | Versión |
|----------|---------|
| macOS    | 15.5 (Sequoia) |
| Homebrew | 4.5.9 |
| Git      | 2.50.1 |
| Python   | 3.12.1 (pyenv) |
| VS Code  | 1.90 |

## Virtual environment & dependencies
```bash
# Crear entorno (Apple Silicon · Python 3.12.1 via pyenv)
python -m venv .venv
source .venv/bin/activate

# Actualizar pip
pip install --upgrade pip           # pip 25.1.1

# Instalar paquetes base
pip install openai langchain faiss-cpu tiktoken

# Verificar versiones
$ pip list | grep -E "openai|langchain|faiss|tiktoken"
faiss-cpu               1.11.0
langchain               0.3.26
langchain-core          0.3.68
langchain-text-splitters 0.3.8
openai                  1.95.1
tiktoken                0.9.0
```

## Certificaciones

| # | Certificado | Emisor | Fecha | URL |
|---|-------------|--------|-------|-----|
| 1 | Career Essentials in Generative AI | Microsoft & LinkedIn | 2025‑07‑13 | https://www.linkedin.com/learning/certificates/6b7cfe816d24b037ca9567444f7a764467cf7b36d3dd9ecf2b0b5393788af37 |

## Progreso de formación RAG

| # | Curso / Badge (próximos 30 días) | Estado | Entregables |
|---|----------------------------------|--------|-------------|
| 1 | MSFT Career Essentials GenAI | ✅ Completado | [PDF](certs/msft_genai.pdf) |
| 2 | LangChain for LLM App Dev | ⏳ En curso | `courses/02_langchain_rag/` |
| 3 | Google Cloud GenAI Skill Badge | ⏳ Pendiente | — |

## Changelog
- **2025‑07‑13** · Setup completo (Homebrew, Git, Python 3.12, venv) y certificación Microsoft GenAI añadida.

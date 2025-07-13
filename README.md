# Ruta RAG – Semana 0
## Environment
| Software | Versión |
|----------|---------|
| macOS    | 15.5 (Sequoia) |
| Homebrew | 4.5.9 |
| Git      | 2.50.1 |
| Python   | 3.12.1 (pyenv) |
| VS Code  | 1.90 |

## Virtual environment & dependencies
```bash
# Crear entorno (Apple Silicon · Python 3.12.1 via pyenv)
python -m venv .venv
source .venv/bin/activate

# Actualizar pip
pip install --upgrade pip           # pip 25.1.1

# Instalar paquetes base
pip install openai langchain faiss-cpu tiktoken

# Verificar versiones
$ pip list | grep -E "openai|langchain|faiss|tiktoken"
faiss-cpu                1.11.0
langchain                0.3.26
langchain-core           0.3.68
langchain-text-splitters 0.3.8
openai                   1.95.1
tiktoken                 0.9.0

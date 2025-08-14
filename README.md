# AIFLOW SEC RAG POC

Lightweight RAG over SEC 10-K filings.

## Local setup (macOS)
```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -U pip
pip install -e ".[dev]"
pre-commit install
pre-commit run -a

# Guardrailed Free LLM Demo

## Setup with Poetry

```bash
poetry install
poetry run jupyter notebook
```

Open `guardrailed_llm_demo.ipynb`.

## Setup with pip

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

## Model

Uses `google/flan-t5-base`, a free Hugging Face model downloaded locally.

## Flow

User Question -> Input Guardrail -> LLM -> Output Guardrail -> Response

This is a simple educational/demo implementation, not a production safety framework.

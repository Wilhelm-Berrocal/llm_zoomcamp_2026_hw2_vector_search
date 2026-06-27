# LLM Zoomcamp 2026 - Homework 2: Vector Search

Homework repo for Module 2 of LLM Zoomcamp 2026.

The notebook solves the vector search homework using the course lesson pages as the knowledge base. It covers embeddings, cosine similarity, chunking, vector search with minsearch, text search comparison, and hybrid search with RRF.

## Setup

Install dependencies with `uv`:

```bash
uv sync
```

Download the local ONNX embedding model:

```bash
uv run python download.py
```

This creates `models/Xenova/all-MiniLM-L6-v2/`.

## Run The Notebook

Start Jupyter:

```bash
uv run jupyter notebook
```

Open `homework.ipynb` and run the cells in order.

## Important Files

- `homework.ipynb`: solved homework notebook.
- `download.py`: downloads the ONNX embedding model.
- `embedder.py`: helper class for generating embeddings.
- `pyproject.toml`: project dependencies.

## Notes

Generated files such as `models/`, `.venv/`, `__pycache__/`, and notebook checkpoints are ignored.

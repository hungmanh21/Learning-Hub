# Qdrant Vector Database Setup & Experiments

This repository provides instructions to set up the **Qdrant vector database** and reproduce experiments with **multi-vector embeddings**.

---

## 🚀 Getting Started

### 1. Run Qdrant with Docker

Follow the official Qdrant quickstart guide to set up and run Qdrant:
👉 [Qdrant Documentation – Quickstart](https://qdrant.tech/documentation/quickstart/)

---

### 2. Install Project Dependencies

This project uses [`uv`](https://github.com/astral-sh/uv) for dependency management.
Simply run:

```bash
uv sync
```

This will create the virtual environment and install all required dependencies.
Everything code experiment is inside `main.ipynb`.
---

## 📊 Notes from Experiments

* **Multi-vector embedding support**:
  At the time of our experiments, only a limited number of models support multi-vector embeddings.

* **Storage overhead**:
  Multi-vector embeddings require significantly more disk space compared to single-vector embeddings — approximately **6× larger** in our tests.

---

## 📌 Conclusion

While multi-vector embeddings offer potential improvements in retrieval, they come with higher storage costs and limited model availability.
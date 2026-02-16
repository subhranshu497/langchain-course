LangChain course example project — minimal FastAPI app

Quickstart
1. Create and activate a virtual environment (if you haven't already):

```bash
python3 -m venv .venv
source .venv/bin/activate
```

2. Install dependencies (inside the venv):

```bash
python -m pip install --upgrade pip
pip install "fastapi" "uvicorn[standard]"
```

3. Run the app:

```bash
uvicorn main:app --reload
```

Notes
- This repo keeps a `.venv` to make running the example straightforward. Use the venv's Python/uvicorn for consistent results.
- Python version for the project is recorded in `.python-version`.

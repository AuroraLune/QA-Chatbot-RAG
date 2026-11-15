# Health Web RAG

A Vietnamese health information assistant that searches trusted sources and answers with citations.

## MVP scope

- General health information in Vietnamese.
- Answers should be grounded in retrieved sources and show links.
- No diagnosis, prescriptions, or medication dosing advice.
- Questions outside scope should be declined or redirected.

## Current status

This is the initial Streamlit interface scaffold. Web search and LLM providers are not connected yet.

## Run

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
streamlit run app.py
```

On Windows, activate the environment with `.venv\\Scripts\\activate`.

# Apple Retail Analytics Project (Synthetic Data)

Portfolio analytics project using a simulated Apple retail-like dataset generated in Python.
Demonstrates relational modeling, SQL analytics, Python analysis, and reporting.

## Objectives
- Answer business questions with SQL + Python
- Produce visuals and dashboard-ready outputs
- Analyze the retail sales situation.

## Business Questions
- Which products/categories drive revenue and unit volume?
- Which stores/cities perform best and worst?
- What categories show higher warranty claim rates?
- How does revenue trend month-over-month?

## Repo Structure
- `sql/` – schema + metric queries
- `notebooks/` – EDA Python notebooks
- `dataset/` – data documentation (raw data is generated locally)
- `reports/figures/` – charts (PNG) used in README / reporting
- `docs/` – data dictionary and project plan

## How to Run (Windows)
```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt

python src\analysis.py

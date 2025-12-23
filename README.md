# Apple Retail Analytics Project (Synthetic Data)

Portfolio analytics project using a simulated Apple retail-like dataset generated in Python.
Demonstrates relational modeling, SQL analytics, Python analysis, and reporting.

## Objectives
- Generate realistic retail data (sales line-items, products, stores, customers, warranty claims)
- Load data into a relational database (SQLite)
- Answer business questions with SQL + Python
- Produce visuals and dashboard-ready outputs

## Business Questions
- Which products/categories drive revenue and unit volume?
- Which stores/cities perform best and worst?
- What categories show higher warranty claim rates?
- How does revenue trend month-over-month?

## Repo Structure
- `src/` – Python scripts (data generation, DB build, analysis)
- `sql/` – schema + metric queries
- `notebooks/` – optional EDA notebooks
- `data/` – data documentation (raw data is generated locally and ignored by git)
- `reports/figures/` – charts (PNG) used in README / reporting
- `docs/` – data dictionary and project plan

## How to Run (Windows)
```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt

python src\analysis.py

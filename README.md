# E-Commerce Sales Analysis
> Exploratory data analysis on 100k real orders from Olist, a Brazilian e-commerce platform (2016–2018).

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.0-150458?style=flat&logo=pandas)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat&logo=jupyter)
![Dataset](https://img.shields.io/badge/Dataset-Kaggle%20Olist-20BEFF?style=flat&logo=kaggle)

---

## Objective

Practice the full data analyst pipeline on a real-world dataset :
- Data loading & cleaning (missing values, datetime conversion)
- Multi-table merging (8 CSV files → 1 unified DataFrame)
- Business KPIs calculation (revenue, AOV, customer count)
- Customer segmentation using the RFM method
- Data visualization with matplotlib & seaborn

## Project Structure

```
ecommerce-analysis/
├── notebooks/
│   └── analysis.ipynb      # main notebook
├── outputs/
│   ├── report.html         # exported notebook (no Python needed)
│   └── charts/             # saved visualizations
├── data/                   # CSV files (not tracked by git — see below)
├── requirements.txt
└── README.md
```

---

## Technologies

- **Python 3.14**
- **pandas** — data manipulation
- **numpy** — numerical computing
- **matplotlib** — plotting
- **seaborn** — statistical visualization

---

## Dataset

[Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) — Kaggle  
100k orders · 8 CSV files · 2016–2018 · anonymized real commercial data

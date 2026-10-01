# Retail Sales & Customer Demographics Analysis

An exploratory retail analytics notebook with a Gradio dashboard for inspecting sales, customer demographics, and product-category patterns.

**Technology:** Python · pandas · Matplotlib · Seaborn · Gradio

## Features

- Calculate retail KPIs and summarize transaction values.
- Plot sales over time and revenue by product category.
- Explore gender distribution, age/spending relationships, quantities, and correlations.
- Launch the notebook's Gradio interface to display the analysis outputs.

## Repository guide

| Path | Purpose |
|---|---|
| [analysis-retail-sales.ipynb](analysis-retail-sales.ipynb) | Analysis and Gradio dashboard code. |
| [retail_sales_dataset.csv](retail_sales_dataset.csv) | Retail transaction dataset. |

## Requirements and current limitations

The CSV is included, but the notebook reads a Kaggle path in more than one cell. Update each occurrence to the local dataset before running. Execute the analysis and dashboard cells in order. The interface is defined inside the notebook; no separate `app.py` is committed.

## Getting started

```bash
git clone https://github.com/IbrahimAbdelsattar/Retail_Sales_and_Customer_Demographics_Analysis.git
cd Retail_Sales_and_Customer_Demographics_Analysis
```

Use a Python virtual environment:

```bash
python -m venv .venv
```

Activate it with `source .venv/bin/activate` on macOS/Linux or `.venv\Scripts\Activate.ps1` in PowerShell.

```bash
python -m pip install jupyter pandas numpy matplotlib seaborn gradio
python -m jupyter notebook
```

Open the notebook listed above and run its cells in order. Adjust dataset and model paths as described in the limitations section.

# Musa MegaMart — Retail Sales Analysis

A simulated data analyst brief for Musa MegaMart, a multinational retail corporation evaluating a retailer for acquisition. The task is to analyse 2M+ sales transactions, calculate business KPIs, assess whether the retailer's discount strategy is attracting customers without eroding margin, and surface trends across time, product, and geography.

---

## Business Context

The brief is structured as an analyst scenario: given raw flat files from the acquisition target, build a unified dataset, calculate the KPIs a buyer would care about, and determine whether the discounting behaviour is commercially sustainable.

The project brief image (`MMM Brief.png`) in the repo lays out the full scenario and deliverables.

---

## Analysis Covered

**Project 1: Initial Sales Analysis** (`03_project1.ipynb`)
Exploration of the raw dataset, revenue and order volume by category and region, and identification of top-performing segments.

**Time Series Analysis** (`04_time_series.ipynb`)
Month-over-month and year-over-year sales trends, seasonality patterns, and rolling averages to smooth noise.

**Project 2 — KPIs & Discount Assessment** (`07_project2.ipynb`)
Core business KPIs (revenue, profit, margin, return rate), discount depth analysis by category, and margin impact modelling to assess whether promotional activity is value-accretive or destructive.

---

## Notebooks

| Notebook | Description |
|---|---|
| `01_DataFrames.ipynb` | DataFrame construction, indexing, filtering, and basic aggregation |
| `02_data_viz.ipynb` | Chart types and visualisation patterns using Matplotlib and Seaborn |
| `03_project1.ipynb` | Initial sales analysis — revenue, volume, and segment breakdowns |
| `04_time_series.ipynb` | Time series trends, seasonality, and rolling window analysis |
| `05_import_export.ipynb` | Optimised multi-file ingestion with dtype specification and export |
| `06_combining_dfs.ipynb` | Merging and joining DataFrames into a unified source of truth |
| `07_project2.ipynb` | KPI calculation and discount margin assessment |

---

## Files

| File | Description |
|---|---|
| `csv_data_files.tar.bz2` | Compressed archive of all source CSV files — extract before running notebooks |
| `MMM Brief.png` | Original project brief outlining the scenario and analytical objectives |

---

## Setup

```bash
# Extract the data files
tar -xjf csv_data_files.tar.bz2

# Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# Launch notebooks
jupyter notebook
```

---

## Tools

- **Python** — Pandas, NumPy
- **Matplotlib / Seaborn** — data visualisation
- **Jupyter Notebook** — analysis environment

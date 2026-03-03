# Data Crunching with Pandas

Python notebooks for the **Big Data Technologies (BDT)** master course at the University of Trento.

## Course

In these lab sessions students learn to manipulate and analyse data with pandas: loading and inspecting datasets, selecting and filtering rows/columns, computing derived columns, grouping and aggregating, merging DataFrames, sorting, and visualising results with Seaborn.

## Repository Structure

| File | Description |
|---|---|
| `pandas example.ipynb` | Worked examples of key pandas operations (Series, DataFrames, groupby, merge, apply, etc.) |
| `ex1.ipynb` | Lab exercise for students to complete |
| `Solutions.ipynb` | Reference solutions (teacher use) |

## Data Files

| File | Description |
|---|---|
| `data/sales.csv` | Sales transaction records |
| `data/weather.csv` | Weather measurements dataset |
| `data/cadastral_data.csv` | Cadastral (land registry) data |
| `data/house_status.parquet` | House status data in Parquet format |
| `data/books.json` | Book catalogue in JSON format |
| `data/product.json` | Product catalogue in JSON format |
| `data/stations.json` | Station data in JSON format |

## Prerequisites

- Python **3.11** (pinned in `.python-version`)
- Dependencies listed in `requirements.txt`

## Setup

1. Install the requirements:

```bash
pip install -r requirements.txt
```

2. Launch Jupyter Lab:

```bash
jupyter lab
```

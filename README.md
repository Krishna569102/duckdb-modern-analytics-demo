# DuckDB Modern Analytics Demo

This project demonstrates an end-to-end data analytics workflow using DuckDB and Python — inspired by the analytics-first philosophy of MotherDuck.

## Features
- Cleans and loads the Global Superstore dataset
- Stores data in DuckDB for efficient querying
- Runs SQL queries and visualizes insights

## Structure
- notebooks/: Data cleaning, DuckDB setup, queries, and visualization
- data/raw/: Input CSV
- data/processed/: Cleaned data and DuckDB database

## Run Locally
```bash
pip install -r requirements.txt
jupyter notebook
```
Then open `01_load_and_clean.ipynb`.

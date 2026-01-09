# PySpark Practice & ML Walkthrough

> A small, hands-on collection of PySpark notebooks and scripts I used to learn Spark DataFrame operations and MLlib basics.  
> These notebooks were written while actively learning and experimenting in Google Colab, so the code is intentionally exploratory and practical.

---

## What this repo contains

Files in this repository (already included in the project):

- `pySpark1.ipynb` — PySpark fundamentals and DataFrame operations
- `pySparkML.ipynb` — MLlib examples (regression + classification)
- `student_practice_data.csv`
- `sample_pyspark_data.xlsx`
- `missing_values_practice.csv`
- `pyspark_mllib_practice.csv`
- `test1.csv`
- `README.md`

---

## Learning source & inspiration

> **Important note on inspiration**

This project is **heavily inspired by the PySpark tutorial series by Krish Naik**.

I followed his tutorials while learning PySpark and MLlib and used them as a **learning reference**, then:
- rewrote the code while practicing,
- added my own comments and experiments,
- modified examples to better understand concepts like missing-value handling, feature engineering, and evaluation metrics.

This repository reflects my **learning journey**, not a from-scratch original framework.  

If you are new to PySpark, I highly recommend checking out his content before or alongside this repo.

---

## Quick overview — what you'll learn

- Creating a `SparkSession`
- Reading CSV data into Spark DataFrames
- Inspecting schema, data types, and summary statistics
- Selecting, filtering, and chaining conditions
- Adding, renaming, and dropping columns
- Handling missing values (`drop`, `fill`, `Imputer`)
- Converting Excel → CSV using pandas for Spark
- Building ML pipelines using MLlib
- Regression & classification evaluation metrics
- Feature scaling and model comparison

---

## Requirements

Tested primarily on **Google Colab**.

Required Python packages:

```bash
pip install pyspark pandas openpyxl

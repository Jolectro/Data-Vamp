# Data-Vamp — Day 1: Student Performance Dataset Exploration

**Data-Vamp** stands for *Data Validation, Analysis, Modeling & Preparation*.
This project documents my 30-day journey into becoming a stronger data analyst — one dataset at a time.

## Day 1 — First Contact with the Dataset

Today, I worked with the **Student Performance** dataset from Kaggle.
The goal was simple: understand what the data looks like before doing anything else.

## What I Did

### 1. Imported and Inspected the Dataset

* Loaded the CSV into a Jupyter Notebook
* Viewed the first 5–10 rows
* Checked column names, data types, and basic structure
* Identified early issues (inconsistent types, awkward column names, etc.)

### 2. Looked for Common Real-World Problems

Because real datasets rarely come clean:

* Missing values
* Duplicates
* Mixed data types
* Outliers
* Columns that aren’t immediately meaningful (e.g., `G1`, `G2`, `G3`)

### 3. Set Up a Simple Project Structure

```
Data-Vamp/
│── data/
│    └── raw/student_performance.csv
│── notebooks/
│    └── Day1_Exploration.ipynb
│── README.md
```

## Why This Step Matters

Every data analysis project starts with three fundamental questions:

1. **What information do I have?**
2. **Is it clean enough to trust?**
3. **What problems will this dataset create for me later?**

Day 1 builds the foundation for everything that comes next.

## Next Steps

On Day 2, I will:

* Perform deeper EDA
* Create basic visualizations
* Start identifying factors that may influence student performance

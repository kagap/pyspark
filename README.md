# ⚡ PySpark & Databricks Starter Pack

A set of 15 interactive Jupyter Notebook modules for learning distributed data processing with **Apache Spark** and **Databricks**, available in both **English** ([`EN/`](EN)) and **Polish** ([`PL/`](PL)). A continuation of the [python-starter-pack](https://github.com/kagap/python-starter-pack) → [sql-](https://github.com/kagap/sql-) → [statistic](https://github.com/kagap/statistic) course series. Each notebook is built with a clean layout and locked theory cells to keep the focus entirely on coding practice.

## 📌 What's Inside

| # | Topic |
|---|-------|
| 1 | Introduction to Spark and Databricks |
| 2 | DataFrame API |
| 3 | Transformations & Aggregations |
| 4 | JOINs |
| 5 | Spark SQL |
| 6 | Reading & Writing Data |
| 7 | Window Functions |
| 8 | UDFs |
| 9 | Optimization & Performance |
| 10 | Delta Lake Basics |
| 11 | Lakehouse Architecture |
| 12 | MLlib Basics |
| 13 | MLlib Evaluation & Tuning |
| 14 | Working in the Databricks Workspace |
| 15 | Final Project |

* **Core Theory & Examples:** Clear explanations paired with runnable PySpark (DataFrame API, Spark SQL, MLlib, Delta Lake) for each topic.
* **Interactive Exercises:** Hands-on tasks with expandable spoiler solutions.
* **Protected Content:** Theory and description cells are configured as non-editable (`"editable": false`, `"deletable": false`) to prevent accidental changes while working through the material.

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/kagap/pyspark.git
   ```
2. Install the Python dependencies (requires a JDK for Spark to run):
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter:
   ```bash
   jupyter notebook
   ```
4. Pick your language folder ([`EN`](EN) or [`PL`](PL)) and start with Module 1. Module 14 covers the Databricks workspace UI specifically and is best followed with a free [Databricks Community Edition](https://community.cloud.databricks.com/) account.

# Contoso: an analysis with sql and python through Colab.

![Status](https://img.shields.io/badge/Status-Completed-success)
![SQL](https://img.shields.io/badge/DB-DuckDB_%2F_SQL-blue)
![Python](https://img.shields.io/badge/Python-Pandas_%7C_Seaborn-green)

## 📌 Project Overview
**The Goal:** To analyze the 2023 sales dataset compared to an average of the three years before, and to have an idea of the role of discounts from a BI and an econometric perspective on the reliability of correlation.

## 🛠️ Tech Stack
* **Database Engine:** DuckDB (High-performance analytical SQL database).
* **Environment:** Google Colab (Jupyter Notebook).
* **Languages:**
    * **SQL:** Advanced querying for data extraction, metric calculation, and logical classification.
    * **Python:** data visualisation.
* **Libraries:** `jupysql`, `pandas`, `matplotlib`, `seaborn`.

---

## 🔍 Key Analysis & Methodology

### 1. Data Aggregation & Metric Calculation
I utilized SQL to aggregate over **100,000+ sales records**, calculating key financial metrics at the `Subcategory` level:
* **Average Discount %:** Normalized calculation of price reduction.
* **Profit Margin %:** Real-time calculation of `(NetPrice - UnitCost) / NetPrice`.
* **Volume:** Total units sold per category.


### 2. Querying profit margins and discounts to use them for a scatter plot where the negative correlation was found. 
The plausible causes of omitted variable bias that may influence the correlation were stated, so as to avoid making a risky and potentially false causal claim.

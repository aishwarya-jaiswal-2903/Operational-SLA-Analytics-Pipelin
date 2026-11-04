# End-to-End Operational Analytics & Data Pipeline

An End-to-End Operational Analytics & Data Pipeline built using SQL, Python, and Pandas to automate corporate SLA tracking, handle robust data cleaning, and generate executive business summary metrics.

## 🛠️ Tech Stack & Concepts Implemented
- **Database Simulation:** SQLite3 embedded queries for data tracking.
- **Data Parsing:** `pd.to_numeric` parsing to catch faulty string inputs and prevent crashes.
- **Data Imputation:** Mean imputation using `.fillna()` to preserve data integrity.
- **Feature Engineering:** Vectorized logic using `np.where` for automated SLA flags.
- **Aggregations:** Regional summary matrices using `.groupby()`.

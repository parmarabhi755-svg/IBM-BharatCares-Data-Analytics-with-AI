# Retail Sales Data Analysis and Revenue Forecasting Using AI

**Author:** Abhishek  
**Program:** IBM SkillsBuild Data Analytics with AI Academic Internship  
**Conducted by:** BharatCares in association with AICTE

## Project description
This project demonstrates a reproducible data analytics workflow using a synthetic retail-sales dataset covering 2023–2025. It summarizes revenue, profit, units sold, product and regional performance, visualizes monthly trends, and evaluates a Random Forest regression model for daily revenue estimation.

> **Dataset note:** The dataset is synthetic and generated for educational demonstration. It does not represent a real company or real customer transactions.

## Files
- `Abhishek_RetailSalesAnalytics.ipynb` — complete Jupyter Notebook, analysis and model.
- `requirements.txt` — Python dependencies.
- `Abhishek_RetailSalesAnalytics_ProjectReport.docx` — project report.
- `README.md` — project overview and run instructions.
- `retail_sales_dataset.csv` — reproducible dataset used by the notebook.

## Technologies
Python, Jupyter Notebook, pandas, NumPy, Matplotlib, scikit-learn, Random Forest regression.

## Dataset
The CSV is included in this project folder. It contains daily records by product and region with date, product, category, units sold, unit price, discount, revenue, cost and profit. Since the data is synthetic, there is no external dataset URL. The notebook can also regenerate a dataset if the CSV is missing.

## Setup and run
1. Install Python 3.10 or newer.
2. Open a terminal in this folder.
3. Install dependencies:
   ```bash
   python -m pip install -r requirements.txt
   ```
4. Launch Jupyter:
   ```bash
   jupyter notebook
   ```
5. Open `Abhishek_RetailSalesAnalytics.ipynb` and choose **Run All**.

## Key analysis
- Data types, missing values, duplicates and range checks.
- Revenue, profit, units sold and profit margin KPIs.
- Product and regional comparisons.
- Monthly revenue trend.
- Time-ordered model test split with MAE, RMSE and R-squared.

## Important interpretation
Model metrics describe performance on generated data only. Before using this approach in a business, replace the synthetic data with an authorized dataset, compare against a simple baseline, and validate model performance over time.

## Author
Abhishek

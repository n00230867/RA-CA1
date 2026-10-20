# CA1 - Data Analytics for Business

## Scenario

Marketing Director. The student ID and assigned scenario are recorded in `data/Scenario.txt`.

## Project layout

```text
data/       Assigned CSV datasets and scenario
tasks/      Task 1 and Task 2 analysis notebooks/scripts
reports/    Student-written report material for Tasks 3 and 4
```

## Dataset map

- `Retail_regions.csv`: store, marketing, operational and sales performance data for Task 1.
- `Customers_repeat.csv`: customer demographics, region, loyalty and membership data for Task 2.
- `Products_sort.csv`: product category, brand, price, rating and popularity data for Task 2.
- `Transactions_made.csv`: customer-product purchases, recency and spend for Task 2.

## Setup

From PowerShell at the repository root:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
python -m notebook
```

In VS Code, select `.venv\Scripts\python.exe` as the Python interpreter and open the `tasks` folder for your analysis work.

## Analysis checklist

### Task 1 - Retail Performance Analytics

- Inspect data types, missing values, duplicates and outliers.
- Create at least three meaningful engineered features.
- Complete four grouped analyses and two pivot tables.
- Investigate correlations with `SalesRevenue`.
- Compare at least one predictive model using a train/test split and MAE, RMSE and R-squared.
- Produce at least three labelled visualisations.

### Task 2 - Recommendation System

- Validate and integrate the customer, product and transaction tables.
- Build a customer-product interaction matrix.
- Analyse high-value customers and product performance.
- Complete at least three grouped analyses and two pivot tables.
- Implement a popularity-based recommender and one additional approach.
- Evaluate both approaches and test recommendations for at least five customers.

## Academic integrity boundary

The brief permits AI assistance for code development in Tasks 1 and 2 only. Write Tasks 3 and 4 yourself, including business recommendations, the AI process log and reflection. Keep your own prompts, validation evidence and development history for the required submission.
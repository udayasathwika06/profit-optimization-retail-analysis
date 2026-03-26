# profit-optimization-retail-analysis

# 🛍️ Retail Business Performance & Profitability Analysis

## 📌 Objective
To analyze transactional retail data and uncover:
- Profit-draining product categories
- Inventory turnover inefficiencies
- Seasonal trends in product performance

## 🧰 Tools Used
- **SQL**: Data cleaning, profit margin computation
- **Python (Pandas, Seaborn)**: Correlation analysis and data exploration
- **Tableau**: Interactive dashboard with filters for region, product type, and season

## 📂 Dataset
- `retail_transaction_data.csv`: Contains transactional records with product, region, and profitability details

## 🧪 Steps Performed

### 1. Data Preparation in SQL
- Imported the dataset into SQL
- Cleaned missing/null records  
- Created table: `retail_transactions`
- Ran SQL queries to calculate:
  - Profit Margin by **Category**
  - Profit Margin by **Sub-Category**

### 2. Python-Based Analysis
- Analyzed correlation between **Inventory_Days** and **Profitability**
- Visualized patterns and relationships using **Seaborn**

### 3. Tableau Dashboard
- Built a dashboard showing:
  - Profitability by category, region, and season
  - Filters for Region, Product Category/Sub-Category, Season
- Enabled interactive filtering and strategic KPI insights

### 4. Strategic Recommendations
- Identified slow-moving & overstocked items
- Suggested:
  - Focused discounting
  - Optimized inventory & supply chain handling
  - Seasonal bundling strategies

## 📁 Project Files

| File Name                                  | Description                                   |
|--------------------------------------------|-----------------------------------------------|
| `retail_transaction_data.csv`              | Raw transactional data                        |
| `sql_queries.sql`                          | SQL queries for cleaning and analysis         |
| `Python_Based_Insights.ipynb`              | Python notebook for correlation analysis      |
| `Dashboard.twbx`                           | Tableau interactive dashboard                 |
| `Retail_Performance_Analysis_Report.pdf`   | Final PDF report with executive summary       |

## 📈 Key Insights
- Some sub-categories consistently deliver low margins regardless of season.
- High inventory days often correlate with low profitability.
- Certain regions underperform seasonally despite volume, needing targeted campaigns.

---

✅ This project provides a strong foundation for retail decision-makers to act on data-backed insights for profit optimization.


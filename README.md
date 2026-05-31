# 🛒 UK Retail Sales Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

## 📌 Overview

An exploratory data analysis (EDA) of a real UK-based online retailer's transactional data (2010–2011), sourced from the UCI Machine Learning Repository.

The analysis uncovers sales trends, top products, customer behaviour, and actionable business insights.

---

## 🔍 Key Questions Answered

- What are the monthly and seasonal sales trends?
- Which products generate the most revenue?
- Which countries contribute the most to sales?
- Who are the top customers by spend?
- When do customers buy (day of week, hour of day)?

---

## 📊 Key Insights

| # | Insight |
|---|---|
| 1 | Revenue **peaks in Q4 (Oct–Nov)**, indicating strong seasonal demand |
| 2 | A **small number of products** drive the majority of revenue (Pareto principle) |
| 3 | The **United Kingdom** is the dominant market by a large margin |
| 4 | **Top 10 customers** contribute significantly to total revenue |
| 5 | **Thursday** is the busiest sales day — typical B2B behaviour |
| 6 | **10am–3pm** are peak purchasing hours |

---

## 🛠️ Tools & Libraries

| Tool | Purpose |
|---|---|
| Python 3 | Core programming language |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualisation |
| Seaborn | Statistical plots |
| Jupyter Notebook | Interactive analysis environment |

---

## 📁 Project Structure

```
uk-retail-sales-analysis/
│
├── uk_retail_sales_analysis.ipynb   # Main analysis notebook
├── Online_Retail.xlsx               # Dataset (download separately)
├── monthly_revenue.png              # Monthly revenue trend chart
├── top_products.png                 # Top products bar chart
├── top_countries.png                # Top countries bar chart
├── top_customers.png                # Top customers bar chart
├── day_of_week.png                  # Sales by day of week
├── hour_of_day.png                  # Sales by hour of day
└── README.md
```

---

## 🚀 How to Run

1. Clone this repository:
```bash
git clone https://github.com/ranveen_8/uk-retail-sales-analysis.git
cd uk-retail-sales-analysis
```

2. Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn openpyxl jupyter
```

3. Download the dataset from [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/online+retail) and save as `Online_Retail.xlsx` in the project folder.

4. Launch the notebook:
```bash
jupyter notebook uk_retail_sales_analysis.ipynb
```

---

## 📦 Dataset

- **Source:** [UCI Machine Learning Repository – Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/online+retail)
- **Records:** ~541,000 transactions
- **Period:** December 2010 – December 2011
- **Region:** United Kingdom (+ international customers)

---

## 🚀 Future Work

- RFM Analysis (Recency, Frequency, Monetary) for customer segmentation
- Cohort analysis to track customer retention over time
- Market Basket Analysis using association rules
- Revenue forecasting using time series models

---

## 👩‍💻 Author

**Raveena Somasundaram**  
MSc Data Science, University of Surrey  
🔗 [LinkedIn](https://www.linkedin.com/in/raveena-somasundaram-9439b6205/)

# 📊 Loan Data Analysis Project

## 📌 Overview  
This project focuses on analyzing **loan application data** to uncover trends, patterns, and insights.  
The analysis is based on various loan-related attributes such as:  

- `issue_date`  
- `loan_amount`  
- `int_rate`  
- `dti`  
- `loan_status`  
- and more...  

### 🎯 The Goal is to:
- Track monthly loan applications  
- Measure total funded loan amounts per month  
- Visualize average interest rate vs average debt-to-income ratio  
- Explore regional loan distributions by state  
- Highlight monthly trends using line/area charts  

---

## 🛠️ Tools & Technologies  
- **Python 🐍**  
- **Pandas** → Data cleaning, aggregation, and feature extraction  
- **Matplotlib** → Visualizations (line charts, bar charts, pie/donut charts)  
- **Seaborn** → Advanced and aesthetic statistical plots  

---

## 📈 Key Visualizations  
- 📊 **Monthly Loan Applications** (bar chart + MTD tracking)  
- 📈 **Monthly Funded Amounts** (line/area charts)  
- 📉 **Average Interest Rate vs DTI** (comparison curve)  
- 🥧 **Regional Loan Distribution** (pie chart / donut chart with customization)  
- 🔍 **Keyword Search in Data** (string exploration across all columns)  

---

## 🚀 Features Implemented  
- Extracting **month** from `issue_date` to group loans over time  
- Calculating **total loan applications** per month  
- Computing **funded loan amounts** per month (in millions)  
- Comparing **financial ratios** (interest rate vs DTI)  
- Generating **regional state-wise funded loan shares**  
- Applying **custom color palettes** (blue, green, teal) for consistency  
- Adding **labels and annotations** directly on plots for clarity  

---

## 📂 Project Structure  

```bash
├── data/               # Loan dataset (CSV/Excel format)  
├── notebooks/          # Jupyter/Colab notebooks with code & analysis  
├── plots/              # Saved visualizations (PNG/JPEG)  
├── requirements.txt    # Dependencies  
└── README.md           # Project documentation  

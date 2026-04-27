# 🏡 Real Estate Analyzer: Undervalued Micro-Markets Detection

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Machine%20Learning-KMeans-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Data%20Analysis-Pandas-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">
</p>

---

## 📌 Overview
This project identifies **undervalued micro-markets** in real estate using **data analysis, statistical validation, and machine learning**.

By analyzing property listings, we detect locations where pricing is inefficient — helping uncover **hidden investment opportunities**.

---

## 🎯 Problem Statement
Develop a system to identify **undervalued locations** by analyzing real estate listings and detecting areas with lower **price per square foot** compared to similar properties.

---

## 🚀 Features
- 📊 Data Extraction & Cleaning (ETL Pipeline)
- 📈 Exploratory Data Analysis (EDA)
- 📉 Statistical Testing (Hypothesis Testing)
- 🤖 Machine Learning (K-Means Clustering)
- 📍 Location-Based Market Segmentation
- 💡 Undervalued Market Detection

---

## 🧠 Core Concept

### 💰 Price per Sq Ft (Key KPI)
Used to normalize pricing across properties of different sizes, allowing for fair comparison.

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook
- Tableau

---

## 📂 Project Structure
```
📦 Egypt-RealEstateAnalyzer/
├── notebooks/
│   ├── 01_extraction.ipynb         # Data Extraction
│   ├── 02_cleaning.ipynb           # Data Cleaning & Preprocessing
│   ├── 03_eda.ipynb                # Exploratory Data Analysis
│   ├── 04_statistical_analysis.ipynb # Hypothesis Testing
│   └── 05_final_load_prep.ipynb    # Feature Engineering + ML Clustering
├── data/
│   ├── listings.csv
│   └── past_rates.csv
├── reports/
│   ├── project_report.pdf
│   └── analysis_report.md
└── README.md
```

---

## 🔍 EDA Insights
Key findings from analysis:
- Property prices are **right-skewed** (most properties are affordable, few are expensive).
- Strong **positive correlation** between property area and price.
- Significant price variations exist across different locations.
- Premium listings tend to command higher prices.

---

## 📊 Statistical Validation
- **Hypothesis Tested**: Do premium properties command significantly higher prices?
- **Method**: Independent samples t-test
- **Result**: **P-value < 0.05** — Premium properties are statistically significantly more expensive.

---

## 🤖 Machine Learning

### Technique: **K-Means Clustering**
Used to segment properties into distinct **micro-markets** based on features like price, area, and location.

### Steps:
1. **Feature Engineering**: Created `price_per_sqft`
2. **Feature Scaling**: StandardScaler applied
3. **Clustering**: Grouped properties into 4 micro-markets
4. **Analysis**: Identified clusters with lowest pricing (undervalued markets)

---

## 💡 Investment Insights
- Identified specific micro-markets where price per sq ft is significantly lower
- These markets represent **high-potential investment opportunities**
- Premium vs non-premium analysis shows clear market segmentation
- Data-driven approach enables smarter investment decisions

---

## 🔮 Future Scope
- Real-time API integration for live pricing data
- Rental yield prediction models
- Price appreciation forecasting
- NLP on property descriptions
- Advanced clustering algorithms

---

## 👨‍💻 Author
**Vivek Kumar Raj**

---

## ⭐ If you like this project
Feel free to give it a star ⭐


---

### 🔗 Useful Links
- [GitHub Repository](https://github.com/viveeeeek13/SectionE_G-5_Egypt-RealEstateAnalyzer)
- [Tableau Public Dashboard](link-to-dashboard-here)

---

**Happy Analyzing! 📊**
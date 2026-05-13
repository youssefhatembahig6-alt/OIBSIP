# 📊 Unemployment Analysis with Python — OIBSIP Task 2

**Author:** Youssef Hatem Mohamed Bahig  
**GitHub:** [@youssefhatembahig6-alt](https://github.com/youssefhatembahig6-alt)  
**Internship:** AICTE Oasis Infobyte Internship Program  

---

## 📌 Objective

Analyze the unemployment rate in India — especially the sharp increase during **Covid-19** — using data science and visualization techniques.

> **Unemployment Rate** = Number of unemployed people as a percentage of the total labour force.

---

## 📂 Project Structure

```
OIBSIP/
└── Task2_UnemploymentAnalysis/
    ├── Unemployment_Analysis.ipynb           # Main notebook
    ├── Unemployment_Rate_upto_11_2020.csv    # Dataset
    └── README.md                             # Documentation
```

---

## 📊 Dataset

- **Source:** [Kaggle — Unemployment in India](https://www.kaggle.com/datasets/gokulrajkmv/unemployment-in-india)
- **Features:**

| Feature | Description |
|---|---|
| Region | Indian state/region |
| Date | Month of record |
| Frequency | Monthly |
| Estimated Unemployment Rate (%) | Target variable |
| Estimated Employed | Number of employed people |
| Estimated Labour Participation Rate (%) | Labour participation |
| Area | Rural / Urban |

---

## ⚙️ Environment & Installation

- **Python:** 3.11.15
- **Environment:** `myenv`

```bash
pip install pandas numpy matplotlib seaborn plotly
```

---

## 📓 How to Run

```bash
source ~/myenv/bin/activate
jupyter notebook
```
Then open `Unemployment_Analysis.ipynb` and click **Run All**

---

## 📈 Notebook Steps

1. Import Libraries
2. Load Dataset
3. Exploratory Data Analysis (EDA)
4. Unemployment Rate Over Time
5. Unemployment by Region
6. Rural vs Urban Comparison
7. Covid-19 Impact Analysis
8. Heatmap by Region & Month
9. Labour Participation Rate Analysis
10. Top 5 Most & Least Affected Regions
11. Correlation Analysis
12. Final Summary & Key Insights

---

## 🔍 Key Findings

- Unemployment rate **sharply increased** during Covid-19 lockdown (March–June 2020)
- **Urban areas** were more severely impacted than rural areas
- Significant variation in unemployment rates across different Indian regions
- Labour participation rate **dropped** as unemployment rose during Covid-19

---

## 📤 Submission

- **GitHub Repo:** [OIBSIP](https://github.com/youssefhatembahig6-alt/OIBSIP)
- **Submitted via:** [Official Form](https://forms.gle/GXLNLfbCTkhBhB4K6)

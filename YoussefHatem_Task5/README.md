# 💰 Sales Prediction Using Python — OIBSIP Task 5

**Author:** Youssef Hatem Mohamed Bahig  
**GitHub:** [@youssefhatembahig6-alt](https://github.com/youssefhatembahig6-alt)  
**Internship:** AICTE Oasis Infobyte Internship Program  

---

## 📌 Objective

Build a machine learning model that predicts how much of a product people will buy based on advertising spend across different platforms:
- 📺 **TV** Advertising Budget
- 📻 **Radio** Advertising Budget
- 📰 **Newspaper** Advertising Budget

---

## 📂 Project Structure

```
OIBSIP/
└── Task5_SalesPrediction/
    ├── Sales_Prediction.ipynb   # Main notebook
    ├── advertising.csv          # Dataset
    └── README.md                # Documentation
```

---

## 📊 Dataset

- **Source:** [Advertising Dataset – Kaggle](https://www.kaggle.com/datasets/bumba5341/advertisingcsv)
- **Rows:** 200 samples
- **Features:**

| Feature | Description |
|---|---|
| TV | Advertising budget spent on TV ($000s) |
| Radio | Advertising budget spent on Radio ($000s) |
| Newspaper | Advertising budget spent on Newspaper ($000s) |
| Sales | Units sold (Target variable) |

---

## ⚙️ Environment & Installation

- **Python:** 3.11.15
- **Environment:** `myenv` (Virtual Environment)

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 📓 How to Run

```bash
source ~/myenv/bin/activate
jupyter notebook
```
Then open `Sales_Prediction.ipynb` and click **Run All**

---

## 🤖 Models Used & Results

| Model | R² Score |
|---|---|
| Linear Regression | ~90% |
| Ridge Regression | ~90% |
| Decision Tree | ~94% |
| Random Forest | ~98% |

---

## 📈 Notebook Steps

1. Import Libraries  
2. Load Dataset  
3. Exploratory Data Analysis (EDA)  
4. Visualizations (Pair Plot, Heatmap, Distributions, Budget Breakdown)  
5. Preprocessing (Feature Scaling + Train/Test Split)  
6. Train & Evaluate 4 Models  
7. Model R² Score Comparison Chart  
8. Actual vs Predicted Plot (Best Model)  
9. Predict a New Sample  
10. Final Summary  

---

## 🔍 Key Findings

- TV advertising has the strongest correlation with sales
- Radio is the second most influential channel
- Newspaper spend has minimal impact on sales
- Random Forest achieves the highest predictive accuracy

---

## 📤 Submission

- **GitHub Repo:** [OIBSIP](https://github.com/youssefhatembahig6-alt/OIBSIP)
- **Submitted via:** [Official Form](https://forms.gle/GXLNLfbCTkhBhB4K6)

# 🚗 Car Price Prediction with Machine Learning — OIBSIP Task 3

**Author:** Youssef Hatem Mohamed Bahig  
**GitHub:** [@youssefhatembahig6-alt](https://github.com/youssefhatembahig6-alt)  
**Internship:** AICTE Oasis Infobyte Internship Program  

---

## 📌 Objective

Train a machine learning model that learns from used car listings and predicts the **selling price** of a car based on its attributes such as present market price, kilometres driven, fuel type, transmission type, and age.

---

## 📂 Project Structure

```
OIBSIP/
└── Task3_CarPricePrediction/
    ├── Task3_CarPricePrediction.ipynb   # Main notebook
    ├── car data.csv                     # Dataset
    └── README.md                        # Documentation
```

---

## 📊 Dataset

- **Source:** [Kaggle — Car Price Prediction (Used Cars)](https://www.kaggle.com/datasets/vijayaadithyanvg/car-price-predictionused-cars)
- **Rows:** 301 samples
- **Features:**

| Feature | Description |
|---|---|
| Car_Name | Name / model of the car |
| Year | Year of manufacture |
| Selling_Price | Price the owner wants to sell at (Lakhs) ← **Target** |
| Present_Price | Current ex-showroom price (Lakhs) |
| Kms_Driven | Total kilometres driven |
| Fuel_Type | Petrol / Diesel / CNG |
| Seller_Type | Dealer / Individual |
| Transmission | Manual / Automatic |
| Owner | Number of previous owners |

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
Then open `Task3_CarPricePrediction.ipynb` and click **Run All**

---

## 🤖 Models Used & Results

| Model | R² Score |
|---|---|
| Random Forest | ~0.96 |
| Gradient Boosting | ~0.95 |
| Decision Tree | ~0.89 |
| Ridge Regression | ~0.84 |
| Linear Regression | ~0.83 |
| Lasso Regression | ~0.82 |

---

## 📈 Notebook Steps

1. Import Libraries  
2. Load Dataset  
3. Explore the Dataset (shape, info, describe, missing values)  
4. Exploratory Data Analysis (EDA)  
5. Feature Engineering & Preprocessing (Car_Age, Label Encoding, Train/Test Split)  
6. Model Building & Training (6 models)  
7. Model Evaluation (R², MAE, RMSE)  
8. Predict on New Input  
9. Conclusion  

---

## 🔍 Key Findings

- **Present Price** is the strongest predictor of resale value
- **Car Age** is the second most influential feature — newer cars retain more value
- **Automatic** cars command significantly higher resale prices than Manual
- **Diesel** cars have higher resale value compared to Petrol or CNG
- **Random Forest** outperformed all other models with R² ≈ 0.96

---

## 📤 Submission

- **GitHub Repo:** [OIBSIP](https://github.com/youssefhatembahig6-alt/OIBSIP)
- **Submitted via:** [Official Form](https://forms.gle/GXLNLfbCTkhBhB4K6)
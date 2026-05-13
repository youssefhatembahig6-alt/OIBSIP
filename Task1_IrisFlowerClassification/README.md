# 🌸 Iris Flower Classification — OIBSIP Task 1

**Author:** Youssef Hatem Mohamed Bahig  
**GitHub:** [@youssefhatembahig6-alt](https://github.com/youssefhatembahig6-alt)  
**Internship:** AICTE Oasis Infobyte Internship Program  

---

## 📌 Objective

Train a machine learning model that learns from iris flower measurements and classifies them into one of three species:
- 🌸 **Setosa**
- 🌺 **Versicolor**
- 🌼 **Virginica**

---

## 📂 Project Structure

```
OIBSIP/
└── Task1_IrisFlowerClassification/
    ├── Iris_Classification.ipynb   # Main notebook
    ├── Iris.csv                    # Dataset
    └── README.md                   # Documentation
```

---

## 📊 Dataset

- **Source:** [IRIS.csv](https://raw.githubusercontent.com/amankharwal/Website-data/master/IRIS.csv)
- **Rows:** 150 samples (50 per species)
- **Features:**

| Feature | Description |
|---|---|
| sepal_length | Length of the sepal (cm) |
| sepal_width | Width of the sepal (cm) |
| petal_length | Length of the petal (cm) |
| petal_width | Width of the petal (cm) |
| species | Target label |

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
Then open `Iris_Classification.ipynb` and click **Run All**

---

## 🤖 Models Used & Results

| Model | Accuracy |
|---|---|
| Logistic Regression | ~97% |
| Decision Tree | ~93% |
| Random Forest | ~90% |
| Support Vector Machine (SVM) | ~97% |

---

## 📈 Notebook Steps

1. Import Libraries  
2. Load Dataset  
3. Exploratory Data Analysis (EDA)  
4. Visualizations (Pair Plot, Heatmap, Boxplots)  
5. Preprocessing (Label Encoding + Train/Test Split)  
6. Train & Evaluate 4 Models  
7. Model Accuracy Comparison Chart  
8. Confusion Matrix (Best Model)  
9. Predict a New Sample  
10. Final Summary  

---

## 🔍 Key Findings

- Petal length and petal width are the most important features
- Setosa is perfectly separable from the other two species
- Random Forest and SVM achieve 100% accuracy on the test set

---

## 📤 Submission

- **GitHub Repo:** [OIBSIP](https://github.com/youssefhatembahig6-alt/OIBSIP)
- **Submitted via:** [Official Form](https://forms.gle/GXLNLfbCTkhBhB4K6)

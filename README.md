# 🌸 Iris Flower Classification — OIBSIP Task 1

**Author:** Youssef Hatem Mohamed Bahig  
**Internship:** AICTE Oasis Infobyte Internship Program  
**Task:** Iris Flower Classification using Machine Learning

---

## 📌 Objective

Train a machine learning model that learns from iris flower measurements and classifies them into one of three species:
- **Setosa**
- **Versicolor**
- **Virginica**

---

## 📂 Project Structure

```
Task1_IrisFlowerClassification/
├── iris_classification.py   # Main ML script
├── iris.csv                 # Dataset (optional local copy)
├── pairplot.png             # Pair plot visualization
├── heatmap.png              # Correlation heatmap
├── boxplots.png             # Feature boxplots
├── model_comparison.png     # Accuracy bar chart
├── confusion_matrix.png     # Best model confusion matrix
└── README.md                # Project documentation
```

---

## 📊 Dataset

- **Source:** [IRIS.csv](https://raw.githubusercontent.com/amankharwal/Website-data/master/IRIS.csv)
- **Rows:** 150 samples (50 per species)
- **Features:**
  | Feature | Description |
  |---|---|
  | sepal_length | Length of the sepal (cm) |
  | sepal_width  | Width of the sepal (cm) |
  | petal_length | Length of the petal (cm) |
  | petal_width  | Width of the petal (cm) |
  | species      | Target label (setosa / versicolor / virginica) |

---

## ⚙️ Installation

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## ▶️ How to Run

```bash
python iris_classification.py
```

---

## 🤖 Models Used

| Model | Description |
|---|---|
| Logistic Regression | Linear probabilistic classifier |
| Decision Tree | Rule-based tree classifier |
| Random Forest | Ensemble of decision trees |
| SVM (RBF kernel) | Margin-based classifier |

---

## 📈 Results

All four models achieve high accuracy (95–100%) on this dataset.  
The **Random Forest** and **SVM** models typically reach **100% accuracy** on the test set.

---

## 🔍 Key Findings

- Petal length and petal width are the most discriminating features
- Setosa is perfectly separable from the other two species
- Versicolor and Virginica have some overlap in sepal measurements

---

## 📤 Submission

- GitHub Repo: `OIBSIP`
- File name: `YourName_Task1`
- Submitted via: [Official Form](https://forms.gle/GXLNLfbCTkhBhB4K6)

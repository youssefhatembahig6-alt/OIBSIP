# 📧 Email Spam Detection with Machine Learning — OIBSIP Task 4

**Author:** Youssef Hatem Mohamed Bahig  
**GitHub:** [@youssefhatembahig6-alt](https://github.com/youssefhatembahig6-alt)  
**Internship:** AICTE Oasis Infobyte Internship Program  

---

## 📌 Objective

Build a machine learning model that learns from SMS/email text messages and classifies them as:
- ✅ **Ham** (Legitimate message)
- 🚫 **Spam** (Junk / unwanted message)

---

## 📂 Project Structure

```
OIBSIP/
└── Task4_EmailSpamDetection/
    ├── SMS_Spam_Detection.ipynb   # Main notebook
    ├── spam.csv                   # Dataset
    └── README.md                  # Documentation
```

---

## 📊 Dataset

- **Source:** [SMS Spam Collection Dataset – Kaggle](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- **Rows:** 5,572 messages
- **Features:**

| Feature | Description |
|---|---|
| label | Target label: `ham` or `spam` |
| message | Raw text content of the SMS/email |

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
Then open `SMS_Spam_Detection.ipynb` and click **Run All**

---

## 🤖 Models Used & Results

| Model | Accuracy |
|---|---|
| Logistic Regression | ~98% |
| Decision Tree | ~97% |
| Random Forest | ~97% |
| Naive Bayes | ~98% |

---

## 📈 Notebook Steps

1. Import Libraries  
2. Load Dataset  
3. Exploratory Data Analysis (EDA)  
4. Visualizations (Count Plot, Length Distribution, Boxplots)  
5. Preprocessing (Text Cleaning + TF-IDF Vectorization + Train/Test Split)  
6. Train & Evaluate 4 Models  
7. Model Accuracy Comparison Chart  
8. Confusion Matrix (Best Model)  
9. Predict a New Message  
10. Final Summary  

---

## 🔍 Key Findings

- Spam messages are significantly longer than ham messages on average
- TF-IDF effectively captures discriminative word patterns between spam and ham
- Naive Bayes and Logistic Regression both perform exceptionally well on text classification

---

## 📤 Submission

- **GitHub Repo:** [OIBSIP](https://github.com/youssefhatembahig6-alt/OIBSIP)
- **Submitted via:** [Official Form](https://forms.gle/GXLNLfbCTkhBhB4K6)

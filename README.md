# 🧠 Visa Approval Prediction using Machine Learning  

### 📊 Predicting visa application outcomes using multiple ML algorithms  

---

## 🧾 Overview  

This project applies **supervised machine learning techniques** to predict visa approval outcomes using the **Easy Visa dataset**.  
The process involves **data preprocessing**, **feature engineering**, **model development**, and **comparative evaluation** of various classification algorithms — including **Decision Tree**, **Random Forest**, **Gradient Boosting**, **AdaBoost**, and **Bagging**.  

---

## 🎯 Objectives  

- 🔍 Understand and explore the Easy Visa dataset  
- 🧹 Perform data cleaning, encoding, and feature selection  
- 🤖 Train and evaluate multiple ML classification models  
- 📈 Compare results using Accuracy, Precision, Recall, and F1-Score  
- 🏆 Identify the most reliable and interpretable model  
- 💡 Deliver a transparent, reproducible ML workflow 

---

## 🧩 Dataset  

- **Source:** EasyVisa (synthetic dataset for educational use)  
- **Features:** Education, Job Experience, Wages, Employment Region, Job Training Requirements, etc.  
- **Target:** `case_status` — Visa Approved (1) or Denied (0)  

---
## ⚙️ Project Workflow  
```

Visa_Approval_Prediction/
├── Data/
│ └── easyvisa.csv
├── Source_Code/
│ └── Visa_approval.ipynb
├── Results/
│ ├── confusion_matrix.png
│ ├── classification_report.txt
│ └── model_summary.txt
├── Documentation/
│ └── Project_Report.pdf
├── requirements.txt
├── .gitignore
└── README.md
```
---

## 🤖 Machine Learning Models  

This project compared multiple ensemble learning algorithms — both **Boosting** and **Bagging** — to identify the most effective method for predicting visa approval outcomes.  

Boosting techniques (AdaBoost and Gradient Boosting) showed stronger generalization and recall compared to Bagging-based models.

| Model | Accuracy | Precision | Recall | F1-Score |
|-------|-----------|------------|----------|-----------|
| **AdaBoost** | **0.7206** | **0.7495** | **0.8737** | **0.8068** |
| **Gradient Boosting** | **0.7369** | **0.7669** | **0.8707** | **0.8155** |
| **Bagging Classifier** | **0.7121** | **0.7633** | **0.8249** | **0.7929** |
| **Random Forest** | **0.7190** | **0.7676** | **0.8308** | **0.7980** |

✅ **Best Model:** Gradient Boosting  
💡 Demonstrated the highest F1-Score (0.8155) and recall, indicating superior overall balance and predictive performance.

---


## ⚙️ Setup and Execution  

### Step 1: Create a Virtual Environment  

```
python -m venv venv
venv\Scripts\activate

```

### Step 2: Install Dependencies  

```
 pip install -r requirements.txt

```

### Step 3: Launch Jupyter Notebook  

```
jupyter notebook

```

### Step 4: Run the Notebook  
```
Open `Source_Code/Visa_approval.ipynb` and execute all cells in order.

```

## 📊 Results and Insights  

The project evaluated multiple ensemble machine learning models under two major categories **Boosting** and **Bagging** to predict visa approval outcomes using applicant and job-related data.

| Model | Accuracy | Precision | Recall | F1-Score |
|-------|-----------|------------|----------|-----------|
| **AdaBoost** | **0.7206** | **0.7495** | **0.8737** | **0.8068** |
| **Gradient Boosting** | **0.7369** | **0.7669** | **0.8707** | **0.8155** |
| **Bagging Classifier** | **0.7121** | **0.7633** | **0.8249** | **0.7929** |
| **Random Forest** | **0.7190** | **0.7676** | **0.8308** | **0.7980** |

✅ **Best Model:** Gradient Boosting  
💡 Achieved the highest **F1-Score (0.8155)** and strong **recall (0.8707)**, indicating excellent balance between correctly identifying approved visa cases and maintaining high precision.

---

### 🔍 Key Insights  

- **Boosting models** (AdaBoost, Gradient Boosting) outperformed **Bagging methods** (Bagging Classifier, Random Forest) across most metrics.  
- **Gradient Boosting** demonstrated superior performance due to its sequential learning approach, which reduces bias and improves generalization.  
- **High recall values** show that the model effectively minimizes false negatives — an important factor when identifying eligible visa approvals.  
- **Random Forest** and **Bagging Classifier** also achieved competitive performance, confirming that ensemble techniques outperform simple decision trees.  

---

### 💡 Business Interpretation  

The results suggest that visa approvals are **most strongly influenced by factors** such as:  
- Education level and work experience of the applicant  
- Employment region and company size  
- Prevailing wage and full-time job status  

The **Gradient Boosting model** serves as an ideal decision-support tool for organizations like EasyVisa to predict visa outcomes more **accurately, fairly, and efficiently.**

---

## 👩‍💻 Author  

**Name:** Hasnath Unnisa  
**Email:** unnisahasnath@gmail.com  
**LinkedIn:** www.linkedin.com/in/hasnath22  





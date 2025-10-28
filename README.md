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

| Model | Accuracy | Precision | Recall | F1-score |
|-------|-----------|------------|----------|-----------|
| Decision Tree | 70.1% | 0.68 | 0.71 | 0.69 |
| Random Forest | 74.5% | 0.73 | 0.76 | 0.74 |
| AdaBoost | 73.2% | 0.71 | 0.74 | 0.73 |
| Bagging | 75.0% | 0.74 | 0.75 | 0.74 |
| **Gradient Boosting** | **76.3%** | **0.76** | **0.78** | **0.77** |

✅ **Best Model:** Gradient Boosting  
💡 Provides an excellent balance between interpretability and predictive performance.  

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

- **Best Performing Model:** Gradient Boosting  
- **Accuracy:** 76.3%  
- **Precision:** 0.76  
- **Recall:** 0.78  
- **F1-Score:** 0.77  

### 🔍 Key Observations  

- Gradient Boosting achieved the highest performance among all tested models.  
- The model maintained a **strong recall**, meaning it successfully identified most approved applications.  
- The **feature importance analysis** showed that the following factors most influenced visa approvals:  

  - Education level of the employee  
  - Years of job experience  
  - Region of employment  
  - Prevailing wage  

### 💡 Business Insight  

Visa approvals are **more likely** for candidates with: 
 
- Higher education qualifications  
- More work experience  
- Employment in high-demand regions  
- Competitive wage offers  

This model can help organizations **prioritize and evaluate visa applications** more effectively, ensuring fairness and efficiency.


## 👩‍💻 Author  

**Name:** Hasnath Unnisa  
**Email:** unnisahasnath@gmail.com  
**LinkedIn:** www.linkedin.com/in/hasnath22  





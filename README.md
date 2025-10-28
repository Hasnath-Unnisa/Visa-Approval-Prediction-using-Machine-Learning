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

### 1️⃣ Create a virtual environment  
```bash
python -m venv venv
venv\Scripts\activate

2️⃣ Install dependencies

pip install -r requirements.txt

3️⃣ Launch Jupyter Notebook

jupyter notebook

4️⃣ Open and execute the notebook

Navigate to Source_Code/Visa_approval.ipynb and run all cells sequentially.

📊 Results and Insights

Gradient Boosting achieved the best accuracy (76.3%) and stable recall scores.

Major factors influencing visa approval:

Education level of employee

Years of job experience

Region of employment

Prevailing wage

📈 The model enables smarter, fairer, and faster visa application analysis.

🧪 Reproducibility

To reproduce results:

Clone or download the repository

Follow the setup instructions

Run the Jupyter Notebook end-to-end

🚀 Future Enhancements

Integrate advanced algorithms like XGBoost and LightGBM

Develop a Streamlit/Flask web interface for interactive predictions

Add explainability features (SHAP, LIME) for decision transparency

Author :Hasnath Unnisa
Email : unnisahasnath@gmail.com
Linkedin: www.linkedin.com/in/hasnath22




# 🧠 Visa Approval Prediction using Machine Learning

### 📊 Predicting visa application outcomes using multiple ML algorithms  

---

## 🧾 Abstract  

This project applies **supervised machine learning techniques** to predict visa approval outcomes using the **Easy Visa dataset**.  
The process involves **data preprocessing**, **feature engineering**, **model development**, and **comparative evaluation** of various classification algorithms — including **Decision Tree**, **Random Forest**, **Gradient Boosting**, **AdaBoost**, and **Bagging**.  

The final results identify **Gradient Boosting** as the most accurate and business-aligned model, offering actionable insights for scaling smarter, fairer visa processing decisions.  

---

## 🎯 Objectives  

- 🔍 Understand and explore the Easy Visa dataset  
- 🧹 Perform data cleaning, encoding, and feature selection  
- 🤖 Train and evaluate multiple ML classification models  
- 📈 Compare results using Accuracy, Precision, Recall, and F1-Score  
- 🏆 Identify the most reliable and interpretable model  
- 💡 Deliver a transparent, reproducible ML workflow  

---

## 🗂️ Project Structure  

Visa_Approval_Prediction_using_Machine_Learning/
├── README.md
├── Source_Code/
│ └── Visa_approval.ipynb
├── Data/
│ └── easyvisa.csv
├── Results/
│ ├── confusion_matrix.png
│ ├── classification_report.txt
│ ├── model_performance.txt
│ └── gradient_boosting_model.pkl
├── Documentation/
│ └── Project_Report.pdf
├── requirements.txt
└── .gitignore


---

## ⚙️ Setup Instructions  

1️⃣ **Create and activate a virtual environment:**  
```bash
python -m venv venv
venv\Scripts\activate

2️⃣ Install dependencies:

pip install -r requirements.txt

3️⃣ Launch Jupyter Notebook:

jupyter lab

4️⃣ Run all cells in:

Source_Code/Visa_approval.ipynb

🧩 Dataset

The project uses the Easy Visa dataset, containing attributes such as education, experience, employment region, and wage details.
If the full dataset includes sensitive information, do not upload it publicly — instead:

Include a small anonymized file named sample_easyvisa.csv inside the Data/ folder, or

Add a short README.md in Data/ explaining how to obtain it.

📊 Results

The notebook provides:

🔹 Model comparison across multiple classifiers

🔹 Confusion matrix and classification report visualizations

🔹 Identification of the best performing model (Gradient Boosting)

🔹 Insights for optimizing decision workflows

Final Model Summary:

✅ Algorithm: Gradient Boosting

📈 Accuracy: 76.3%

🧠 Key Strength: Balances interpretability and predictive performance

🧪 Reproducibility

Every step — from preprocessing to model evaluation — is contained in the Jupyter Notebook.
Follow the setup guide and execute cells sequentially to reproduce identical results.

👩‍💻 Author : Hasnath Unnisa
📧 Email : unnisahasnath@gmail.com

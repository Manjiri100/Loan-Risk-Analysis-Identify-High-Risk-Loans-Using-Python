# 💰 Loan Risk Analysis Project

This project performs **Loan Risk Analysis** using a sample loan dataset. The goal is to identify **high-risk loans** based on financial and demographic data, and provide insights for smarter decision-making. 📊

---

## 🚀 Project Overview

- **🎯 Objective:** Analyze loan applications to determine potential risk and provide actionable insights  
- **📂 Type:** Data Analysis / Rule-based Risk Scoring  
- **📄 Dataset:** `Loan_Risk_Data.csv` (columns include Loan_ID, Gender, Married, Dependents, Education, Self_Employed, ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term, Credit_History, Property_Area, Loan_Status)  
- **🛠 Tools & Libraries:** Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

---

## 📝 Project Steps

1. **🔹 Data Loading & Inspection**  
   - Loaded the CSV file and inspected dataset structure.  
2. **🔹 Data Cleaning**  
   - Checked for missing values and duplicates (none in this dataset).  
3. **🔹 Exploratory Data Analysis (EDA)**  
   - Visualized distributions of Loan Status, Credit History, Applicant Income vs Loan Amount, Property Area, etc.  
4. **🔹 Feature Engineering & Risk Scoring**  
   - Created `TotalIncome` feature.  
   - Applied **rule-based scoring**: loans with bad credit history or high LoanAmount relative to income are flagged as **High Risk** ⚠️  
5. **🔹 Risk Insights Visualization**  
   - Plotted Risk distribution, LoanAmount vs Risk, TotalIncome vs Risk 📈  
6. **🔹 Summary & Recommendations**  
   - Most loans with bad credit history or high LoanAmount relative to income are flagged as High Risk ⚠️  
   - Banks can use this scoring for **quick pre-screening** 🏦  
   - Visual insights help identify **high-risk demographic or property areas** 🌍

---

## 🛠 How to Use

1. Clone or download this repository.  
2. Open `Loan_Risk_Analysis.ipynb` in Jupyter Notebook.  
3. Make sure `Loan_Risk_Data.csv` is in the same folder.  
4. Run all cells sequentially to see data analysis, visualizations, and risk scoring ✅

---

## 📊 Project Insights

- High-risk loans are mostly associated with:  
  - ❌ Bad credit history (Credit_History = 0)  
  - 💸 High LoanAmount relative to total income  
- 🌆 Urban vs Rural property areas may show trends in risk distribution  
- This analysis helps banks **prioritize applications that need further review**  

---

## 🖼 Project Image / Visualization

<img width="1536" height="1024" alt="Loan risk analysis data visualization" src="https://github.com/user-attachments/assets/7eaf10ae-e2fb-4431-a8dd-66e16659e7d4" />


**👩‍💻 Author:** Manjiri Hundikar

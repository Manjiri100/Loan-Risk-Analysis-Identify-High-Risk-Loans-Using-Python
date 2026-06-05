📊 Loan Risk Analysis Project
🧾 Overview

This project performs Exploratory Data Analysis (EDA) on a loan dataset to understand the factors that influence loan approval. The goal is to analyze patterns in applicant data and identify key drivers of loan risk and approval decisions.

🎯 Objective
Analyze loan application data
Identify patterns affecting loan approval
Handle missing values and duplicates
Visualize relationships between features and loan status
Gain insights for better decision-making in loan risk assessment
📁 Dataset

The dataset includes applicant information such as:

Applicant Income
Loan Amount
Credit History
Property Area
Loan Status (Approved/Not Approved)

Note: Dataset path used locally in the project.

🛠️ Tools & Libraries Used
Python 🐍
Pandas
NumPy
Matplotlib
Seaborn
📊 Project Workflow
1. Import Libraries

Standard data science libraries were imported for analysis and visualization.

2. Load Dataset

The dataset was loaded using Pandas for further analysis.

3. Data Exploration
Checked data structure using head(), info(), and describe()
Identified missing values
Checked duplicate records
4. Data Cleaning
Analyzed missing values
Checked dataset consistency
5. Data Visualization

Key insights were visualized using Seaborn and Matplotlib:

Loan approval distribution
Loan status vs credit history
Loan status vs property area
Income distribution
Correlation heatmap
📌 Key Insights
Credit history plays a major role in loan approval
Property area shows variation in approval patterns
Income distribution is skewed with some high earners
Missing values exist in multiple columns and need preprocessing
📈 Visualizations

The project includes:

Count plots for categorical analysis
Histograms for income distribution
Heatmaps for missing values and correlation
Comparative plots for loan status vs features
🚀 How to Run This Project
Clone this repository
git clone https://github.com/your-username/loan-risk-analysis.git
Install dependencies
pip install pandas numpy matplotlib seaborn
Run the notebook or Python script
jupyter notebook
📂 Project Structure
Loan_Risk_Analysis_Project/
│
├── Loan_Risk_Data.csv
├── loan_analysis.ipynb
├── README.md
📌 Future Improvements
Build a machine learning model for loan prediction
Perform feature engineering
Handle missing values using imputation techniques
Deploy model as a web app

---

## 🖼 Project Image / Visualization

<img width="1536" height="1024" alt="Loan risk analysis data visualization" src="https://github.com/user-attachments/assets/7eaf10ae-e2fb-4431-a8dd-66e16659e7d4" />




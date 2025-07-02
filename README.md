# 📊 Bank Loan Risk Analysis - EDA Project

## 🔍 Project Overview

This project focuses on **Exploratory Data Analysis (EDA)** for a bank loan dataset to identify key risk factors related to **loan default**. The goal is to assist financial institutions in making **data-driven decisions** when approving or rejecting loan applications by uncovering patterns in the applicant and loan attributes.

We use Python libraries such as **Pandas**, **Matplotlib**, **Seaborn**, and **Plotly** to analyze, clean, and visualize the data.

---

## 📁 Dataset Description

The project uses two datasets:

- `financial_loan.csv` — Contains client and loan attributes at the time of application.
- `financialReport.csv` — Includes additional demographic and financial info.

### Key Features Include:
- Demographic: `gender`, `marital_status`, `education`, `employment_type`
- Financial: `annual_income`, `loan_amount`, `loan_status`, `credit_score`
- Temporal: `application_date`, `disbursal_date`, `last_delinquency`

---

## 🎯 Business Objective

To identify **high-risk loan applicants** by analyzing customer data and understanding key variables that lead to **loan default**, enabling:
- Loan approval for creditworthy customers
- Rejection or stricter terms for risky applicants
- Better portfolio and risk management

---

## 🧠 EDA Workflow

### 1. Data Loading & Inspection
- Read and combine loan datasets
- View column names, types, and shape

### 2. Data Cleaning
- Handled missing values (suggested imputation)
- Detected and suggested treatment for outliers
- Converted date columns and extracted useful time features

### 3. Univariate Analysis
- Distribution of `loan_status`, `gender`, `education`, etc.
- Boxplots and histograms for continuous features

### 4. Bivariate/Multivariate Analysis
- Cross-analysis of `loan_status` with other variables
- Correlation heatmaps
- Time series plots of loan applications per month

### 5. Outlier Detection
- Boxplots for `annual_income`, `loan_amount`, and `credit_score`
- Suggested boundaries (IQR method)

### 6. Visualization Tools
- **Matplotlib** and **Seaborn** for static plots
- **Plotly** for interactive bar, scatter, and donut charts

---

## 📊 Visualizations Created

- Gender-wise loan application distribution
- Loan status by education level
- Boxplot of income vs loan status
- Donut chart of loan purposes
- Time series (monthly loan applications)
- Scatter plot of loan amount vs credit score
- Default rate by employment type

---

## 📌 Key Findings

- Higher default rates among self-employed applicants
- Loan amount and credit score have inverse relationship
- Most defaults occur in lower education and lower income groups
- Seasonal trends in application frequency (e.g., March, September spikes)

---

## 🛠️ Tech Stack

| Tool/Library     | Purpose                     |
|------------------|-----------------------------|
| Python (Pandas)  | Data cleaning & analysis    |
| Matplotlib       | Data visualization (static) |
| Seaborn          | Enhanced visual aesthetics  |
| Plotly           | Interactive plots           |
| Jupyter Notebook | Code development            |

---

## 📈 Possible Enhancements

- Add ML model for loan default prediction
- Build an interactive dashboard using **Streamlit** or **Power BI**
- Integrate real-time data from **Azure SQL** or **Firebase**
- Automate cleaning pipeline with modular code

---

## 🧾 License

This project is for educational purposes. Feel free to use the code with proper credit.

---

## 👨‍💻 Author

**BAIJU KUMAR YADAV**  
📧 yadavbaiju2005@gmail.com 
🌐 LinkedIn : https://www.linkedin.com/in/baiju-yadav-4882b81aa

---


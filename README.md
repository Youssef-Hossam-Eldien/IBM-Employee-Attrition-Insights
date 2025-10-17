# 🧠 Attrition Insights Dashboard

## 📋 Project Overview
This project explores employee attrition patterns to identify the main drivers of turnover and help HR teams make data-driven decisions.  
The analysis focuses on discovering which factors contribute most to employees leaving the company and how retention strategies can be improved.

---

## 🗂️ Dataset Description
The dataset includes demographic and professional information about employees.

| Column | Description |
|--------|-------------|
| EmployeeNumber | Unique employee identifier |
| Age | Employee’s age |
| Gender | Male / Female |
| Department | Department name |
| JobRole | Employee’s job position |
| Attrition | Whether the employee left (1 = Yes, 0 = No) |
| YearsAtCompany | Years worked at the current company |
| TotalWorkingYears | Total years of experience |
| NumCompaniesWorked | Number of previous employers |

Additional features may include salary, satisfaction level, education, and work-life balance scores.

---

## ⚙️ Tools & Technologies
- **SQL Server** → Data extraction and filtering  
- **Excel / Power Query** → Data cleaning and transformation  
- **Tableau** → Visualization and dashboard design  
- **Python (optional)** → Exploratory data analysis and preprocessing  

---

## 🧹 Data Cleaning Process
1. Extracted data from SQL Server  
2. Cleaned missing and inconsistent values using Power Query  
3. Converted binary fields like `Attrition` from `1/0` to `Yes/No`  
4. Standardized data types and removed duplicates  
5. Exported cleaned dataset for visualization in Tableau  

---

## 📊 Dashboard Insights
The Tableau dashboard provides an interactive view of:
- Overall attrition rate  
- Attrition by department, gender, and age group  
- Attrition by years at the company  
- Impact of total working years on attrition  
- Key satisfaction and engagement indicators  

### 🔍 Key Findings
- Higher attrition in **Sales** and **R&D** departments  
- Younger employees and those with fewer years at the company are more likely to leave  
- Job satisfaction and work-life balance are strongly correlated with attrition  

---

## 🧩 KPIs
- **Total Employees**  
- **Attrition Count**  
- **Attrition Rate (%)**  
- **Average Age of Leavers**  
- **Average Tenure Before Leaving**  

---

## 🚀 Outcomes
- Identified top factors influencing employee resignations  
- Provided HR with actionable insights to reduce turnover  
- Built an interactive Tableau dashboard for continuous monitoring  

---

## 📁 Project Structure
Attrition_Insights_Dashboard/
│
├── data/
│ ├── raw_data.csv
│ └── cleaned_data.xlsx
│
├── sql/
│ └── extract_attrition_data.sql
│
├── tableau/
│ └── Attrition_Insights_Dashboard.twbx
│
└── README.md

---

## 🔮 Future Enhancements
- Develop a machine learning model to predict attrition risk  
- Combine HR data with employee performance metrics  
- Automate dashboard updates using SQL or Python pipelines  

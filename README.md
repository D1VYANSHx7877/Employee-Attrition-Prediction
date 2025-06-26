# 🚀 Employee Attrition Prediction & Cost Analysis

> A data science + business intelligence project to predict employee attrition and quantify its financial impact using ML and Power BI.

**🔗 Live Dashboard** (coming soon)  
**📁 Dataset**: IBM HR Analytics — [Kaggle Source](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)  
**📌 Tools**: Python, Scikit-learn, Power BI, Pandas, Seaborn, Matplotlib  
**👤 Author**: Divyansh Dhadhich

---

## 📊 Overview

Employee attrition can cost organizations millions in lost talent and hiring. This project combines **ML modeling**, **business cost estimation**, and a **3-page Power BI dashboard** to help HR teams make data-driven retention decisions.

### 🎯 Objectives

- Predict which employees are likely to leave
- Understand key attrition drivers (job, overtime, satisfaction)
- Estimate annual attrition cost
- Provide actionable HR insights via dashboard

---

## 🧱 Project Architecture

├── data/ # Raw CSV dataset
├── notebooks/ # Python EDA + modeling notebook
├── output/ # Cleaned + enriched CSVs & model
├── powerbi/ # Final .pbix file (Power BI dashboard)
├── visuals/ # Charts for README/docs
└── README.md

---

## 🧠 ML Model Building (Python)

- Logistic Regression & Decision Tree models
- Features scaled, categorical columns encoded
- Performance evaluated on Accuracy, Recall, ROC AUC
- Final model saved using `joblib`

📌 Key Outcome:
> Logistic Regression model with **85% accuracy**  
> Identified **top 10 attrition drivers**

---

## 💸 Attrition Cost Analysis

- Estimated ₹50,000 cost per employee exit (industry avg)
- Attrition cost calculated for each department
- Exported CSV with department-level costs for Power BI

📌 Total Cost Identified:
> ₹3.4 Million in potential annual loss 💥

---

## 📊 Power BI Dashboard Overview

📁 **Location**: `/powerbi/dashboard.pbix`  
📌 **Built using:** Power BI Desktop

### 🔹 Page 1: Employee Attrition Risk & Cost Overview

- 4 KPI Cards: Attrition Rate, Cost Exposure, Risk Score, Critical Risk Employees
- Risk Histogram & Heatmap
- Retention Impact % Slider → Estimated Cost Savings 💰
- Avg Importance by Feature

### 🔹 Page 2: Department-Level Insights

- Department-wise Attrition Rate
- Attrition by Work-Life Balance
- Job Role Donut Chart
- Tenure & Income Distribution

### 🔹 Page 3: Strategic HR Actions

- Risk & Cost Matrix by Department & Role
- Suggested Action Card (Dynamic)
- Retention Strategy Table
- High-Risk Employee Download Button
- Footer: Designed by Divyansh Dhadhich

📌 **Bonus Page: KPI Tooltip Page**
- Average Years with Company, Role, Promotion, Manager
- Overtime-wise Attrition Bar Chart

---

## 🖼️ Power BI Dashboard Screenshots

Below are sample screenshots of the interactive Power BI dashboard pages:

**Page 1: Attrition Risk & Cost Overview**  
![Dashboard Page 1](visuals/charts/1.png)

**Page 2: Department-Level Insights**  
![Dashboard Page 2](visuals/charts/2.png)

**Page 3: Strategic HR Actions**  
![Dashboard Page 3](visuals/charts/3.png)

**Bonus: KPI Tooltip Page**  
![KPI Tooltip Page](visuals/charts/tooltip.png)

---

## 📁 Exported Files for Business Use

- `employee_attrition_dashboard.csv`: Cleaned & encoded data
- `employee_attrition_risk_scores.csv`: Model scores + attrition cost
- `top_attrition_drivers.csv`: Top 10 driver insights
- `model.pkl`: Trained logistic model
- `dashboard.pbix`: Power BI visualization

---

## 🧾 Key Business Insights

| Insight | Strategy |
|--------|----------|
| Sales has highest attrition rate | Adjust incentive + review OT workload |
| Overtime is a major risk factor | Introduce recovery days policy |
| Employees with <2 yrs tenure are high-risk | Implement onboarding retention mentoring |
| Costliest attrition in R&D | Provide internal mobility or tech growth |

---

## 📤 How to Run Locally

1. Clone the repo  
2. Run `01_eda_modeling.ipynb` to train model  
3. Open `powerbi/dashboard.pbix` in Power BI Desktop  
4. Adjust slicers to simulate retention strategies

---

## 📌 Contact

📧 divyanshdhadhich@gmail.com  
📍 India  
🔗 [LinkedIn](https://linkedin.com/in/yourprofile)  
🌐 Portfolio coming soon

---

## 🏁 Conclusion

This project not only predicts attrition but translates raw HR data into a **financial narrative** with real impact. A great blend of:
- ✅ Data Science
- ✅ BI Tools
- ✅ Domain Strategy

If you found this helpful, ⭐️ the repo and share your feedback!

---
# Loan Risk Analysis - IDFC Bank
This project focuses on analyzing loan applicant data from IDFC Bank to understand demographic, financial, and behavioral factors influencing loan risk.
Using Python-based data analysis, the project explores relationships among key variables such as income, age, experience, house ownership, and risk flag.
It helps in identifying low-risk, high-value customer segments, revealing regional trends, and deriving actionable insights for smarter decision-making.

## 📊 Project Overview
This project focuses on **analyzing loan applicant data** from IDFC Bank to understand customer demographics, financial attributes, and behavioral factors that influence loan risk.
The main goal is to uncover insights that can help identify **low-risk, high-value customers** and support **data-driven decision-making** for financial institutions.

---

## 🎯 Objectives
- Understand relationships among demographic and financial variables.
- Identify factors influencing the **Risk_Flag** (loan risk indicator).
- Visualize customer trends based on **profession, income, ownership, and region**.
- Support strategic planning and marketing through data insights.

---

## 🧩 Dataset Description
**File:** `Training Data.csv`  
**Rows:** ~25,000 (approx.)  
**Columns:** 12 (after cleaning)

| Column Name          | What It Means                              | Type         |
|-----------------------|---------------------------------------------|--------------|
| Income               | Annual income of the customer              | Numerical    |
| Age                  | Age of the applicant                       | Numerical    |
| Experience           | Years of work experience                   | Numerical    |
| CURRENT_JOB_YRS      | Years in current job                       | Numerical    |
| CURRENT_HOUSE_YRS    | Years in current house                     | Numerical    |
| Married/Single       | Marital status                             | Categorical  |
| House_Ownership      | House ownership type (Owned/Rented)         | Categorical  |
| Car_Ownership        | Whether the applicant owns a car            | Categorical  |
| Profession           | Profession type                            | Categorical  |
| CITY                 | Applicant’s city                           | Categorical  |
| STATE                | Applicant’s state                          | Categorical  |
| Risk_Flag            | Loan risk indicator (0 = Low Risk, 1 = High Risk) | Categorical  |

---

## 🔍 Key Analysis Performed
- Data Cleaning and Null Value Handling  
- Descriptive Statistics and Data Distribution  
- Categorical vs Numerical Variable Relationships  
- Correlation and Risk Analysis  
- Visualization using **Matplotlib, Seaborn, and Plotly**  
- Regional and Professional Trends (Tree Map, Bar, Pie, Heatmap)

---

## 📈 Sample Visuals
| Visualization | Insight |
|----------------|----------|
| **Tree Map** | Risk distribution across professions |
| **Bar Chart** | Average income by house ownership |
| **Heatmap** | Correlation among numeric variables |
| **Pie Chart** | Distribution of car ownership |

---

## 🛠️ Tools & Libraries Used
- **Python 3**
- **Pandas** – Data manipulation  
- **Matplotlib & Seaborn** – Visualization  
- **Plotly** – Interactive visuals  
- **NumPy** – Numerical computation  
- **Jupyter Notebook**

---

## 📂 Repository Structure


loan-risk-analysis-idfc/
├── data/
│ └── Training Data.csv
├── notebooks/
│ └── IDFC Loan Data (4).ipynb
├── visuals/
├── README.md
├── requirements.txt
└── LICENSE


---

## ⚙️ How to Run the Project
1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/loan-risk-analysis-idfc.git


Navigate to the folder

cd loan-risk-analysis-idfc


Install dependencies

pip install -r requirements.txt


Open the notebook

jupyter notebook notebooks/IDFC\ Loan\ Data\ (4).ipynb

💡 Insights Summary

Majority of applicants are in the Age range of 25–40 with moderate income.

Profession and Income strongly influence the Risk Flag.

Applicants with stable job and home duration show lower risk.

Urban states and metros show higher applicant volume but mixed risk levels.

🧾 Future Scope

Build a predictive model for risk classification.

Develop a dashboard for visual exploration.

Integrate with real-time loan approval systems.

👨‍💻 Author

Palavalasa Sai
📧 [palavalasasai42@gmail.com
]
💼 Data Analytics Enthusiast | Python | SQL | Visualization

📜 License

This project is open-source and available under the MIT License.

---

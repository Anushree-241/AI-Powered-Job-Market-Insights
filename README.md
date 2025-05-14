# AI Adoption Power BI Dashboard

This project visualizes AI adoption trends across industries using job market data. The dashboard was created in Power BI and includes insights into:

- 📌 Top 3 industries with the highest AI adoption
- 🏢 AI adoption by company size
- ⚠️ Automation risk levels across roles

## 📊 Dataset

**Source**: [AI-Powered Job Market Insights (Kaggle)](https://www.kaggle.com/datasets/uom190346a/ai-powered-job-market-insights)

- 500+ job listings
- Fields include Industry, AI Adoption Level, Company Size, Automation Risk

> You may need a free Kaggle account to access the dataset.

## 🛠️ Tools Used

- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query
- Excel (for data preprocessing)

## 📷 Screenshot

![Dashboard Preview](screenshots/dashboard.png)

## 📁 How to Use

1. Clone or download this repo.
2. Open the `.pbix` file using Power BI Desktop.
3. Interact with the visuals using filters for industry, company size, and more.

---

## 📎 Key Measures (DAX)

- **Total Jobs**: `COUNTROWS(AI_Jobs)`
- **High AI Adoption %**: `% of jobs with AI_Adoption_Level = High`
- **High Risk %**: `% of jobs with Automation_Risk = High`

---

## 🔗 Author

**Anushree R**  
[LinkedIn](https://www.linkedin.com/in/anushree-r-25104920a) | [GitHub](https://github.com/Anushree-241)

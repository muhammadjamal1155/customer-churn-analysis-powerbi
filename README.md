# 📊 Customer Churn Analysis — Power BI Case Study

> **A complete end-to-end churn analysis dashboard built in Power BI**, identifying why customers leave and which segments are most at risk.

This project was completed as part of the **Data Analyst in Power BI** career track on [DataCamp](https://www.datacamp.com/learn/courses/case-study-analyzing-customer-churn-in-power-bi).

---

## 📌 Project Overview

Customer churn is one of the most critical business problems — losing a customer costs far more than retaining one. In this case study, I analyzed a telecom company's customer data to:

- Calculate the overall churn rate
- Identify the top reasons customers are leaving
- Discover which contract types, data plans, and payment methods are linked to higher churn
- Analyze geographic churn patterns across US states
- Understand how customer service interactions relate to churn behavior

---

## 🛠️ Tools & Skills Used

| Tool / Skill | Usage |
|---|---|
| **Power BI Desktop** | Dashboard design & report building |
| **Power Query** | Data cleaning & transformation |
| **DAX (Data Analysis Expressions)** | Custom measures & KPIs |
| **Data Modeling** | Relationships between tables |
| **Map Visuals (Bing Maps)** | Geographic churn analysis |
| **Drill-throughs & Slicers** | Interactive filtering |

---

## 📂 Dataset

The dataset contains telecom customer records including:

- Customer demographics
- Contract type (Monthly / Yearly)
- Data plan & consumption (Less than 5 GB / 5–10 GB / 10+ GB)
- Payment method
- Customer service call history
- Churn label and churn reason

---

## 📈 Dashboard Pages

### Page 1 — Churn Overview & Reasons

![Churn Overview Dashboard](screenshots/page1_churn_overview.png)

**Key highlights:**
- Overall churn rate: **26.86%** (1,796 out of 6,687 customers churned)
- **Monthly contract customers** churn at a significantly higher rate (~45%) compared to yearly contract customers (~7%)
- Top churn categories: **Competitor (44.82%)**, followed by Attitude (15.98%) and Dissatisfaction (15.92%)
- Leading churn reasons: Competitor made a better offer, Competitor had better devices, and Attitude of support staff

---

### Page 2 — International Data Charges & Data Plan Analysis

![International Data and Data Plan Dashboard](screenshots/page2_data_plan.png)

**Key highlights:**
- Average extra international charges: **$33.64**
- Average extra data charges: **$3.37**
- Customers on an **unlimited data plan who use less than 5 GB** have a disproportionately high churn rate (~35%), suggesting they are overpaying and likely to leave
- Churn rate is relatively similar for heavy data users (5 GB+) regardless of unlimited plan status

---

### Page 3 — Service Calls & Contract/Payment Analysis

![Service Calls and Contract Analysis Dashboard](screenshots/page3_service_calls.png)

**Key highlights:**
- Total customer service calls: **6,123** | Average per customer: **0.92**
- Churned customers ("Yes" label) consistently make **more service calls** across all states compared to retained customers
- Monthly contract customers who pay via direct debit show the highest churn rates (50–57%) in the scatter plot
- Yearly contract customers have much longer average account lengths (40–50 months) and very low churn rates (5–10%)

---

### Page 4 — Churn Rate by Contract Category & Payment Method

![Churn Rate by Contract and Payment Dashboard](screenshots/page4_contract_payment.png)

**Key highlights:**
- Sum of customer service calls: **6,123** | Average: **0.92 per customer**
- Clear pattern: **shorter account length = higher churn risk** for monthly contract customers
- Monthly customers with 5–20 months tenure show churn rates of 30–58%
- Yearly customers remain stable regardless of account length

---

## 💡 Key Insights & Recommendations

| # | Insight | Recommendation |
|---|---|---|
| 1 | Month-to-month contracts drive the most churn (~45%) | Offer incentives to convert customers to yearly contracts |
| 2 | Competitors are the #1 churn reason (44.82%) | Conduct competitive analysis and improve offering |
| 3 | Customers making more service calls are more likely to churn | Improve first-call resolution and support quality |
| 4 | Customers on unlimited plans using <5 GB churn at ~35% | Offer plan downgrades proactively to retain value-conscious customers |
| 5 | New customers (first 12 months) are most vulnerable | Implement an onboarding retention program |

---

## 🚀 How to Open This Project

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Clone or download this repository
3. Open the `.pbix` file in Power BI Desktop
4. Explore the interactive dashboard using slicers and drill-throughs

```bash
git clone https://github.com/YOUR_USERNAME/customer-churn-analysis-powerbi.git
```

```

---

## 🎓 Course

This project is part of the **[Data Analyst in Power BI](https://www.datacamp.com/tracks/data-analyst-in-power-bi)** career track on DataCamp.

**Case Study:** [Analyzing Customer Churn in Power BI](https://app.datacamp.com/learn/courses/case-study-analyzing-customer-churn-in-power-bi)

---

## 🙋‍♂️ About Me

I'm currently building my skills in data analytics through the DataCamp Power BI track. This project demonstrates my ability to work with real-world business data, build interactive dashboards, and extract actionable insights.

📫 Connect with me on [LinkedIn](https://www.linkedin.com/in/YOUR_PROFILE)

---

*If you found this useful, feel free to ⭐ star the repo!*

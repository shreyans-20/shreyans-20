<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=230&section=header&text=Shreyans%20Jain&fontSize=62&fontAlignY=36&desc=I%20turn%20messy%20data%20into%20decisions%20people%20can%20act%20on&descAlignY=58&descSize=18" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=8B5CF6&center=true&vCenter=true&width=720&lines=Business+Analyst+%F0%9F%93%8A;Power+BI+%2B+DAX+Storyteller+%F0%9F%93%88;SQL+Detective+%F0%9F%95%B5%EF%B8%8F;Fresher+with+real+internship+impact+%F0%9F%9A%80)](https://git.io/typing-svg)

</div>

---

```sql
SELECT  name, role, superpower
FROM    analysts
WHERE   turns_messy_data_into_decisions = TRUE
LIMIT   1;   -- 👈 that's me
```

| 👤 **Who** | 📍 **Where** | 🎯 **Aiming for** |
|---|---|---|
| Shreyans Jain | BBA Business Analytics, V.M. Patel College of Management Studies, Ganpat University | Business Analyst · Power BI Developer · Data Analyst |

I build dashboards that **track real business decisions**: hotel demand, flight spend, campaign profitability and route-level travel intelligence. At **TripTrip India** (a B2B corporate travel platform), I replaced spreadsheet grind with automated dashboards and **cut manual reporting effort by 40%**.

<div align="center">

![Reporting Effort Cut](https://img.shields.io/badge/Manual%20Reporting-%E2%88%9240%25-22c55e?style=for-the-badge)
![SGPA](https://img.shields.io/badge/SGPA-9.10-8b5cf6?style=for-the-badge)
![IBM](https://img.shields.io/badge/IBM-Data%20Analyst-1f70c1?style=for-the-badge&logo=ibm&logoColor=white)
![Microsoft](https://img.shields.io/badge/Microsoft-Certified-00a4ef?style=for-the-badge&logo=microsoft&logoColor=white)
![Google](https://img.shields.io/badge/Google-Data%20Analytics-ea4335?style=for-the-badge&logo=google&logoColor=white)

</div>

---

## 🌐 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shreyansjainn/)
[![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)](https://www.notion.so/Shreyans-Jain-s-Portfolio-2e748001fb70801e9400d5a0adc59544)

---

## 🧰 The Toolkit

| 🎒 Slot | ⚔️ Tools |
|---|---|
| **Code & Analytics** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) Matplotlib · Seaborn · SAS |
| **Databases** | ![MySQL](https://img.shields.io/badge/MySQL-00758F?style=flat-square&logo=mysql&logoColor=white) SQL (CTEs · Window Functions) · Azure |
| **BI & Visualization** | ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black) ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white) ![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white) |
| **Data Modeling** | Power Query (M) · DAX · Data Cleaning · Star Schema Design |
| **Business Analysis** | BRD · FRD & SRS · NFR · UAT · Stakeholder Analysis |
| **Statistical Tools** | SPSS · AMOS · NVivo |
| **Certifications** | IBM Data Analyst · Google Data Analytics · Microsoft Certified · Johns Hopkins |

---

## 🗂️ Featured Case Files

> Every project below starts with a real question, and ends with something a stakeholder can act on.

<br>

### 🥇 [Case #1 · E-commerce & Campaign Profitability Analyzer](https://github.com/shreyans-20/Ecommerce-Campaign-Profitability-Analyzer)
*Closing the gap between what Marketing reports and what Finance actually earns.*

![SQL](https://img.shields.io/badge/SQL-CTEs%20%7C%20Window%20Functions-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00758F?style=flat-square&logo=mysql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![BA](https://img.shields.io/badge/BRD%20%C2%B7%20FRD%20%C2%B7%20UAT-Full%20BA%20Lifecycle-8b5cf6?style=flat-square)

**🕵️ The mystery:** Marketing sees checkout revenue vs. ad spend. Finance sees what's left after discounts, COGS, refunds and payment reconciliation. Same campaign, two different numbers.

**🛠️ The build** *(co-built with Aadhya Patel)*
- Designed a **7-table relational MySQL database** (customers, campaigns, products, orders, line items, payments, refunds) to act as one reconciled source of truth.
- Wrote SQL for **10 functional requirements**: net revenue and COGS per order, campaign contribution profit and **ROAS ranked with `DENSE_RANK()`**, VIP/Active/Dormant segmentation, payment and refund exception reports, and **MoM growth with `LAG()`**.
- Enforced hard business rules: cancelled orders excluded everywhere, and **zero-spend campaigns return `NULL` ROAS, never a fake 0**.
- Took it through the full BA lifecycle: Problem Statement → BRD → FRD/SRS → NFR → **UAT (7/7 test cases passed)**.

**💡 The plot twist:** at a $1,500 threshold, **88% of customers came out as VIP**. That is a flag, not a win: the rule needs recalibrating. I documented it as a finding instead of hiding it.

*🚧 Power BI dashboard layer in progress.*

<br>

### 🥈 [Case #2 · DataLens: EDA Studio](https://github.com/shreyans-20/Data-Lens-Eda)
*Drop in a CSV. Get a full analysis dashboard. Zero setup.*

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

- 🧠 **Auto column profiling** detects numeric, categorical and datetime columns, then computes stats, outliers and correlations in a single pass.
- 🎨 A **Visualization Builder** with 8 chart types lets you explore without writing code.
- 🤖 **ML-prep export** (encoding + standardization) and **auto-generated HTML EDA reports**.
- ⭐ **Star Schema detection** automatically joins fact and dimension tables from multi-sheet Excel files.

<br>

### 🏨 [Case #3 · City-Level Hotel Insight Dashboard](https://github.com/shreyans-20/City-Level-Hotel-Insight-Dashboard)
*Built at TripTrip India to kill manual reporting.*

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black) ![DAX](https://img.shields.io/badge/DAX-8b5cf6?style=flat-square) ![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=flat-square)

- Automated city-level demand tracking → **40% less manual reporting effort**.
- Wrote DAX measures that surface **occupancy trends and demand shifts** across hotel segments.

<br>

### ✈️ [Case #4 · Flight Spend & Cost Analysis Dashboard](https://github.com/shreyans-20/Flight-Spend-Cost-Analysis-Dashboard)
*Where is the corporate travel budget actually going?*

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black) ![DAX](https://img.shields.io/badge/DAX-8b5cf6?style=flat-square) ![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=flat-square)

- Built **route-level cost intelligence** to spot high-spend corridors and booking inefficiencies.
- Gave stakeholders the data to make calls on **travel policy and vendor selection**.

<br>

### 🗺️ [Case #5 · Corporate Travel Demand & Route Intelligence](https://github.com/shreyans-20/Corporate-Travel-Demand-Route-Intelligence-Dashboard)
*A map of where the business actually travels.*

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black) ![DAX](https://img.shields.io/badge/DAX-8b5cf6?style=flat-square) ![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=flat-square)

- Mapped route-level demand patterns to support **procurement and capacity planning**.
- Merged multiple data sources into **one unified model** using Power Query transformations.

<br>

### 🤖 [Case #6 · Measuring the Impact of AI Tools on Students' Productivity](https://github.com/shreyans-20/Measuring-the-Impact-of-Artificial-Intelligence-Tools-on-Students-Productivity)
*Does AI actually make students more productive? I asked 388 of them.*

![SPSS](https://img.shields.io/badge/SPSS-052FAD?style=flat-square&logo=ibm&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)

- Primary research across **North Gujarat** with **n = 388** survey responses.
- Ran **regression analysis, Cronbach's Alpha reliability testing and descriptive statistics**.
- Identified the key **predictors of productivity gain** and validated the model with **factor analysis**.

---

## 🚀 Now Loading...

- 🐍 Sharpening **Python** for automation and end-to-end data pipelines
- 📐 **Business Analytics capstone**: regression, ANOVA and logistic modeling on real datasets
- 📈 Finishing the **Power BI layer** for the Campaign Profitability Analyzer

---

## 📊 GitHub Stats

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=shreyans-20&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=shreyans-20&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

<div align="center">

### 🟢 Open to opportunities

**Business Analyst · Power BI Developer · Data Analyst** (Fresher)

*If your team has messy data and big questions, let's talk.*

[![Message me on LinkedIn](https://img.shields.io/badge/Message%20me%20on%20LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shreyansjainn/)

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%"/>

</div>

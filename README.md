# 🚴 Bike Sales Analytics Dashboard | Excel End-to-End Project

> **An interactive Excel dashboard that turns 1,000 raw customer records into a clear answer to one business question: *who actually buys a bike, and where should marketing spend next?***

<p align="center">
  <img src="https://img.shields.io/badge/Status-Completed-2E8B57?style=for-the-badge&logo=checkmarx&logoColor=white" />
  <img src="https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" />
  <img src="https://img.shields.io/badge/Pivot%20Tables-D2691E?style=for-the-badge&logo=microsoft-excel&logoColor=white" />
  <img src="https://img.shields.io/badge/Dashboarding-1F77B4?style=for-the-badge&logo=tableau&logoColor=white" />
  <img src="https://img.shields.io/badge/Records-1%2C000%20Customers-2E8B57?style=for-the-badge&logo=databricks&logoColor=white" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Domain-Retail%20Analytics-FF6F00?style=flat-square" />
  <img src="https://img.shields.io/badge/Type-Customer%20Segmentation-8E44AD?style=flat-square" />
  <img src="https://img.shields.io/badge/Difficulty-Intermediate-yellow?style=flat-square" />
  <img src="https://img.shields.io/badge/Build%20Time-12%20hours-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Last%20Updated-May%202026-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square" />
</p>

---

## 📸 Dashboard Preview

![Bike Sales Dashboard](dashboard_preview.png)

<p align="center">
  <img src="https://img.shields.io/badge/Charts-3%20Interactive-2E8B57?style=flat-square&logo=chartdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/KPI%20Cards-3-D2691E?style=flat-square" />
  <img src="https://img.shields.io/badge/Slicers-Enabled-217346?style=flat-square&logo=microsoft-excel&logoColor=white" />
  <img src="https://img.shields.io/badge/Plugins-None-success?style=flat-square" />
</p>

*Built entirely in Microsoft Excel no plugins, no add-ins. Pivot tables, slicers, and native chart objects only.*

---

## 🎯 Project Objective

<p align="left">
  <img src="https://img.shields.io/badge/Business%20Goal-Targeted%20Marketing-orange?style=flat-square&logo=target&logoColor=white" />
  <img src="https://img.shields.io/badge/Output-Executive%20Dashboard-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Audience-Non%E2%80%91Technical-lightgrey?style=flat-square" />
</p>

A bicycle retailer wanted to understand **which customer segments are most likely to purchase a bike** so the marketing team could move from "spray-and-pray" campaigns to targeted outreach. I was given an unvalidated dataset of 1,000 customer profiles and asked to deliver a dashboard a non-technical sales manager could read in under 30 seconds.

**Business questions answered:**
1. What does the average bike buyer look like age, income, region, lifestyle?
2. Is there an income gap between buyers and non-buyers?
3. Does commute distance actually predict purchase intent?
4. Which age group is the most profitable target audience?
5. Which geographic region should we double down on?

---

## 🛠️ Tech Stack & Skills Demonstrated

<p align="left">
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" />
  <img src="https://img.shields.io/badge/Pivot%20Tables-D2691E?style=for-the-badge&logo=microsoft-excel&logoColor=white" />
  <img src="https://img.shields.io/badge/Slicers-2E8B57?style=for-the-badge&logo=microsoft-excel&logoColor=white" />
  <img src="https://img.shields.io/badge/Charts-1F77B4?style=for-the-badge&logo=chartdotjs&logoColor=white" />
</p>

| Area | Skills Used | Badge |
|---|---|---|
| **Data Cleaning** | Find & Replace, Remove Duplicates, conditional formatting | ![Cleaning](https://img.shields.io/badge/Cleaning-217346?style=flat-square) |
| **Data Transformation** | `IF` statements, bucketing continuous variables | ![Transform](https://img.shields.io/badge/Transform-D2691E?style=flat-square) |
| **Analysis** | Pivot Tables, cross-tabulations, aggregation | ![Analysis](https://img.shields.io/badge/Analysis-2E8B57?style=flat-square) |
| **Visualization** | Clustered bar, line charts, KPI cards | ![Viz](https://img.shields.io/badge/Visualization-1F77B4?style=flat-square) |
| **Interactivity** | Slicers, dynamic filters | ![Interactive](https://img.shields.io/badge/Interactive-8E44AD?style=flat-square) |
| **Design** | Color palette, typography, exec-ready layout | ![Design](https://img.shields.io/badge/Design-FF6F00?style=flat-square) |

**Transferable to:**

<p align="left">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
</p>

---

## 📂 Workbook Structure

<p align="left">
  <img src="https://img.shields.io/badge/Sheets-4-217346?style=flat-square&logo=microsoft-excel&logoColor=white" />
  <img src="https://img.shields.io/badge/Total%20Rows-2%2C000%2B-D2691E?style=flat-square" />
  <img src="https://img.shields.io/badge/Fields-14-2E8B57?style=flat-square" />
</p>

The file (`Bikes_Sales_Dashboard.xlsx`) is organized into four sheets, each with a clear purpose:

| Sheet | Purpose | Rows | Badge |
|---|---|---|---|
| **`bike_buyers`** | Raw data as received — preserved untouched for auditability | 1,000 | ![Raw](https://img.shields.io/badge/Type-Raw%20Data-lightgrey?style=flat-square) |
| **`Clean Sheet`** | Deduplicated, standardized, and bucketed working dataset | 1,026 | ![Clean](https://img.shields.io/badge/Type-Cleaned-2E8B57?style=flat-square) |
| **`PIVOT TABLE`** | Three pivot tables that power every chart on the dashboard | — | ![Pivot](https://img.shields.io/badge/Type-Aggregated-D2691E?style=flat-square) |
| **`DASHBOARD`** | The final one-page interactive view| ![Dash](https://img.shields.io/badge/Type-Visualization-1F77B4?style=flat-square) |

### Dataset Schema (14 fields)

`ID` · `Marital Status` · `Gender` · `Income` · `Children` · `Education` · `Occupation` · `Home Owner` · `Cars` · `Commute Distance` · `Region` · `Age` · `Age Brackets` · `Purchased Bike`

---

## 🔍 Process Walkthrough

<p align="left">
  <img src="https://img.shields.io/badge/Step%201-Data%20Cleaning-217346?style=flat-square" />
  <img src="https://img.shields.io/badge/Step%202-Feature%20Engineering-D2691E?style=flat-square" />
  <img src="https://img.shields.io/badge/Step%203-Pivot%20Analysis-2E8B57?style=flat-square" />
  <img src="https://img.shields.io/badge/Step%204-Dashboard%20Build-1F77B4?style=flat-square" />
</p>

### Step 1 — Data Cleaning ![Cleaning](https://img.shields.io/badge/Status-Done-success?style=flat-square)
- Removed **26 duplicate records** using `Data → Remove Duplicates`
- Standardized inconsistent values (e.g., `"M"` / `"Male"` → `Male`)
- Replaced cryptic codes with readable labels (`M`/`S` → `Married`/`Single`)
- Spot-checked outliers in `Income` (range: $10K–$170K) and `Age` (25–89)

### Step 2 — Feature Engineering ![Feature](https://img.shields.io/badge/Status-Done-success?style=flat-square)
Created an `Age Brackets` column to make age analysis chart-friendly:
```excel
=IF(L2<31,"Adolescent", IF(L2<55,"Middle Age","Old"))
```
This single transformation turned a continuous variable into the cleanest insight in the entire dashboard.

### Step 3 — Pivot Analysis ![Pivot](https://img.shields.io/badge/Status-Done-success?style=flat-square)
Built three pivot tables, each isolating one variable against `Purchased Bike`:
- **Avg Income** broken down by `Gender` and purchase outcome
- **Customer count** by `Commute Distance` and purchase outcome
- **Customer count** by `Age Bracket` and purchase outcome

### Step 4 — Dashboard Assembly ![Dashboard](https://img.shields.io/badge/Status-Done-success?style=flat-square)
- Pulled three live charts from the pivots onto a dedicated `DASHBOARD` sheet
- Added three KPI cards (Total Customers · Bikes Purchased · Top Region)
- Wired slicers so a stakeholder can filter by region/marital status/education and watch every chart update instantly
- Applied a consistent green (`#2E5947`) / orange (`#D2691E`) palette for visual hierarchy

---

## 💡 Key Insights

<p align="left">
  <img src="https://img.shields.io/badge/Insights-5%20Actionable-FF6F00?style=for-the-badge&logo=lightbulb&logoColor=white" />
  <img src="https://img.shields.io/badge/Conversion%20Rate-48.1%25-2E8B57?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Top%20Segment-Middle%20Age-D2691E?style=for-the-badge" />
</p>

After the analysis, five findings stood out — each one directly actionable for marketing:

### 1️⃣ **48.1% of customers in the dataset purchased a bike**
![Conversion](https://img.shields.io/badge/Buyers-481%20%2F%201%2C000-2E8B57?style=flat-square) ![Rate](https://img.shields.io/badge/Baseline%20Rate-48.1%25-D2691E?style=flat-square)

Out of 1,000 prospects, **481 became buyers**. A healthy baseline conversion rate — but the *distribution* matters far more than the average.

### 2️⃣ **Pacific is the highest-converting region (58.9%)**
| Region | Purchase Rate | Badge |
|---|---|---|
| 🌏 **Pacific** | **58.9%** | ![Pacific](https://img.shields.io/badge/Top%20Region-58.9%25-2E8B57?style=flat-square) |
| 🇪🇺 Europe | 49.3% | ![Europe](https://img.shields.io/badge/Europe-49.3%25-D2691E?style=flat-square) |
| 🇺🇸 North America | 43.3% | ![NA](https://img.shields.io/badge/North%20America-43.3%25-lightgrey?style=flat-square) |

> ![Rec](https://img.shields.io/badge/Recommendation-Action-FF6F00?style=flat-square) Re-balance the regional ad budget. Pacific outperforms North America by 15.6 percentage points despite likely receiving less spend.

### 3️⃣ **Middle-Age (31–54) buyers convert at 54.6%** — almost 2× the rate of older customers
| Age Bracket | Purchase Rate | Badge |
|---|---|---|
| Adolescent (<31) | 35.5% | ![Adol](https://img.shields.io/badge/Adolescent-35.5%25-lightgrey?style=flat-square) |
| **Middle Age (31–54)** | **54.6%** | ![Mid](https://img.shields.io/badge/Middle%20Age-54.6%25-2E8B57?style=flat-square) |
| Old (55+) | 31.2% | ![Old](https://img.shields.io/badge/Old-31.2%25-lightgrey?style=flat-square) |

> ![Rec](https://img.shields.io/badge/Recommendation-Action-FF6F00?style=flat-square) Lead campaigns with Middle-Age messaging — career-stage cyclists, family commute angles, fitness-restart narratives.

### 4️⃣ **Buyers earn more — but the gap is smaller than you'd think**
![Male](https://img.shields.io/badge/Male%20Buyers-%2460K-2E8B57?style=flat-square) ![MaleNo](https://img.shields.io/badge/Male%20Non%E2%80%91Buyers-%2456K-lightgrey?style=flat-square)
![Fem](https://img.shields.io/badge/Female%20Buyers-%2456K-2E8B57?style=flat-square) ![FemNo](https://img.shields.io/badge/Female%20Non%E2%80%91Buyers-%2453K-lightgrey?style=flat-square)

- Male buyers earn ~**$60K** vs. ~$56K for non-buyers
- Female buyers earn ~**$56K** vs. ~$53K for non-buyers

> ![Rec](https://img.shields.io/badge/Recommendation-Action-FF6F00?style=flat-square) Income matters but isn't the gatekeeper. A $50K shopper is still a strong prospect — don't price out the middle market.

### 5️⃣ **Commute distance has a non-linear effect**
![Short](https://img.shields.io/badge/0%E2%80%911%20mi-54.6%25-2E8B57?style=flat-square) ![Mid](https://img.shields.io/badge/2%E2%80%915%20mi-58.6%25-2E8B57?style=flat-square) ![Long](https://img.shields.io/badge/10%2B%20mi-29.7%25-red?style=flat-square)

Short (0–1 mi) and medium (2–5 mi) commuters buy most. Long-distance commuters (10+ mi) convert at only **29.7%** — they likely drive.

> ![Rec](https://img.shields.io/badge/Recommendation-Action-FF6F00?style=flat-square) Geo-target neighborhoods within 5 miles of business districts. Skip suburban-sprawl zip codes.

---

## 📈 Business Impact (If Deployed)

<p align="left">
  <img src="https://img.shields.io/badge/Current%20Rate-48.1%25-D2691E?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Projected%20Rate-~53%25-2E8B57?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Lift-%2B50%20Sales%20%2F%201K-FF6F00?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Added%20Budget-%240-success?style=for-the-badge" />
</p>

If marketing acts on the regional and age-bracket findings, a conservative re-allocation could lift overall conversion from **48.1% → ~53%** — roughly **50 additional sales per 1,000 prospects** without growing the budget.

---

## 🚀 How to Use This Project

<p align="left">
  <img src="https://img.shields.io/badge/Excel-2016%2B-217346?style=flat-square&logo=microsoft-excel&logoColor=white" />
  <img src="https://img.shields.io/badge/Setup%20Time-30%20seconds-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/No%20Code%20Required-success?style=flat-square" />
</p>

1. **Clone or download** this repository.
2. Open `Bikes_Sales_Dashboard.xlsx` in Microsoft Excel (2016 or later).
3. Navigate to the **`DASHBOARD`** sheet.
4. Use the slicers on the left panel to filter by region, education, or marital status — every chart updates in real time.

---

## 🗂️ Repository Contents

```
📁 Bike-Sales-Dashboard/
├── 📊 Bikes_Sales_Dashboard.xlsx     # The full workbook (4 sheets)
├── 🖼️ dashboard_preview.png          # Static preview of the dashboard
└── 📄 README.md                      # This file
```

---

## 🧑‍💻 About Me

<p align="left">
  <img src="https://img.shields.io/badge/MS%20Business%20Analytics-Golden%20Gate%20University-2E8B57?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Graduating-May%202026-D2691E?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Location-San%20Francisco%2C%20CA-1F77B4?style=for-the-badge&logo=googlemaps&logoColor=white" />
  <img src="https://img.shields.io/badge/Open%20to%20Work-Yes-success?style=for-the-badge" />
</p>

I'm **Satish**, an M.S. Business Analytics candidate at **Golden Gate University, San Francisco** (graduating May 2026), focused on roles at the intersection of **data, strategy, and product** — Business Analyst, Data Analyst, and Strategy & Operations Analyst positions at SaaS and product-led growth companies.

### My Toolkit

<p align="left">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" />
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
</p>

### Focus Areas

<p align="left">
  <img src="https://img.shields.io/badge/Funnel%20Analysis-2E8B57?style=flat-square" />
  <img src="https://img.shields.io/badge/KPI%20Tracking-D2691E?style=flat-square" />
  <img src="https://img.shields.io/badge/Dashboard%20Development-1F77B4?style=flat-square" />
  <img src="https://img.shields.io/badge/Customer%20Segmentation-8E44AD?style=flat-square" />
  <img src="https://img.shields.io/badge/Product%E2%80%91Led%20Growth-FF6F00?style=flat-square" />
  <img src="https://img.shields.io/badge/SaaS%20Metrics-217346?style=flat-square" />
</p>

### 📫 Let's Connect

<p align="left">
  <a href="https://linkedin.com/in/satishreddy16">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:satishreddygunukula@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/satishreddy16">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>

## ⭐ If you found this project useful…

<p align="center">
  <img src="https://img.shields.io/badge/Star%20the%20Repo-%E2%AD%90-yellow?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Fork%20Welcome-%F0%9F%8D%B4-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Feedback%20Appreciated-%F0%9F%92%AC-success?style=for-the-badge" />
</p>

…drop a star on the repo it helps recruiters find my work and helps me know what's landing.

---

<p align="center">
  <em>Built with curiosity, caffeine, and a deep belief that good analytics is just clear questions answered clearly.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F-red?style=flat-square" />
  <img src="https://img.shields.io/badge/Powered%20by-Curiosity-blueviolet?style=flat-square" />
  <img src="https://img.shields.io/badge/Fueled%20by-%E2%98%95%20Caffeine-795548?style=flat-square" />
</p>

# 🚀 Influencer Marketing ROI Engine

> A full-stack Excel analytics dashboard for evaluating influencer campaign performance, identifying high-ROI creators, and optimizing marketing budget allocation.

---

## 📌 Overview

This project analyzes influencer marketing campaigns across Instagram, TikTok, and YouTube using key performance metrics — including CTR, Conversion Rate, CAC, and ROAS — to surface which creators and platforms deliver the strongest return on investment.

Built entirely in **Microsoft Excel for the Web**, it demonstrates end-to-end marketing analytics: raw data ingestion, KPI calculation, platform aggregation, and executive-level dashboarding with strategic recommendations.

---

## 🛠️ Tools & Techniques

| Tool | Usage |
|------|-------|
| Excel for the Web | Primary analytics environment |
| Structured Tables | Raw campaign data with auto-expanding formulas |
| SUMIF / AVERAGEIF | Platform-level aggregation |
| INDEX / MATCH | Dynamic top/bottom creator lookup |
| Column & Bar Charts | Revenue, ROAS, and platform visualizations |
| Dashboard Design | KPI cards, color-coded metrics, recommendation boxes |

---

## 📐 Metrics Tracked

| Metric | Formula | Business Meaning |
|--------|---------|-----------------|
| **CTR** | Clicks ÷ Followers | Audience engagement with content |
| **Conversion Rate** | Conversions ÷ Clicks | Landing page / offer effectiveness |
| **CAC** | Cost ÷ Conversions | Efficiency of spend per customer |
| **ROAS** | Revenue ÷ Cost | Dollar return per dollar spent |
| **ROI Score** | (Engagement × Conversions × Revenue) ÷ Cost | Composite performance index |

---

## 🎯 Business Goal

Identify which creators and platforms generate the highest return so marketing budgets can be shifted toward campaigns with the strongest conversion efficiency and lowest customer acquisition cost.

---

## 📊 Dashboard Preview

The Dashboard sheet includes:

- **4 KPI Cards** — Total Revenue, Total Cost, Avg ROAS, Total Conversions
- **4 Secondary Metrics** — Avg CTR, Avg Conversion Rate, Avg CAC, Total Clicks
- **3 Charts** — Revenue by Creator, ROAS by Creator, Platform Avg ROAS
- **3 Recommendation Boxes** — Top creator to scale, lowest performer to reassess, best platform to prioritize

---

## 💡 Key Insights

1. **Instagram micro-influencers (25K–70K followers)** consistently outperform larger creators on ROAS and CAC, driven by higher engagement rates in the 5–7% range.
2. **YouTube creators** show the highest raw reach but the lowest ROAS — better suited for brand awareness campaigns than direct-response objectives.
3. **TikTok** delivers balanced mid-tier performance; shifting toward native short-video ad formats could meaningfully improve conversion rates.

---

## 📂 Workbook Structure

```
Influencer_Marketing_ROI_Engine.xlsx
├── Raw_Data          # 15 creator rows + CTR, Conv Rate, CAC, ROAS, ROI Score
├── Calculations      # Aggregated KPIs + platform-level SUMIF/AVERAGEIF summaries
├── Dashboard         # Visual KPI cards, charts, and strategic recommendations
└── Read_Me           # Project documentation and metric definitions
```

---

## 📁 Files

| File | Description |
|------|-------------|
| `Influencer_Marketing_ROI_Engine.xlsx` | Full Excel workbook with all 4 sheets |
| `dashboard_screenshot.png` | Dashboard overview *(add after opening in Excel)* |
| `raw_data_screenshot.png` | Raw data table *(add after opening in Excel)* |
| `README.md` | This file |

---

## 🚀 How to Use

1. Download `Influencer_Marketing_ROI_Engine.xlsx`
2. Open in **Excel for the Web** or **Excel for Mac**
3. Navigate to `Raw_Data` to update or add creator rows — all KPIs recalculate automatically
4. View the `Dashboard` sheet for the full visual summary
5. Use the Recommendations section to guide budget decisions

---

## 🏷️ Skills Demonstrated

`Marketing Analytics` · `KPI Modeling` · `Excel Dashboarding` · `CAC / ROAS` · `Data Visualization` · `Budget Optimization` · `Influencer Performance Analysis`

---

*Built as a portfolio project to demonstrate marketing analytics and Excel dashboarding capabilities.*

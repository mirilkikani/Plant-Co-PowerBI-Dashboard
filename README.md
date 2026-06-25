# 🌿 Plant Co. Sales Performance Dashboard — Power BI
> *"Growing Plants. Growing Insights."*

An interactive Power BI dashboard analyzing sales performance across Plant Co. accounts worldwide (2022–2024).

---

## 📊 Dashboard Preview

![Sales](Screenshot%202026-06-26%20005533.png)
![Quantity](Screenshot%202026-06-26%20005618.png)
![Gross Profit](Screenshot%202026-06-26%20005731.png)

---

## 📁 Project Structure

```
Plant-Co-PowerBI-Dashboard/
│
├── Performance_Report.pbix          # Power BI report file
├── Plant_DTS.xls                    # Source dataset
├── Screenshot 2026-06-26 005533.png # Sales view preview
├── Screenshot 2026-06-26 005618.png # Quantity view preview
├── Screenshot 2026-06-26 005731.png # Gross Profit view preview
└── README.md
```

---

## 🧾 Dataset Overview

| Attribute     | Details                          |
|---------------|----------------------------------|
| Source        | Plant_DTS.xls                    |
| Rows          | 2,440 (Fact Sales)               |
| Accounts      | 1,744                            |
| Products      | 1,000                            |
| Time Period   | 2022 – 2024                      |
| Countries     | 54                               |

### Fact Sales Columns

| Column       | Description                        |
|--------------|------------------------------------|
| Product_id   | Unique product identifier          |
| Sales_USD    | Sales revenue in USD               |
| Quantity     | Number of units sold               |
| Price_USD    | Unit price in USD                  |
| COGS_USD     | Cost of goods sold in USD          |
| Date_Time    | Transaction date                   |
| Account_id   | Linked account identifier          |

### Account Columns

| Column        | Description                       |
|---------------|-----------------------------------|
| Account       | Account/company name              |
| Account_id    | Unique account identifier         |
| country_code  | Country code                      |
| country2      | Full country name                 |
| Postal_code   | Postal code                       |
| latitude2     | Geographic latitude               |
| longitude     | Geographic longitude              |

### Product Hierarchy Columns

| Column            | Description                   |
|-------------------|-------------------------------|
| Product_Family    | Plant family (e.g. Rosaceae)  |
| Product_Group     | Product group                 |
| Product_Name      | Full product name             |
| Product_Size      | Size category                 |
| Produt_Type       | Indoor / Outdoor / Landscape  |

---

## 📌 Key KPIs

| Metric              | Value          |
|---------------------|----------------|
| 💰 Total Sales       | $ 30.08M       |
| 📦 Total Quantity    | 1,242,744      |
| 📈 Average Sales     | $ 12,326       |
| 🌍 Countries Covered | 54             |
| 🏢 Total Accounts    | 1,744          |
| 🌿 Total Products    | 1,000          |

---

## 🔍 Key Insights

- **China dominates** account distribution with 551 accounts — the largest market by far, followed by Philippines (136) and Brazil (123).
- **Outdoor and Landscape** product types drive the majority of sales volume alongside Indoor plants.
- **Top plant families** include Asteraceae (106 products) and Fabaceae (70 products), representing the widest product range.
- **YTD vs PYTD** comparison reveals clear seasonal patterns, with performance dips in Q2 across multiple years.
- **2022–2024 growth trend** shows expanding geographic reach across 54 countries in Europe, Asia, and the Americas.
- **Gross Profit margins** tracked via GP% metric allow quick identification of high-margin vs low-margin product segments.

---

## 🎛️ Dashboard Features

- **Dynamic Slicer** — Switch between Sales, Quantity, and Gross Profit views instantly
- **KPI Cards** — YTD, PYTD, YTD vs PYTD, and GP% at a glance
- **S_YTD by Country** — Treemap showing geographic sales distribution
- **YTD vs PYTD by Month** — Waterfall chart showing monthly performance vs prior year
- **S_YTD & S_PYTD by Quarter & Product Type** — Stacked bar with line overlay for Indoor/Outdoor/Landscape
- **Account Profitability Segmentation** — Scatter plot of GP% vs Sales per account
- **Year Slicer** — Filter entire dashboard by year

---

## 🛠️ Tools & Technologies

| Tool                      | Usage                              |
|---------------------------|------------------------------------|
| Microsoft Power BI Desktop | Dashboard development & DAX measures |
| Microsoft Excel (.xls)    | Source data                        |
| Power Query               | Data cleaning & transformation     |
| DAX                       | YTD, PYTD, SWITCH, InPast measures |

---

## 📄 License

This project is for educational and portfolio purposes.  
Dataset is used for academic/non-commercial analysis only.

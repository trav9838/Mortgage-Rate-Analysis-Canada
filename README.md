# Canadian Mortgage Rate Analysis (2000–2024)

📊 **Project Summary**

This Excel-based project analyzes the trends and relationships between:
- 🏦 Bank of Canada policy interest rates
- 🏡 Conventional 5-year mortgage lending rates
- 📈 Consumer Price Index (CPI) inflation
- 🗳️ Federal political party in power

Over a 25-year period (2000–2024), the dashboard provides a comprehensive view of rate dynamics, policy effects, and macroeconomic factors in Canada.

---

## 📁 Files Included

- `data/Mortgage_Rate_Analysis_Canada.xlsx` — Cleaned and structured Excel file with all visuals and pivot tables
- `images/dashboard_preview.png` — Visual dashboard summary (with sparklines, slicers, party breakdowns)

---

## 🧠 Dashboard Highlights

| Feature | Description |
|---------|-------------|
| 📉 Sparklines | Monthly mortgage rate trends per year |
| 🟧 Symbol Bars | Yearly policy rate changes |
| 📊 Interactive Filters | Year & Political Party slicers |
| 📈 Overlayed Chart | Mortgage vs. Policy Rate vs. CPI |
| 🗳️ Pivot Tables | Party-wise average rate comparison |

---

## 🔍 Key Insights

- Mortgage rates tend to lag behind Bank of Canada’s policy rate decisions
- CPI spikes (2021–2022) triggered sharp policy rate hikes
- Political leadership may correlate with rate levels — e.g., Liberal years had slightly higher mortgage rates on average

---

## 🔧 Tools & Excel Techniques Used

This project leverages a wide range of **advanced Excel capabilities**, demonstrating both data manipulation and visualization proficiency:

### 📐 Functions & Formulas
- `YEAR()` — to extract the year from monthly `REF_DATE`
- `AVERAGEIFS()` — to calculate annual averages based on multiple conditions
- `FILTER()` (Excel 365) — to dynamically extract monthly data per year
- `TRANSPOSE()` — used in combination with `FILTER()` to reshape data for sparkline input
- `INDEX()` + `MATCH()` — for assigning political parties to each month based on term ranges
- `VLOOKUP()` — for aligning macroeconomic indicators by year (e.g., inflation, GDP)

### 📊 Visualization Techniques
- **Sparklines** — line-type sparklines for visualizing intra-year mortgage rate trends
- **Data Bars & Symbol Columns** — conditional formatting to show rate changes and inflation comparisons
- **Pivot Tables** — used for grouped summaries by political party and year
- **Slicers & Timelines** — enabling interactive filtering by political party and year
- **Combined Line & Column Charts** — showing overlay of policy rate, mortgage rate, and CPI

### 🧱 Structure
- Modular sheets separating raw data, cleaned data, and dashboard views
- Dynamic name ranges and non-destructive formatting practices
- Fully refreshable dashboard (no hardcoded values)


---

## 📷 Dashboard Preview

<table>
  <tr>
    <td align="center">
      <img src="images/mortgage_dashboard_summary.png" width="380"/>
      <br/>
      <strong>📊 Mortgage Dashboard Summary</strong><br/>
      Yearly mortgage rates, monthly sparklines, BoC policy changes & CPI inflation.
    </td>
    <td align="center">
      <img src="images/mortgage_rate_by_party.png" width="360"  height="460">
      <br/>
      <strong>🏳️ Party Comparison</strong><br/>
      5-Year mortgage rates under Liberal vs Conservative governments.
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="images/rate_trends_mortgage_policy_inflation.png" width="380"/>
      <br/>
      <strong>📈 Trend Line Chart</strong><br/>
      Mortgage rates vs BoC policy rates vs inflation (2000–2024).
    </td>
    <td align="center">
      <img src="images/dashboard_filters_and_interaction.png" width="380"/>
      <br/>
      <strong>🧩 Dashboard Filters</strong><br/>
      Slicers and timeline for political party and year-based filtering.
    </td>
  </tr>
</table>


---

## 📬 Contact

If you have feedback or want to collaborate on more economic data projects, feel free to connect via GitHub or LinkedIn!

# Financial Projection: Kids' Coding School, Yangon

This project is an **interactive financial feasibility study and strategic plan** for opening a kids' coding school in Yangon, Myanmar. The study evaluates two potential locations—**Taw Win Center** and **Time Link Condo**—using detailed financial modeling, scenario analysis, and visual dashboards.

## Project Overview

The application presents a comprehensive, interactive summary of the business plan, including:

- **Key Metrics Dashboard:** Compare Initial Investment, Payback Period, ROI, NPV, IRR for both locations.
- **Location Financials:** Detailed breakdown of setup costs, operational expenses, and revenue projections for each location.
- **Comparative Analysis:** Side-by-side review of financial and strategic factors.
- **Financial Projections & KPIs:** Visualizations of 5-year profit & loss, cash flow, and other key investment metrics.
- **Sensitivity Analysis:** Shows the impact of changes in assumptions (student numbers, fees, expenses).
- **Conclusions & Recommended Next Steps:** Actionable guidance for moving forward.

All financials are in Myanmar Kyat (MMK) unless stated otherwise. The study uses an exchange rate of $1 USD = 4500 MMK and assumes an 8% annual MMK inflation rate.

## How It Works

The `index.html` provides an interactive dashboard with the following technologies:

- **Tailwind CSS** for responsive, modern UI
- **Chart.js** for interactive charts and data visualization
- Plain JavaScript for dynamic content/tab navigation

All data and calculations are client-side for rapid exploration and comparison.

## Key Financial Findings

- **Time Link Condo** is recommended due to its:
  - Lower initial capital requirement (by over 10 million MMK)
  - Faster payback period (2.20 years vs. 2.85)
  - Higher IRR (87.0% vs. 69.8%) and 5-year average ROI (138.5% vs. 115.8%)
- **Taw Win Center** offers slightly higher average annual net profit but at higher upfront risk.

## Project Structure

```
financial_projection/
└── index.html   # Main interactive report and dashboard
```

## Usage

1. **Open `index.html` in your web browser.**
2. Use the navigation tabs to explore each section of the report—no backend required.

## Features

- Interactive scenario toggles for "Realistic", "Pessimistic", and "Optimistic" revenue cases.
- Automated charts for all major financial indicators.
- Detailed cost tables and sensitivity summaries.
- Actionable recommendations and next steps for business setup.

## Customization

To adapt the financial model for other school types, locations, or currencies:
- Update the corresponding data arrays and variables in the `<script>` section of `index.html`.

## License

This project is released under the MIT License.

---

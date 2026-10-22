# Marketing Campaign Performance Dashboard | Tableau

## Project Overview

The **Marketing Campaign Performance Dashboard** is a data analytics project built using Tableau to evaluate marketing campaign effectiveness across different channels and campaigns.

The dashboard analyzes marketing spend, conversions, attributed revenue, return on ad spend (ROAS), click-through rate (CTR), and cost per conversion. It helps users compare channel performance, identify high-performing campaigns, and understand how marketing budgets relate to recorded business outcomes.

This project uses a synthetic, analysis-ready marketing dataset covering 2023–2025. It is designed as a portfolio case study to demonstrate practical data analysis and business intelligence skills.

## Business Problem

Marketing teams need to understand whether their advertising spend is generating measurable results. Spending more does not necessarily mean generating more revenue or conversions.

This project addresses the following business questions:

- Which marketing channels generate the highest attributed revenue?
- Which campaigns deliver the strongest return on ad spend?
- How does marketing spend change over time?
- Which channels have the lowest cost per conversion?
- How do conversions and revenue compare with advertising spend?
- How can campaign performance metrics support better budget allocation decisions?

## Project Objectives

- Analyze marketing performance across channels and campaigns.
- Compare advertising spend with attributed revenue and conversions.
- Calculate important marketing performance indicators.
- Identify performance trends over time.
- Build an interactive Tableau dashboard for business reporting.
- Present insights in a clear, decision-oriented format.

## Tools and Technologies

- **Tableau Desktop:** Data visualization, calculated fields, and interactive dashboards.
- **Microsoft Excel:** Analysis-ready dataset and data source.
- **GitHub:** Project documentation, version control, and portfolio presentation.

## Dataset

The project uses the analysis-ready Excel workbook from the Marketing Campaigns dataset provided by Analytics Engineering.

- **Coverage:** 2023–2025
- **Data type:** Synthetic marketing campaign data
- **Source:** [Marketing Campaigns Dataset](https://www.analyticsengineering.com/datasets/marketing-campaigns)
- **License:** CC BY 4.0, as stated by the dataset provider

The workbook combines campaign data into a reporting-friendly structure. The exact field names may vary depending on the workbook version.

Key fields used in the analysis include:

| Field | Description |
|---|---|
| Date | Date of the marketing activity |
| Campaign | Marketing campaign identifier or name |
| Channel | Marketing channel |
| Spend | Advertising expenditure |
| Impressions | Number of times an advertisement was displayed |
| Clicks | Number of advertisement clicks |
| Conversions | Recorded conversions |
| Attributed Revenue | Revenue attributed to marketing activity |

## Key Performance Indicators (KPIs)

The dashboard uses the following metrics to evaluate campaign performance.

### 1. Total Marketing Spend

The total advertising expenditure across the selected reporting period.

**Formula:** Total Spend = SUM(Spend)

### 2. Total Conversions

The total number of recorded conversions.

**Formula:** Total Conversions = SUM(Conversions)

### 3. Total Attributed Revenue

The total revenue attributed to marketing activity.

**Formula:** Total Revenue = SUM(Attributed Revenue)

### 4. Return on Ad Spend (ROAS)

Measures the attributed revenue generated for each unit of advertising spend.

**Formula:** ROAS = Total Attributed Revenue / Total Spend

A higher ROAS indicates more attributed revenue per unit of spend, although profitability also depends on product costs and other expenses.

### 5. Cost per Conversion

Measures the average advertising spend required to generate one recorded conversion.

**Formula:** Cost per Conversion = Total Spend / Total Conversions

A lower cost per conversion can indicate greater acquisition efficiency when comparing similar campaigns and conversion types.

### 6. Click-Through Rate (CTR)

Measures the percentage of impressions that resulted in clicks.

**Formula:** CTR = Total Clicks / Total Impressions × 100

These metrics are calculated using aggregated totals to support consistent reporting.

## Dashboard Features

The Tableau dashboard includes the following analytical views:

### Channel Performance
Compares marketing spend and attributed revenue across channels to understand differences in expenditure and recorded revenue.

### Monthly Trend
Tracks marketing spend and attributed revenue over time to identify changes and potential trends.

### Campaign Ranking
Ranks campaigns by ROAS to help identify campaigns with stronger attributed revenue relative to spend.

### Cost per Conversion
Compares acquisition costs across channels and provides context through conversion counts.

### KPI Cards
Summarizes total spend, total conversions, total attributed revenue, and overall ROAS.

### Interactive Filters
Allows users to explore the dashboard by relevant dimensions such as date and channel, where supported by the workbook.

## Methodology

1. Connected the analysis-ready Excel workbook to Tableau.
2. Reviewed the available fields and their data types.
3. Created calculated fields for ROAS, cost per conversion, and CTR.
4. Built individual worksheets for channel performance, monthly trends, campaign ranking, conversion cost, and KPIs.
5. Combined the worksheets into an interactive dashboard.
6. Checked aggregations and calculations to ensure that overall ratios were calculated from aggregated totals.
7. Reviewed the dashboard to identify useful performance comparisons and trends.

## Business Value

This dashboard demonstrates how marketing performance data can be transformed into a visual reporting solution.

It supports:

- Comparing channels using revenue, spend, and efficiency metrics.
- Evaluating campaigns based on attributed revenue relative to expenditure.
- Monitoring monthly performance changes.
- Identifying campaigns that may need further investigation.
- Supporting data-informed marketing budget discussions.

The dashboard provides analytical evidence for decision-making rather than automatically recommending that a particular campaign should receive more or less budget.

## Key Findings

**Add your actual findings after reviewing your completed dashboard.**

Use this section to document:

- The channel with the highest attributed revenue.
- The campaign with the highest ROAS.
- The channel with the lowest cost per conversion.
- Any notable monthly changes in spend or revenue.
- Any campaigns with high spend but comparatively weak results.

Do not enter findings until you have verified the values in Tableau. Results may differ depending on the dataset and applied filters.

## Project Limitations

- The dataset is synthetic and does not represent verified company performance.
- Revenue attribution does not establish that marketing activity caused a conversion.
- Last-touch attribution assigns credit according to the dataset's attribution methodology and does not capture the full customer journey.
- ROAS measures attributed revenue relative to advertising spend; it is not the same as profit or overall business ROI.
- Campaign comparisons should account for differences in conversion definitions, audience, and campaign objectives.

## Project Structure

Organize the GitHub repository as follows:

```text
marketing-campaign-performance/
│
├── data/
│   └── marketing_campaigns.xlsx
│
├── dashboard/
│   └── marketing_campaign_performance.twbx
│
├── screenshots/
│   └── marketing_dashboard.png
│
└── README.md
```



## Future Improvements

- Add campaign-level profitability analysis if suitable cost data becomes available.
- Add year-over-year comparisons and more advanced time-series analysis.
- Include additional audience and conversion-segment analysis where supported by the dataset.
- Develop a SQL-based version to demonstrate data preparation and analytical querying.
- Improve dashboard usability with parameter controls, detailed tooltips, and additional drill-down views.



*This project was developed for learning and portfolio demonstration. All findings should be interpreted in the context of the synthetic dataset and its attribution limitations.*

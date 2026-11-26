# Amazon India Sales Performance Dashboard

An interactive, responsive business intelligence dashboard built from the supplied **Amazon Sales Data India.xlsx** workbook and aligned with the Sapphire IQ dashboard brief.

## Dashboard sections
- Overall sales and profit performance: sales, profit, orders, units, AOV and profit margin
- Monthly sales and profit trends (date-window control)
- Category and top-10 product performance
- Order status: delivered, shipped, returned and cancelled
- Payment and fulfilment mix
- State-wise sales and profit

## Dataset
- 10,000 order records
- Date range: 1 January 2024 – 30 August 2026
- Currency: INR
- Source workbook: Amazon Sales Data India.xlsx

## Key figures
- Total sales: ₹15,57,89,893.89
- Total profit: ₹3,31,67,008.49
- Orders: 10,000
- Units sold: 24,926
- Average order value: ₹15,578.99
- Profit margin: 21.29%

## Run locally
Open `index.html` in a modern browser. Plotly is loaded from its CDN, so an internet connection is required for charts.

## Deploy
This repository includes a GitHub Actions workflow that publishes the site to GitHub Pages on pushes to `main`. In repository Settings → Pages, select **GitHub Actions** as the build and deployment source if it is not already selected.

## Important data interpretation
The workbook does not contain separate refund amounts, shipping costs or cancellation reasons. Returned/cancelled sales are shown as operational status indicators, not confirmed cash losses. The summary KPIs and breakdowns represent the full dataset; the date controls adjust the monthly trend window.

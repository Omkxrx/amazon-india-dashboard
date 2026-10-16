# Amazon India Dashboard — SAPPhIRE IQ Project

This repository contains an Excel dashboard built from the supplied Amazon Sales Data India dataset and the SAPPhIRE IQ project requirements.

## Files
- `Amazon_India_Dashboard_Completed.xlsx` — workbook with Dashboard, Data, and Analysis sheets.
- `Amazon Sales Data India.xlsx` — original supplied source dataset.

## Dashboard coverage
1. Overall sales and profit performance: total sales, total profit, orders, units sold, average order value, profit margin, monthly sales and profit.
2. Category and product performance: category sales, profit, units sold, top 10 products by sales.
3. Order status and revenue loss: delivered, shipped, returned, cancelled orders; return and cancellation rates; category-wise returns and cancellations.
4. Payment, fulfillment and geography: sales and profit by payment method; sales and profit by fulfillment method; state-wise sales, profit and orders.

## Notes
- Figures are calculated from the supplied dataset; they should not be represented as verified real-world Amazon company results.
- Order-status rates are calculated as each status's unique Order_ID count divided by total unique orders.
- The workbook contains summary charts and analysis tables. If the source dataset changes, refresh/rebuild the summaries before using the results.

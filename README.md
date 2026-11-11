# Apocalypse Food Prep Sales Dashboard (Power BI)
## Project objective
A fictional store selling apocalypse food-prep products, with its sales, products and customers


## Questions

- Which products sell the most units?
- Which customers buy the most, and which products do they buy?
- How do sales change over time (by month and day)?
- How does each product's production cost compare with its price (profitability)?
- Do high-selling products also carry high production costs?
- Which states generate the most purchases?
- What are the overall purchase totals: the total, the count of purchases, and the smallest purchase?

## Dashboard: https://github.com/mansur58/Power-BI-project/blob/main/Screenshot%202026-11-10%20214226_edited.png

## Process
1.Import. Four sheets were pulled in from Excel with Power Query. Headers were promoted and data types set (integers, text, dates).
2.1Model. The tables link through Product ID, Customer ID and Order ID. Sales connects to products and customers, and the buyer table connects to customers.
3.Visualize. Each question above got a visual:
  -Units sold by customer, split by product (column chart).
  -Units sold over time (line chart).
  -Units sold versus production cost by product (column chart).
  -Price versus production cost by product (scatter).
  -Units sold by product (bar chart).
  -Purchases by state (donut chart).
  -Four KPI cards on Total Purchased: sum, count and minimum.
  -A customer and units-sold table.

## Insights

- **Product performance:** Comparing units sold with production cost shows which products sell well but are costly to make.
- **Pricing:** The scatter chart shows which products have a healthy gap between price and production cost.
- **Customer concentration:** The customer chart and table show whether a few customers drive most of the volume.
- **Trend:** The line chart can reveal seasonality or spikes in demand.
- **Geography:** The donut chart shows which states account for the largest share of purchases.

## Final Conclusion

This project shows a complete Power BI workflow: importing four related datasets from Excel, cleaning them in Power Query, modelling them, and presenting them in an eleven-visual dashboard. The report shows which products, customers and states drive sales, how demand changes over time, and how production cost compares with price.
It is a strong foundation. Consolidating the duplicate tables, adding profit and margin measures, and adding slicers would turn it into a fuller decision-support tool. Overall, it shows solid skills in data preparation, modelling and visualization.


## Dashboard
<img width="1142" height="645" alt="image" src="https://github.com/user-attachments/assets/fb63dcff-8eb7-4a35-8678-4e6dfe7f4412" />

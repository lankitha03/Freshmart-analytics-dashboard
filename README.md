# Lanka Fresh Mart Sales Dashboard (Power BI)

An interactive Power BI dashboard that analyses sales, profit and cost for Lanka Fresh Mart, a supermarket chain with 8 branches across Sri Lanka. The goal is to find which products, categories, branches and provinces make money, where costs are highest, and what the business should do next.

## Business Questions
- How much does the business sell, and how much does it earn?
- Which products and categories bring the most profit?
- Which branches and provinces drive profit and cost?
- When are sales and costs highest?
- Does delivery time affect cost?

## Key Numbers

| Measure | Value |
|---|---|
| Net Sales | 11M |
| Total Cost | 9M |
| Profit | 2M (2,123,946) |
| Profit Margin | about 19% |
| Quantity Sold | 17K |
| Discount Amount | 280K |

## Dashboard Pages

### 1. Dashboard (Overview)
KPI cards, profit by product, net sales by year and product, monthly net sales vs profit, and total cost by province.

![Dashboard](images/dashboard.png)

### 2. Profit Analysis
A decomposition tree (District > Branch > Product > Loyalty Tier), profit by year and product, and a donut chart of profit share by category.

![Profit Analysis](images/profit-analysis.png)

### 3. Cost Analysis
Total cost vs gross sales by branch, total cost by quarter, delivery days vs cost by branch and category, and a cost decomposition tree.

![Cost Analysis](images/cost-analysis.png)

## Key Findings
- **Profit margin is about 19%.** Net sales of 11M gave 2M profit after 9M cost, so cost takes about 81% of every sale. Small cost savings make a big difference.
- **Sales grow through the year, but profit stays flat.** Net sales are lowest in January, rise in April, and reach their highest point in December (about 1.5M), while monthly profit barely moves.
- **Beverages earn the most profit.** It brings 408K (19.2% of profit), followed by Household (318K) and Personal Care (301K). Fresh Produce, Dairy and Bakery bring the least (about 9% each).
- **Body Lotion 400ml is the top profit product**, while Samba Rice 5kg is the lowest of the top 10.
- **Colombo district carries the business.** It earns about 796K, around 37% of total profit.
- **Western Province takes about 50% of total cost.** The other five provinces each take between 6.5% and 14%.
- **Costs fall from Colombo 07 down to Jaffna.** Colombo 07 has the highest cost and Jaffna the lowest, which follows branch size.
- **Costs peak in Quarter 2 and Quarter 4** (about 2.5M and 2.7M), compared with about 1.8M in Quarter 1.
- **Delivery days and cost rise together**, but this is probably because busy branches and categories have more orders, not because slow delivery costs more.

## Recommendations
1. **Protect and grow Beverages.** It is the largest profit maker, so promotions and good stock here pay off most.
2. **Review costs in high-volume products.** Profit stays flat while sales grow, so check supplier prices and discounts.
3. **Learn from Colombo 07 and Colombo district.** Find what works (location, stock, customers) and copy it in the smaller branches.
4. **Plan ahead for April and December.** Stock up and add staff before the peaks.
5. **Watch Quarter 2 and Quarter 4 costs.** Check whether costs grow faster than sales in those quarters.
6. **Look at Western Province costs.** Half of all cost sits in one province, so small savings there have a large effect.

## Tools Used
- Power BI (dashboard and visuals)
- DAX (measures such as profit)
- Excel (data source)

## How to Open
1. Download `lanka-fresh-mart-dashboard.pbix` from this repository.
2. Open it in Power BI Desktop.
3. Use the arrow buttons to move between pages.

## Author
**[Your Full Name]**
Business Analytics Undergraduate, NSBM Green University
[LinkedIn link]

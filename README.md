# Superstore-Sales-Analysis

## 1. Shipping Mode Analysis

<img src="https://github.com/user-attachments/assets/6958e374-3235-41f3-97b3-a027d6eec068" alt="Sheet 2 (1)" height="400px">

- Majority customers choose **Standard Class** (≈60%).
- Likely due to lower cost.
- Notable: First Class and Same Day together are ~20%.

## 2. Customer Segment Distribution

<img src="https://github.com/user-attachments/assets/3ba1ad90-baf9-4b78-889f-607db97c9849" alt="Sheet 2 (2)" height="200px">

- Consumer: 52%
- Corporate: 30%
- Home Office: 18%

## 3. Regional Analysis
- West leads in shipment volume (32%).
- South is lowest (16%).
- Distribution is not even — ideal would be 25% each.

## 4. Product Category Insights
- Office Supplies dominate at 60%.
- Furniture and Tech come next.

## 5. Sub-category Breakdown
- Binders, Paper, and Furnishings are top 3.
- "Others" combine many small-volume categories.

## 6. Shipping Category
- 40% of shipments are **Late** — a problem.
- Recommend investigation into vendors or processes.

## 7. Sales Segment by State
- ~80% of sales are **Normal Sales**.
- No "Low Sales" category — positive outcome.

## 8. Region-wise Shipping Speed
(Include matplotlib/seaborn bar plots)
- West leads in both **Late** and **Fast** shipments.
- Patterns suggest similar distribution regardless of speed.

## 9. Shipping Mode vs Category
- All **Late** shipments are from **Standard Class**.
- However, **Second Class** is appearing across all categories.
  - Needs investigation — Second Class should rarely be late.
  - Consider dropping Second Class if no difference from Standard.

## 🔍 Conclusion
Focus points:
- Reduce Late Shipping (esp. Standard and Second Class).
- Balance region-wise operations.
- Optimize resource allocation toward Office Supplies and Consumer segment.

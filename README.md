# Walmart Sales Data Analysis (Databricks)

## 📋 Project Overview
This project analyzes 10,000 Walmart transaction records to uncover sales trends, peak traffic times, and branch performance. 

## 🛠️ Technical Challenges & Solutions
* **Currency Formatting:** Handled malformed strings like `$99.7` using PySpark Regex `[\\$,]` to enable mathematical operations.
* **Schema Resolution:** Fixed `[CANNOT_INFER_EMPTY_SCHEMA]` by optimizing the data loading sequence.
* **Advanced SQL:** Used Window Functions (RANK) and CTEs to identify top-performing categories per city.

## 📊 Key Insights
* **Top Payment Method:** [Insert Result]
* **Peak Revenue Day:** [Insert Result]
* **Monthly Trend:** [Insert Result]
  
## 📊 Analytical Questions Answered
I used Spark SQL to answer the following 8 business questions:

1. **Most common payment method:** Identified which payment system is used most frequently by customers.
2. **Highest selling category:** Determined which product line moves the highest unit volume.
3. **Monthly Revenue:** Generated a month-by-month sales performance report.
4. **City Rankings:** Identified the city with the highest average customer satisfaction rating.
5. **Branch Profitability:** Calculated total profit per branch (Branch A, B, and C).
6. **Peak Traffic Days:** Found which day of the week generates the highest sales volume.
7. **Top Category per City:** Used Window Functions to find the best-rated category in every location.
8. **Revenue Growth/Decrease:** Calculated the Year-over-Year (YoY) performance ratio to find declining trends.
---
🔗 **[View Interactive Notebook](./your_filename.html)**

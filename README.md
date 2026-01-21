# Payment Data Analysis (July–September 2025)

## Project Overview
This project analyzes payment data from July to September 2025 to monitor payment trends, on-time payments, late payments, and partial payments. The goal is to generate actionable insights for better cash flow management and customer follow-ups.  

**Tools Used:**  
- Power BI for data analysis and visualization  
- Excel as the source data  
- GitHub for documentation  

---

## Data Preparation
- **Source:** Excel file with 3 sheets (July, August, September)  
- **Transformations:**  
  - Combined all sheets into a single table  
  - Replaced null values in `payment_date` with 15/07/2025 in July, 16/08/2025 in August, and 19/09/2025 in September.   
  - Standardized column names: `Amount Due`, `Amount Paid`, `Payment Date`, `Status`  

**Screenshot of Power Query:**  
![Power Query Transformation](screenshots/powerquery.png)  

---

## Metrics & Insights

### 1. Total Payments per Month
**Visualization:** Bar/line chart in Power BI  
**Insight:** July's total payments were lower compared to August and September.  

![Total Payments per Month](screenshots/total_payments.png)  

### 2. Payment Status Analysis
**Visualization:** Pie chart / Stacked bar chart  
**Insight:** Partial payments increased in September, indicating potential follow-up needs.  

![Payment Status Analysis](screenshots/payment_status.png)  

### 3. Top Customers / Paid Amount Trend
**Insight:** Identify customers with frequent late payments or highest total paid amounts.  

![Top Customers Trend](screenshots/top_customers.png)  

### 4. Late Payments (>10 days)
**Visualization:** KPI card or conditional formatting  
**Insight:** Late payments may impact cash flow planning; identify high-risk accounts.  

![Late Payments KPI](screenshots/late_payments.png)  

---

## Conclusion & Recommendations
- Follow up with customers with partial or late payments  
- Set reminders for upcoming payments before due dates  
- Monitor monthly trends to improve cash flow forecasting  


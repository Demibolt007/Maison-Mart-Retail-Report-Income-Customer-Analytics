# Maison Mart Retail Report: Income & Customer Analytics

This project delivers a detailed Power BI analysis of income performance, product movement, and customer behaviour for a retail e-commerce business. The insights span trends in sales, customer loyalty, top-selling products, and regional performance — enabling data-driven recommendations for business optimisation.

![Analysis+Boards](https://github.com/user-attachments/assets/a5f96327-3429-43e6-8d8e-7abd1ddb4450)

##  Project Details

- **Project Title:** Maison Mart Retail Report — Income & Customer Analytics  
- **Tool Used:** Microsoft Power BI  
- **Dataset Source:** [Kaggle – E-Commerce Dataset](https://www.kaggle.com/datasets/carrie1/ecommerce-data)  
- **Period Covered:** December 2010 – December 2011  
- **Repository Link:** [GitHub Repository](https://github.com/Demibolt007/Maison-Mart-Retail-Report-Income-Customer-Analytics)

---

##  Objectives of the Analysis

- Track and evaluate monthly sales revenue trends.
- Identify top-performing products and customers by revenue and quantity.
- Understand customer purchase behaviour and loyalty.
- Reveal geographic distribution of sales and quantity sold.
- Highlight peak shopping days and hours.
- Assess order fulfilment efficiency (cancelled vs successful).

---

##  Data Preprocessing Steps

- Removed cancelled orders (Invoice numbers starting with "C").
- Eliminated rows with missing `CustomerID` values.
- Filtered out rows with StockCodes like "POST", "S", and "M" (postage, samples, manuals).
- Removed transactions with zero or negative quantity and unit price.
- Split `InvoiceDate` into separate columns for Date, Month, Year, and Hour.
- Created calculated fields:
  - **Total Sales** = Quantity × Unit Price
  - **Customer Type** = New or Repeat (based on unique Invoice counts)
  - **Order Status** = Cancelled or Successful

---

##  Dashboard Overview

###  Page 1: Revenue & Customer Performance

**KPI Cards**
- Total Revenue: £8.91M  
- Total Unique Customers: 4,339  
- Total Quantity Sold: 5.18M  
- Total Invoices Issued: 18.54K  

**Visuals**
- Sales Trend (Monthly)
- Sales by Day of the Week
- Top 5 Products by Revenue
- Top Customers by Revenue
- Sales by Country

###  Page 2: Quantity & Behavioural Insights

**Visuals**
- Top 5 Products by Quantity Sold
- Quantity Sold by Country
- Quantity Sold by Day of the Week
- Repeat vs New Customers (Donut Chart)
- Orders by Hour and Day (Heatmap)
- Cancelled vs Successful Orders (Bar Chart)
- Top Customers by Quantity Purchased

---

##  Key Insights

### Sales & Revenue
- **Peak Month:** November 2011 (£1.16M), followed by October 2011.
- **Decline:** December 2011 revenue fell below December 2010, suggesting a seasonal dip or issue.

### Product Performance
- **Top Product (Revenue):** *Paper Craft, Little Birdie* — £168.75K
- **Top Product (Quantity):** *Paper Craft, Little Birdie* — 81K units

### Customer Loyalty
- **Repeat Customers:** 91.57%
- **New Customers:** 8.43%
- Strong retention, but a narrow acquisition funnel.

### Operational Efficiency
- **Successful Orders:** 98.29%
- **Cancelled Orders:** 1.71%
- Excellent fulfilment and stock handling rate.

### Geography
- **UK:** £7.3M in sales and 4.2M items sold.
- **Other top countries:** Netherlands, Germany, EIRE, and France.

---

##  Recommendations

- **Boost New Customer Acquisition**: Launch referral campaigns or targeted ads to expand reach.
- **Explore Saturday Sales Opportunity**: No transactions were recorded on Saturdays — investigate potential platform or operational limitations.
- **Double Down on High-Movers**: Products with high quantity movement but lower revenue may benefit from bundling or upselling.
- **Strengthen International Strategy**: Scale marketing and fulfilment in high-performing non-UK countries.
- **Retain Top Customers**: Personalised loyalty or incentive programmes for top buyers like Customer ID 14646.

---

##  Conclusion

This analysis showcases the power of clean transaction data in uncovering customer patterns and revenue opportunities. With high customer retention and clear product winners, the business is well-positioned to scale. The insights offer a path for enhanced decision-making in marketing, inventory, and fulfilment operations.

---

##  References & Resources

- Dataset: [Kaggle – E-Commerce Dataset](https://www.kaggle.com/datasets/carrie1/ecommerce-data)
- GitHub Repository: [Maison Mart Retail Report](https://github.com/Demibolt007/Maison-Mart-Retail-Report-Income-Customer-Analytics)
- Power BI Desktop

---

##  About the Analyst

**Oluwademilade Adeniyi**  
Junior Data Analyst | Power BI & Excel Specialist  
- [LinkedIn](https://www.linkedin.com/in/adeniyioluwademilade)  
- [Twitter](https://twitter.com/iamdemibolt)  
- Email: adeniyioluwademilade@gmail.com  

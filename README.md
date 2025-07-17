# TransBorder-Freight-Data-Analysis
The objective of this project is to analyze the transportation data provided by the Bureau of Transportation Statistics (BTS) to uncover insights related to the efficiency, safety, and environmental impacts of freight transportation across various modes (road, rail, air, and water). Using this data, the goal is to identify inefficiencies, recognize patterns, and propose actionable solutions to improve the overall performance and sustainability of transportation systems.





##  Project Details

- **Project Title:** TransBorder-Freight-Data-Analysis Report   
- **Tool Used:** Microsoft Power BI  
- **Dataset Source:**  
- **Period Covered:** January 2020 – September 2024  (Dataset has October 2020 - December 2020 missing)

---

##  Objectives of the Analysis

- Uncover Freight Movement Patterns.
- Identify Operational Inefficiencies.
- Analyze Environmental Impact.
- Safety and Risk Assessment.
- Economic Disruptions.
- Provide Data-Driven Recommendations.

---

##  Data Preprocessing Steps

- Extract and combine csv data files into a folder for import into PowerBI.
- Transform value coded categorical columns. Eg. `MONTH` values of 1 into January, 2 into February, etc.
- Created calculated fields:
  - **Total Value of goods Transported** = Sum(Values)
  - **Number of Transportations** = Count(Transportation modes)

---

##  Dashboard Overview

###  Page 1: Revenue & Customer Performance

**KPI Cards**
- Total Value Transported: $108.9T  
- Number of Freight Transported: 39M  
 

**Visuals**
- Mode of Transportation by Value
- Trend of Value by Year
- Shipping weight by Month and Country 
- Value by USA State and Mode of Transportation

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

**Isaac Owusu Akowuah**  
Data Analyst | Power BI Developer | Power BI & Excel Specialist  
- [LinkedIn](https://www.linkedin.com/in/adeniyioluwademilade)  
- [Twitter](https://twitter.com/demibolt_)  
- Email: ioakowuah@gmail.com  






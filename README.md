# MTN-Analysis

## Table of Contents

- [Data Description](#dataset-description)
- [Content](#content)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Inference Analysis](#inference-analysis)
- [Findings](#findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [Conclusion](#conclusion)

### Dataset Description(Overview)
An international MTN company in Nigeria specializing in tele communication service is on a quest to extract pivotal insights from their customer database. Their approach involves the application of a Data Analyst to scrutinize and understand their diverse customer base, in efforts to enhance their operations and sales strategies.

### Content
 The dataset comprises 19,500 observations across 17 variables, each illuminating different facets of the company's operations and customer interactions:

- Customer ID: Customer identification number.
- Full Name: The Costumers Names
- Date of Purchase: Periodical Time Track Record
- Age: Costomers Age diffrience.
- State: The State records of each costumer.
- MTN Device: MTN Product for sales.
- Gender: Customer gender, categorized as Male and Female.
- Satisfaction Rate: Customers sactisfaction rate.
- Customer Review: categorized as "poor,fair, good, excellent and very good"
- Customer Tenure in months.
- Subscription Plan: The product unit and diffrient packages of the company.
- Unit Price: The unit price.
- Number of Times Purchased: The count record of each sales.
- Total Revenue: Total amount of sales
- Data Usage: Data unit comsumtion by customers
- Customer Churn Status: The column contains the Active customers and Inactive Customers
- Goal: To assertain the reason why customers are having low ratings, why some are inactive and others customers are leaving for rivals.

### Data Sources

The data source is an Excel file (.xlsx) named "MTN_DATASET" which is gotten from techrative technology limited as a capstone project

### Tools:
 * Excel
 * Power Pivot for replacing the null value
 * Pivot Tabl for proper analylis.
 * Excel Dashboard for interactive visualizations
### Data Cleaning
* 1. Null/empty value check: 690 rows missing data detected.
* 2. Removal of the unneccesary null value and replacing the null value in column "Reason for chum" with Active for proper analysis.
* 3. Duplicate value check: no duplicates found.
* 4. The "Date of purchase" column is been split into Days, Month, and Year of purchase for proper analysis.
 
### Inference Analysis
  The analysis uses several techniques:
* 1. Clustered Column Chart: Analys the state with more customers.
* 2. Doughnut Chart: Analyzes the gender with more sales.
* 3. Clustered Column Chart: Examines the customers rating and review.
* 4. Pie of Pie: Analyzes the customers for all state.
* 5. 3-D culomn Chart: Examines the sub with more patronage and more decline base on location.
* 6. 3-D clustered culomn: Analys the device with the highest revenue base on relocation.
* 7. 3-D Stacked culomn: Shows the status of customer in each location.
* 8. 3-D Stacked culomn: Shows the location with the highest reveneu.
* 9. 3-D Stacked culomn: Analyzes the state with more revenue.
* 10.3-D Stacked Area: Show the month with the highest sales.
* 11.3-D culomn Chart: Analyzes the month with more decline customers.
* 12.3-D culomn Chart: Shows the period for higher revenue base on states.
 
### Findings
* The total revenue from January to March is N199,348,200
* The month with more declined customers is Febuary.
* The month with the lowest number of customers is march.
* The state with more customer is osun with 43% rgistered customers next to Abj with 42%.
* Females are the genger with more patronage with 50% compare to the males with 42.2%. 
* Product like 5G seems to have a low count on sales yet generate more revenue compare to sim.

### Recommendations
1. **Focus more on Osun**: The Osun state is the dominant mode and the results don't indicate a huge difference in the total revenue, There shoud be a proper investigation on the network provider in Osun perhaps a lower pakage for average customers in that region.

2. **Investigate low customer ratings:** Further analysis is needed to understand why "Sim" has more Poor rate and same time more Excellent, Explore customer feedback to identify areas for improvement. A deeper dive into the characteristics of customers giving low ratings might provide valuable insights.

3. **Product Importance Segmentation**:  Analyze the factors influencing "high importance" product classifications more closely.  If this category corresponds to 5G and 5G Broadband Router products, they may be experiencing a different set of challenges that warrant further investigation.

4. **Discount Optimization**: Understand the relationship between discounts and customer ratings. Test the impact of different discount strategies, potentially optimizing for higher ratings rather than just sales.
5. **Discount on 5G Router and Subscription**: There should be a distcount price on this set product in other to drive customers attention on them and increase the company's revenue.

### Limitations
1. **Lack of detailed customer feedback data**: Customer feedback would significantly enhance understanding of the rating distributions and offer targeted ways to improve customer satisfaction.

2. **Missing context on "high importance" Reasons for Churn**: More information is needed to identify any special activities on "Reasons for Churn".

### Conclusion
- The enitre distribution shows that 5G provives more revenue despite low sales.
- The sim product is overated against its service providing and revenue.
- sim network should considers an upgrade, Customer prefer using phone sim for browsing due to its convenience than to convey product that has great mass of weight.
- for some product to receive high product ratings from customers they need to step up the service provider.



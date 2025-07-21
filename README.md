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
An international MTN company in Nigeria that specialize in tele communication service is on a quest to extract pivotal insights from their customer database. Their approach involves the application of a Data Analyst to scrutinize and understand their diverse customer base, in efforts to enhance their operations and sales strategies.

### Content
 The dataset comprises 974,500 rows, observations across 17 variables, each illuminating different facets of the company's operations and customer interactions:

- **Customer ID**: Customer identification number.
- **Full Name**: The Costumers Names
- **Date of Purchase:** Periodical Time Track Record
- **Age**: Costomers Age diffrience.
- **State**: The State records of each costumer.
- **MTN Device**: MTN Product for sales.
- **Gender**: Customer gender, categorized as Male and Female.
- **Satisfaction Rate**: Customers sactisfaction rate.
- **Customer Review**: categorized as "poor,fair, good, excellent and very good"
- **Customer Tenure in months**: The time count record of each sales.
- **Subscription Plan**: The product unit and diffrient packages of the company.
- **Unit Price**: The unit price.
- **Number of Times Purchased**: The count record of each sales.
- **Total Revenue**: Total amount of sales
- **Data Usage**: Data unit comsumtion by customers
- **Customer Churn Status**: The column contains the Active customers and Inactive Customers.

### Data Sources

The data source is an Excel file (.xlsx) named "MTN_DATASET" which i got from techrative technology limited as a capstone project

### Tools:
 * Excel
 * Power Pivot for replacing the null value
 * Pivot Tabl for proper analysis.
 * Excel Dashboard for interactive visualizations
### Data Cleaning
* 1. Null/empty value check: 690 rows missing data detected.
* 2. Removal of the unneccesary null value and replacing the null value in column "Reason for chum" with Active for proper analysis.
* 3. Duplicate value check: no duplicates found.
* 4. The "Date of purchase" column is been split into Days, Month, and Year of purchase for proper analysis.
 
### Inference Analysis
  The analysis uses several techniques:
* 1. Clustered Column Chart: Analyzes the state with more customers.
* 2. Doughnut Chart: Analyzes the gender with more revenue.
* 3. Clustered Column Chart: Examines the customers rating and review.
* 4. Pie of Pie: Analyzes the customers for all state.
* 5. 3-D Column Chart: Examines the sub with more patronage and more decline base on location.
* 6. 3-D clustered Column: Analyzed the device with the highest revenue base on location.
* 7. 3-D Stacked Column: Shows the status of customer in each location.
* 8. 3-D Stacked Column: Shows the location with the highest reveneu.
* 9. 3-D Stacked Column: Analyzes the state with more revenue.
* 10.3-D Stacked Area: Show the month with the highest sales.
* 11.3-D Column Chart: Analyzes the month with more decline customers.
* 12.3-D Column Chart: Shows the period for higher revenue base on states.
 
### Findings
* The total revenue from January to March is N199,348,200
* Females are the gender with more patronage with 50% compare to the males with 42.2%.
* Out of 974 customers 690 where Active, while 284 stop patronizing the company, the top 5 reason for chum is “High Call Tarriffs” (54), “Better Offers from Competitors”(52), “Poor Network”(45), “Costly Data Plans”(40) and “Poor Customer Service”(34).
* “Ejiro Griffith” from Bauchi with a Broadband MiFi and other top rank customers  left the company  due to poor network
* “Tega Turner” from rivers is among the top 5 customers with a unit price of N150,000 he is currently active but has a poor data usage
* The month with more declined customers is Febuary.
* The month with the lowest number of customers is March.
* The state with more customer is osun with 43% rgistered customers next to Abj with 42%.
* Product like 5G have a low count on sales but generate more revenue compare to sim.
* The States with "Poor Customers Review" are “Akwa Ibom, Benue, Imo, Ekiti, Gombe, Enugu, Kongi, Nasarawa, Niger, Taraba and Sokoto”.
* The State with "Poor Network" are “Bauchi, Bauchi”.


### Recommendations
1. **Focus more on State with Poor Network issues**: There shoud be a proper investigation on the network provider in the above state with poor networt issues in order to generate more revenue.

2. **Lower package subscription concideration**: State like Osun which is the dominant mode in customers, the results don't indicate a huge difference in the total revenue, There shoud be a lower package for average customers in the company in other to speed up the total revenue.

3. **Product Discount**: There should be discount price on the product like 5G Broadband Router and 4G Router in other to drive customers attention on them and increase the company's revenue

4. **Product Importance Segmentation**:  Analyze the factors influencing "5G" product classifications more closely. this category corresponds to premium products, they may be experiencing a different set of challenges that warrant more attention perhaps an investigation.

5. **Discount Optimization**: Understand the relationship between discounts and customer ratings. Test the impact of different discount strategies, potentially optimizing for higher ratings rather than just sales.

6. **Investigate low customer ratings**: Further analysis is needed to understand why "Sim" has more Poor rate and same time more Excellent in "Customer Review", Explore customer feedback to identify areas for improvement. A deeper dive into the characteristics of customers giving low ratings might provide valuable insights.

### Limitations
1. **Lack of detailed customer feedback data**: Customer feedback would significantly enhance understanding of the rating distributions and offer targeted ways to improve customer satisfaction.

2. **Missing context on "Reasons for Churn"**: More information is needed to identify any special activities on "Reasons for Churn".

### Conclusion
- The entire distribution shows that 5G generate more revenue despite low count sales.
- The sim product is overrated against its service providing and revenue.
- sim network should considers an upgrade, Customer prefer using phone sim for browsing due to its convenience than to convey product that has great mass of weight.
- for some product to receive high product ratings from customers they need to step up the service provider.



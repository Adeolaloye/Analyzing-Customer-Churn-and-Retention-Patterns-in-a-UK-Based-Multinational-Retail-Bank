## Analyzing Customer Churn and Retention Patterns in a UK-Based Multinational Retail Bank
### Table of Content
- [Overview](#overview)
- [Business Challenge](#business-challenge)
- [Project Rationale](#project-rationale)
- [ Project Objectives](#project-objectives)
- [Data Dictionary](#data-dictionary)
- [Technology Stack ](#technology-stack)
- [Process](#process)
- [Key Recommendations and Actionable Insights](#key-recommendations-and-actionable-insights)
- [Conclusion](#conclusion)

### Overview
Veritas Bank is a UK-headquartered retail bank established in the 1990s with major operations across Germany and France. Over the past two decades, the bank has grown its customer base to over 3 million, focusing on core retail offerings such as savings accounts, personal loans, debit/credit card services, and online banking.
Headquartered in London, Veritas Bank is known for its technology-driven approach, with strong online banking capabilities and regional service hubs across continental Europe. The bank is strategically positioned in three countries—the UK (head office), Germany, and France—where it has tailored its services to meet local regulatory and customer behavior requirements.The primary goal was to analyse customer churn patterns across the UK, Germany, and France by identifying shared attributes among churned users, comparing behavioural metrics across regions, and segmenting customers based on churn risk. The project aimed to improve customer retention by developing data-driven insights and visualizations to guide targeted engagement.


 ![Screenshot 2025-06-10 184832](https://github.com/user-attachments/assets/fae4ebc4-7cc3-4ffb-8235-3a527d56e2ec)



![Screenshot 2025-06-16 161756](https://github.com/user-attachments/assets/01ef1cd3-c0e6-4ee8-ae55-cfdc66352b62)







###  Business Challenge
Veritas Bank is facing increased customer churn from its users. Retaining customers has become a growing challenge due to:
- Intense competition from neobanks and fintech startups
- Perceived decrease in customer engagement in Germany and France
- Lack of targeted retention strategies based on behavioral insights
- The absence of real-time churn monitoring and customer segmentation has made it difficult for the business to respond proactively.
### Project Rationale 
Customer churn, or attrition, is a key performance metric in banking. Understanding why customers leave and who is at risk allows businesses to reduce revenue loss and improve customer lifetime value.
#### Why This Project Matters:
##### 1. Data-Driven Retention:
Establish churn drivers based on account activity and demographics.
#### 2. Regional Optimization:
Understand and compare churn behavior between the UK, Germany, and France.
#### 3. Personalized Engagement:
Enable tailored offers for specific customer segments.
#### 4. Strategic Reporting: 
Equip leadership with visual dashboards to guide marketing and customer service policies.
#### 5. Optimize Customer Acquisition:
Identify the characteristics of customers most likely to churn to adjust acquisition strategies
###  Project Objectives
- Identify common characteristics among customers who have churned.
- Compare account behavior across the UK, Germany, and France.
- Segment customers based on risk profiles and account usage.
- Visualize key churn metrics via interactive dashboards for better decision-making
###  Data Dictionary
[Dowload Dataset here](https://drive.google.com/drive/folders/1LNHTPQlvgHBTXnxhiW9f2WARywlL62_I?usp=sharing)
- CustomerId: A unique identifier for each customer in the dataset.
- LastName: The surname (last name) of the customer.
- CreditScore: The credit score of the customer, representing their creditworthiness.
- Country: The country where the customer resides.
- Gender: The gender of the customer.
- Age: The age of the customer.
- Tenure: The number of years the customer has been with the bank.
- Balance: The balance of the customer’s account (£).
- Products: The number of products the customer holds with the bank.
- CreditCard: Indicates whether the customer has a credit card with the bank.
- ActiveMember: Indicates whether the customer is an active member of the bank.
- Exited: Indicates whether the customer has exited (churned) from the bank.
### Technology Stack 
- Microsoft SQL Server
- Microsoft Power BI
### Process
#### 1 Phase 1: Database Design and Data Importation (SQL Server)
- Database Setup
- Data Importation
- Basic Data Quality Check
#### 2 Phase 2: Data Transformation & Feature Engineering
- Create Derived Columns
- Churn Analysis Views
#### 3 Phase 3: Power BI Modeling & Dashboard Development
- Connect Power BI to SQL Server
- Create DAX Measures in Power BI
- Dashboard Development (Page 1: Customer Demographics & Segment Analysis, Page 2: Churn Analysis)
#### 4 Phase 4: PowerPoint
#### Key Recommendations and Actionable Insights
Having Processed and analysed data for 10,000 customers using Microsoft SQL Server to uncover key churn drivers such as low tenure, inactivity, and product usage. Created a Power BI dashboard with 16 visualizations that tracked churn trends by country, age group, and account activity, enabling regional comparison and risk profiling, I was able to  come up with the following insights and recommendations:
##### 1. Prioritize Retention of Mid-Term Customers (4–6 years Tenure)
This segment has the highest churn numbers and holds significant balances and credit card usage.
- Action:-Develop tailored loyalty programs and proactive engagement campaigns targeting mid-term customers to reduce churn and deepen product usage.
##### 2. Focus on High-Risk and Medium-Risk Customers in Germany and France
These countries show higher churn rates and larger proportions of high and medium risk customers compared to the UK.
- Action: Implement region-specific retention strategies, including localized offers, personalized communication, and improved customer service.
##### 3. Target Customers with ‘Fair’ Credit Scores for Early Intervention
The ‘Fair’ credit score group has the highest churn and medium risk levels, indicating vulnerability.
- Action: Use predictive analytics to flag these customers early and offer credit education, financial advice, or incentives to improve loyalty.
##### 4. Enhance Engagement Among Inactive Mature Adults and Onboarding Customers
Mature adults (36-55 years) and new customers (0-1 year tenure) show high inactivity and elevated churn risk.
- Action: Launch reactivation campaigns and personalized onboarding experiences to increase activity and satisfaction.
##### 5. Leverage Gender-Sensitive Approaches in Retention Strategies
Females show a slightly higher churn rate proportionally, while males represent larger absolute churn numbers.
- Action: Customize communication and product offers to address gender-specific needs and preferences, improving engagement and retention.
##### Conclusion
By combining demographic profiling with churn risk segmentation, the bank can deploy focused, data-driven retention strategies that protect valuable customer segments, reduce churn, and increase lifetime customer value, driving sustainable growth and profitability.






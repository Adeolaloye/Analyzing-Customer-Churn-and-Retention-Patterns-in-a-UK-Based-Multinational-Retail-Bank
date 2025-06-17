## Analyzing Customer Churn and Retention Patterns in a UK-Based Multinational Retail Bank
### Table of Content
- [Overview](#overview)
- [Business Challenge](#business-challenge)
- [Project Rationale](#project-rationale)
- [ Project Objectives](#project-objectives)
- [Data Dictionary](#data-dictionary)
- [Technology Stack ](#technology-stack)
- [Process](#process)
- [Key Actionable Insights](#key-actionable-insights)
- [strategic Recommendations](#strategic-recommendations)
- [Outcome Expectation](#outcome-expectation)
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
#### Key Actionable Insights
Having Processed and analysed data for 10,000 customers using Microsoft SQL Server to uncover key churn drivers such as low tenure, inactivity, and product usage. Created a Power BI dashboard with 16 visualizations that tracked churn trends by country, age group, and account activity, enabling regional comparison and risk profiling, I was able to  come up with the following insights
-  The mid-term customer segment (4-6 years) holds the largest balances (£104M) but also shows the highest churn (14.81%), indicating a critical revenue risk.
- Mature adults aged 36-55 represent the largest inactive group (2,800 members), many of whom likely fall into this mid-term tenure bracket.
- Germany and France both have higher churn rates (around 18%) than the UK (9.93%), highlighting geographic risk zones.
- Females and customers with “fair” credit scores are more prone to churn, suggesting opportunities for tailored product and engagement strategies.

### Strategic Recommendations
#### 1. Launch a “Mid-Term Loyalty & Reactivation Program” targeting mature adults in Germany and France:
- Offer personalized financial products or incentives to encourage continued engagement.
- Deploy proactive outreach to inactive mature adults with tailored communication.
- Focus on improving customer experience through dedicated relationship managers.
#### 2. Implement Early Warning Systems:
- Use credit score and tenure data to flag customers at “medium” or “high” churn risk for preemptive retention.
- Prioritize customers with “fair” credit scores and mid-term tenure for customized financial counseling and product offers.
#### 3. Enhance Gender-Specific Retention Initiatives:
- Since females churn slightly more, analyze usage patterns and develop products or communication campaigns to improve female customer satisfaction.
#### 4. Leverage UK Best Practices:
- Analyze UK’s engagement and retention models which yield lower churn, then replicate and adapt these strategies for Germany and France.
#### 5. Improve Activation of Inactive Members:
- Target mature adult inactive customers with reactivation campaigns focusing on digital banking adoption, personalized product bundles, or rewards.
### Outcome Expectation
By focusing retention efforts on the high-balance mid-term customers who are mostly mature adults in higher churn countries (Germany and France), the bank can:
- Reduce churn rate in these vulnerable segments,
- Increase overall active member rate beyond the current 51.5%,
- Protect significant deposits and revenue,
- Enhance customer lifetime value, and
- Strengthen regional market competitiveness.
 






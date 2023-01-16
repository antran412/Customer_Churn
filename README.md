**Telecom Customer Churn**
Maven Telecom is a telecommunication company that provides phone and internet servies to 7,043 customers in California. Data from Q2 suggests that customer churn has become a serious concern, in this analysis, with the available data about customer demographucs, location, services and current status, our purpose is to identify:
1. The importance of churn customers on company's performance in general and total revenue and monthly charge in particular
2. Factors can be the key drivers of customer churn
3. Churn reasons

This analysis will be used to suggest some approaches to reduce the customer churn rate.

## **1. The importance of churn customers on company's performace**
We will be looking at churn by revenue. Even though there are more than one KPIs when it comes to revenue: Total lifetime revenue, monthly charge, and average monthy revenue, we will use total revenue to evaluate the value of customers. The customers who churned contributed about 17% of the total revenue of company, which is significant.

## **2. Factors can be the key drivers of customer churn**
### **2.1 Services that company provided.**
Each customer has different customer profile in terms of services that he/she subscribes. Telecom is currently offering 12 serivices. They are: Phone service, Multiple Lines, Internet Service, Internet Type, Online Security, online Backup, Decive Protection Plan, Premium Tech Support, Streaming TV, Streaming Movies, Streaming Music, Unlimited Data.

From the first analysis of datasets, online security, online back up, device protection and premium tech support have correlated relationship with customer status. To be more precise, customers who don't subscribe to these services tend to stop using company's services after a period of time. Although other services seem to have relationship with customer status, however, it is weak and may not be considered factors affecting churning decision of customers.


### 2.2 Customer's other features
Contracts, number of referrals and tenure of months seem like another three features to look into to find the common characteristics of churned customers. 
Customers who have the long contract with company will usually choose to stay with company. It is difficult for them to stop using services because of long commitment that they have made earlier. On the other hand, customers who have month-to-month contract are easier to churn away when there are more attractive offers from Telecom's competitors. 

The relationship between number of refferals and customer status is the same. Customers having more refarrals don't choose to leave the company. There are some reasons behind it. Maybe it is because their family, friend network is using company's services, they receive special promotion and discounts for specific discount or getting special offer when connecting to peole within the same network. Whereas, customers who don't have or have less referrals tend to leave the company. Similarly, the longer the customers using Telecom's service, the harder it is for them to churn the company away. The reason behind this is there is no commitment between them and company. The relationship between these customers and company is so weak that it is easy for competitors to break into. 


Overall, the commitment of customers to company is one of the most important factors that influence the final decision of churning. This commitment is built upon different things: service quality, customer service and customer experience. With this in mind, there are some recommendations to build this commitment and reduce churn rate later in this report. 

## **3. Churn reasons**
The reasons customers choose to stop using company's service vary, however they comes to three main categories: competitors, dissatisfaction and attitude. 

Despite of the fact that customers who churn away because of competitors take a large percentage of churned customers, the ones who churned because of attitude and dissatisfaction also contribute the large portion of churned customers. This is the red alarm for Telecom to do internal audit in training employees, customer service, products and services. 

## **4. Recommendations**

We recommend to Maven Telecom the following action plans based on our analysis.

**Part 1: Improve products and services**
1. Research device offeres from competitors and expend our device offerings accordingly
2. Improve our current products and services to compete with competitors in terms of speed, reliabily...

**Part 2: Customer Service**
1. Design special training for customer service employees when communicating and answering customers' questions. 
2. Create online platform for this two sided communication and for rating level of satisfaction of customers after reaching the company out for help. 
3. Create and organize self-help content on Telecom's website.

**Part 3: Marketing and Sales**
1. Since any offer is better than no offer, experiement with offering customers Device Protection Plan and/or Premium Tech support free trials with discount should they choose to opt in
2. Convert regular customers to high value customers: use offers to incentivize customers to refer our services from others to others and get on one/two year contracts. 

The analysis of company's offers to keep customers stay and convert them to high value customers. 

## **5. Machine Learning Model to preduct customer who is about to churn**
There are thress models built to predict customers who are about to churn to have the appropriate responses: logistics regression, random forest and neural network. The lowest error is kept as low as 0.168. Models can be improved by increasing data and related features

## **6. Model Productionization
The last step is deploying the most accurate model to predict customer's churn decision. 

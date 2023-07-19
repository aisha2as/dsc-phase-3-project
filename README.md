# SYRIATEL TELCOM CHURN RATE ANALYSIS
![OpenAI Logo](https://www.esriuk.com/content/dam/esrisites/en-us/industries/2022/telecommunications/assets/overview/industry-telecom-overview-two-thirds.jpg)

## Project Overview
Customer churn is when a customer ceases his or her relationship with a company. Syriatel Telcom values its customers and wants to understand what leads some of them to end their relationship with us. Binary classification models were used to predict customer churn at Syria Tel. The primary goal is to identify influential factors to minimize financial losses from attrition.

## Problem Statement 
SyriaTel would like to maintain or increase the customer retention rate as well as address the challenge of customer churn by developing an accurate binary classification model that predicts the likelihood of customers discontinuing their services and identifies the factors they should address to reduce attrition.

## Data Science Process Used:
The Data Science Process that is adhered to in this analysis is the CRISP-DM Process.

### 1. Business Understanding
Telecoms prioritize acquiring and retaining subscribers. Customer attrition is a major concern in the competitive telecom sector, impacting companies like Syriatel. To address churn effectively, telecom businesses must recognize its underlying factors and predict them accurately. Businesses can proactively identify customers at risk of leaving and devise personalized retention strategies. Proactive churn management reduces revenue losses and improves customer satisfaction.


### 2. Data Understanding

##### What Data Did We Use?
The SyriaTel Dataset was retrieved from [Kaggle](https://www.kaggle.com/becksddf/churn-in-telecoms-dataset). It contains information on about 3,333 customers. The data includes various details like the state the customer is from, how long they've been a customer, whether they have an international plan or voice mail plan, how many customer service calls they've made, and many more.

### 3. Data Preparation:
In this stage, data is transformed, cleaned, and preprocessed to make it suitable for analysis. This included;
* Data Type conversion, Dealing with multicollinearity, and splitting the data.
  
### 4. Modeling

We tested our model to see how well it could predict customer churn. We fitted four models, Decision trees, Random forests, Logistic regression, and Gradient boost model. Our best model was the Gradient Boost Classifier, which had a recall score of about 81.2%.

##### Model Evaluation:

A combination of metrics such as accuracy, precision, recall, F1-score, and ROC- AUC can be used to evaluate the performance of the model and ensure that it meets the business requirements and goals of the telecom company.
![scores](https://github.com/Weru-Stanley/Group-2-Phase-3---SyriaTel-Churn-Rate-Project/assets/128227310/5b35723f-b1d5-4a7b-9f40-89ec70586d3f)

Additionally, the key features that were shown to influence whether a customer would churn or not can be seen in the bar plot displayed below. We can note that the total expenditure is a key predicting variable.
![Features](https://github.com/Weru-Stanley/Group-2-Phase-3---SyriaTel-Churn-Rate-Project/assets/128227310/666b8e94-bfb2-4c08-8219-d93221a685d9)

## Conclusions 
Factors such as the number of customer service calls, whether the customer has an international plan, and the total day's minutes and charges were significant predictors of customer churn. Interestingly, we found that customers with an international plan are more likely to churn.

### What's Next?
Based on our findings, we recommend SyriaTel to:
- **Review International Plan:** Review the structure and pricing of the international plan to ensure it meets customer needs.

- **Improve Customer Service:** Improve the customer service experience to reduce the likelihood of churn.

- **Analyze Pricing Structure:** A review of pricing strategies and structures could help to ensure they are competitive and provide value to customers.

# Customer churn prediction
![image](https://github.com/Evah282/Phase-3-project/assets/125399280/a0cb0ad7-90dd-4759-87af-a622c74293a1)
### BUSINESS OVERVIEW
SyriaTel is a telecommunications company operating in a highly competitive market.
The company provides various services, including mobile, landline communications and internet to its customers.
SyriaTel's success relies on customer acquisition and retention.

###  Business understanding
In this project, we are working with SyriaTel, a telecommunications company, to predict customer churn. The goal is to build a classifier that can identify customers who are likely to stop using SyriaTel's services. By understanding the factors contributing to churn, SyriaTel can take proactive measures to retain customers and improve their business performance. Through data analysis and predictive modeling, we aim to provide insights and recommendations that can help SyriaTel reduce churn rates and enhance customer retention strategies.

** Objectives **
1. Build a predictive model to accurately classify customers as churn or non-churn.
2. Identify key factors and patterns that contribute to customer churn in SyriaTel.
3. Provide actionable recommendations for SyriaTel to implement targeted retention strategies and reduce churn rates.

### Data understanding
The dataset consists of various features such as customer information, usage patterns, and service details. The target variable is "churn," indicating whether a customer has churned or not. We will preprocess the data, perform exploratory data analysis, and generate relevant features to prepare it for modeling

### Data cleaning and preparation
our dataset had neither missing value nor duplicates.
Encoded the data, feature scaled and handled imbalanced classes.

### Modeling
I used logistic regression, random forest and hyperparamer tuned the random forest model to predict customer churn.

### Model Evaluation
The models were evaluated based on accuracy, precision, recall, and F1-score.

### Findings 
1. The logistic regression and random forest models identified customer service calls as an important factor in predicting churn.

2. Both models highlighted the significance of international plans in predicting churn.

3. The analysis revealed that specific usage patterns, such as the total day minutes and total eve minutes, were important predictors of churn. 

4. The churn prediction models can be used to identify high-risk customers who are more likely to churn.

### Recommendations
1. Focus on improving customer service.

2. Personalized offers for international plans.

3. Analyze usage patterns and identify opportunities.

4. Proactively monitor and engage high-risk customers.

### Next steps
1. Implement the recommended retention strategies, including personalized incentives, improved customer service, and proactive outreach to high-risk customers.

2. Track and measure the impact of the implemented strategies by monitoring churn rates, customer satisfaction levels, and key performance indicators related to customer retention.

3. Conduct further analysis to gain deeper insights into customer behavior, preferences, and churn drivers. This may involve conducting customer surveys or interviews.

# Data-Mining-Project
Business Context

The insurance industry offers a wide range of policies to its customers. Caravan insurance is a niche product with a specific target audience. With 86 features that capture customer demographics, behaviors, and existing policy data, there is a significant opportunity to leverage this data to predict customer propensity to purchase caravan insurance.

The marketing team faces the challenge of a limited budget, a common constraint for many businesses. Reaching out to potential customers can be expensive, and not all engaged customers will convert into policyholders. Marketing to all customers could lead to inefficient resource allocation and a lower return on investment (ROI).

Approach

To address this challenge, predictive analytics can be used to identify a segment of the customer base with a higher likelihood of purchasing caravan insurance. By analyzing existing features, such as the number and types of policies customers already have, their income levels, social class, household composition, and more, the team aims to develop a predictive model. This model will score each customer on their probability of purchasing a caravan insurance policy.

By leveraging predictive analytics, the company aims to allocate its limited marketing budget effectively, targeting customers most likely to purchase caravan insurance. This will save on customer acquisition costs and increase the overall effectiveness of marketing campaigns.

Data:

ticdata2000.csv: Training data with features and target variable (caravan insurance ownership).

ticeval2000.csv: Unseen data with features but no target variable.

tictgts2000.csv: Target variable data for evaluating model performance on unseen data.


Model Building:
Split the data into training and testing sets.(20 % test)
•	Trained several predictive models using different machine learning algorithms:
o	Logistic Regression
o	Decision Trees
o	Random Forest
o	Support Vector Machines (SVM)
o	Gradient Boosting


![image](https://github.com/ageerHarikrishna/Data-Mining-Project/blob/main/Screenshot%202024-06-16%20005058.png)


To strike a balance, I consider the F1 score, which harmonizes precision and recall, especially because my classes are imbalanced. I also conduct a cost-benefit analysis to weigh the financial impact of false positives and negatives.



Evaluation Metric :

A high recall rate means that the model is good at identifying actual buyers (minimizing the number of false negatives), which is crucial if the cost of missing a potential buyer is high. So we are choosing recall as important parameter.

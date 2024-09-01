# SyriaTel Customer Churn prediction

Author : Collins Ouko

## ** Overview **

For Telco companies it is key to attract new customers and at the same time avoid contract terminations (=churn) to grow their revenue generating base. Looking at churn, different reasons trigger customers to terminate their contracts, for example better price offers, more interesting packages, bad service experiences or change of customers’ personal situations.
This project investigates possible causes of customer churning and suggests recommendations to prevent churning.

## ** Business Understanding **

Syriatel, a telecommunications company, just like other telecommunication companies is facing a high churn rate, with many customers discontinuing their services and switching to competitors. The company wants to address this issue by developing a customer churn prediction model. By analyzing the dataset, Syriatel aims to gain insights into factors associated with churn, with the goal of reducing churn rate, increasing customer retention, and improving overall profitability.

## ** Data Understanding **

In this project, we will work with a customer churn dataset from the telecom industry provided as one of the project resource. The dataset contains information about customers, their usage patterns, and whether they have churned or not. The dataset contains 3,333 records and spans 21 columns. Of these columns, we identified 5 to be categorical, and 16 as numerical.

## ** Data Preparation **

In this phase, the dataset was cleaned, relevant features were extracted, and appropriate transformations were applied for modeling. Just to mention the variables with high cardinality were broken down into groups so that the analysis could be done excepting false misleads

## ** Modeling **

To begin, we point out that the dataset is imbalanced, with only 14.5% of the data being classified as "churn" and the rest being classified as "not churn."

Our baseline model was LogisticRegression , just to test how our chosen attributes would perform on a basic level. The logistic regression was tested for various classification metrics and we looked at the confusion matrix. We then explored the Decision tree and it's accuracy calculated which was compared to that of the logistic regression.

## ** Evaluation **

Logistic regression model has the highest accuracy of 0.869 and that of the decision tree is 0.846.

For this reason we adopted the logistic regression model which will be tuned for better performance.

## ** Conclusion **

The accuracy score of the logistic regression model is almost 87%. While this is still a good predictive model, we would like to undertake further feature engineering to boost this accuracy score. We achieved our objectives to be able to predict customer churn and had an acceptable accuracy score.

## ** Recommendations **

    . Offer discounts or promotional offers to customers in areas that have a higher churn rate.

    . Improve customer service quality and reduce the number of customer service calls.

    . Evaluate the pricing structure for day, evening, night, and international charges.

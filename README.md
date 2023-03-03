# Cap-III-Health-Insurance-Cross-Sell-Prediction

This is the second project in the category of supervised machine learning, in the  type of classification. "Health insurance cross sell prediction" is the project name. By predicting whether or not a customer will be interested in purchasing insurance, we will assist the insurance firm. Insurance companies hold all the information about their clients who have health insurance. The business is now attempting to cross-sell customers vehicle insurance. So, we need to identify the client who will purchase vehicle insurance from the specified insurance provider.

Let's break this down a little more in terms of a business context. Our client is an insurance company that has previously offered health insurance to its clients. Now, they need our assistance in developing a model to determine whether the policyholders' clients from the prior year will also be interested in the company's provision of vehicle insurance. A policy of insurance is an agreement whereby a business agrees to guarantee reimbursement for a specific loss, damage, disease, or death in exchange for the payment of a specific premium.

Vehicle insurance works similarly to medical insurance in that customers must pay an annual premium to the insurance provider firm in order for them to be compensated (referred to as Sum assured) in the event that their car is involved in an unfortunate accident.

Using a model to determine whether a consumer would be interested in vehicle insurance is very beneficial for the business since it allows it to plan its marketing strategy to reach out to those customers and maximise its business model and revenue.

So, we have information on demographics (gender, age, region code type), vehicles (car age, damage), policies (premium, sourcing channel), etc. to determine whether a customer would be interested in purchasing vehicle insurance.

So first we  do data preprocessing and then  feature selection and then we  build some kind of classification model. and try to compare different evaluation metrics and find out which model performs well.


conclusion from the project:

1] We have done our EDA and found out that the some features are not important in predicting the class for example - id , Annual premium , Driving liecense and vintage.

2] In the given dataset previously insured , vehicle age , age , policy slaes channel are most impacting features whcih decide the class of target variable.

3] We have implemented several models like logistic regression , Random Forest  and KNN  we found that the and amongs them .

4] We have seen that the data is highly inbalance between not interested class (87%) and intrested class values which are only (13%)

5] We have used SMOTE oversampling technique to balance dataset and we have found that the Random Forest classifier with Smote is offering Highest accuracy 81 %.

6] KNN with SMOTE is offering 79% accuracy and and Random Forest with SMOTE offering 81 % accuracy with our dataset.

# loan-default-prediction
Defaulting loan is one of the biggest challenges for a loan provider especially for fintech and banking industry. Therefore, it is important to assess the risk of loan applicant accurately to mitigate loses. 

Based on the datasets, we can infer the following steps involved in a loan approval process:

1.   Client submits loan application.
2.   After the application is received, client’s information is sent to the underwriters (auto/manual) to detect any possible fraud.
3. Loan application will be approved once the applicant is proven to be genuine and not have track record of defaulting loan.
4. Once the applicant agreed on taking an approved loan, it will be funded.

In this notebook, we will explore the development of a model to predict whether a new applicant is likely to default on their loan repayment. This model will use various features, such as the applicant’s loan amount, previous average payment, lead cost, and other relevant information, to make this prediction. We will start by exploring the data and performing nec:essary data preprocessing steps such as handling missing values, transforming skewed features, and dealing with imbalanced data. We will then build and train our model using popular machine learning algorithms such as XGBoost and measure the performance using metrics such as AUC-ROC. By the end of this notebook, you will have a solid understand of building this loan repayment model and the steps involved in its development.

The final model achieved an ROC AUC score of 96.34% on the test set, which indicates that our model has a good ability to distinguish between the positive and negative classes. The model can be used by lenders to assess the risk associated with lending money to a particular borrower and make informed decisions based on the predictions made by the model.

#Further improvement
1. To improve the model's performance, we could gather features such as:
  *   Income: Reflect borrower's ability to repay the loan
  *   Debt: Provide insights into borrower's ability financial situation and ability to repay the loan
  *   Credit Score: Provide insights into borrower's creditworth. Borrowers with higher credit score is more likely to repay the loan
  *   Employment History: Provide information about borrower's current and previous jobs. Borrowers with stable employment history is more likely to repay the loan.
  *   Education level and age: Borrowers with higher education level or older may be less risky as they are likely to have higher income and stability.

2. Retrieve the missing entries for `loan.csv`. It would be difficult to keep track of borrower's historical data accurately without a complete record.



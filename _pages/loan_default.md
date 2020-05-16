---
title: "Loan Default Detection"
permalink: /loan_default/
---

<img src="/cv-portfolio/assets/images/loans600.png" />

### Boosting credit default detection: Predict how capable applicants are of repaying loans by Gradient Boosting Method
<div style="color:#97AAC3">
  Group Project (5 persons) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Feb, 2020 - Apr, 2020
</div>
*******************
  
  
#### Introduction
Predicting default risk is an essential problem for financial institutions. Leveraging machine learning techniques with business data to make good predictions will not only empower trustworthy clients to be successful by providing loans, but also help financial institutions control business risk.  

Our project focuses on using supervised and unsupervised machine learning techniques to predict applicant’s repayment ability based on historical loan application data and a wide range of credit and transactional data. Our project uses the “Home Credit Default Risk” dataset from Kaggle. The dataset is provided by Home Credit, a company that provides loans to unbanked populations who have insufficient credit histories. After data cleaning and dataset join, the size of the final dataset we get is (307,511, 754). Excluding the ID column (“SK_ID_CURR”) and response column (“TARGET”), we have 752 features in our dataset.

<img src="/cv-portfolio/assets/images/loandefault1.png" />

<img src="/cv-portfolio/assets/images/loandefault2.png" />

<br/>

#### Key Contributions and Highlights
1.Led the team to build the project framework and end-to-end working pipeline, and managed the project progress.   

2.Built Gradient Boosting Classification model on loan default detection and achieved better predicting performance compared with baseline models (e.g. Logistic Regression, Decision Tree, Random Forest and Naive Bayes).  

3.Applied Bayesian Optimization approach in hyperparameter tuning which improved the efficiency of model selection.  

4.Gained experience in handling imbalanced data in classification problems and applied SMOTE (Synthetic Minority Oversampling Technique) method to oversample the minority class.

<br/>

#### Project Findings
According to the feature importance from Gradient Boosting model, we summarize several groups of factors that are valid for default prediction.
- Financial pressure of repaying: in accordance with our daily life experience, how difficult to repay the loan is one of the decisive factors influencing whether or not the client will default. It’s related to the total amount of the credit, how much is the annuity, how long it will take to repay the loan in full and amount and duration of other loans the clients have.
- Repaying capability : the second group of factors are the variables related with the client’s financial capability. The features we got in this project are some indirect indicators that reflect the repaying capability, like client’s age, employment and previous repay behaviors.
- History of loan applications: we also revealed that the duration from previous loan application to current application is also important in default prediction.

<p align="right"><a href="javascript:history.back()"><u>Back to Home</u></a></p>

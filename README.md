# Impact-of-CSM-on-Retention

This notebook is my bachelor’s thesis which was related to the research of factors affecting the retention of customers in the SaaS-business. After the application of classification algorithms, important factors were identified which was later added to the model of prediction the dynamics of MRR Retention. 

As the result it was revealed that the group of accounts with a CSM consultant has a higher MRR Retention value, therefore now it is obvious that the consultant helps to strengthen the relationship between the client and the company, but our company lacked a set of rules for properly assignment a consultant to the account. It was established
that MRR Retention is affected by the number of employees in the company, the initial value of MRR and the country of the company, these parametres were later used to formulate set of guidelines for onboarding process of new clients and assignment of consultants.

Historical data was collected using the SQL query language. Initial data processing was carried out at the stage of data extraction from storage using the SQL (PostgreSQL). The following algorithms and methods were chosen to conduct research: dispersion analysis, multiple linear regression, testing statistical hypotheses using the Mann-Whitney and Krukkell-Wallis criteria (because the distribution wasn't normal and heavily skewed, so the nonparametric tests were needed), a bootstrap algorithm for determining the mean values of the indicator for different samples, algorithms of classification CART, Random Forest, Gradient Boosting (CatBoost).

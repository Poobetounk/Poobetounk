Churn Scoring, customer churn prediction or churn analytics, is a process used by businesses to predict which customers are likely to leave or discontinue using their products or services. 
Customer turnover in the banking sector can happen for several reasons. These include unhappy experiences with service, expensive fees, or a lack of user-friendly and creative services. Moreover, banks can also deal with competition from other financial businesses that provide more appealing products or services.

With the data set we used machine learning to predict customer churning as below.


1. LogisticRegression

   
Accuracy (Test Set): 0.82

Precision (Test Set): 0.57

Recall (Test Set): 0.27

F1-Score (Test Set): 0.37

AUC (test-proba): 0.78

AUC (train-proba): 0.80


2. K-Nearest Neighbor


Accuracy (Test Set): 0.82

Precision (Test Set): 0.55

Recall (Test Set): 0.35

F1-Score (Test Set): 0.43

AUC (test-proba): 0.79

AUC (train-proba): 0.83


3. Decision Tree


Accuracy (Test Set): 0.82

Precision (Test Set): 0.54

Recall (Test Set): 0.43

F1-Score (Test Set): 0.48

AUC (test-proba): 0.79

AUC (train-proba): 0.850


<img width="281" alt="image" src="https://github.com/Poobetounk/Poobetounk/assets/136213004/f896b0c9-bcba-4d8e-9f88-a658604718b1">


4. Random Forest Classifier


Accuracy (Test Set): 0.86

Precision (Test Set): 0.78

Recall (Test Set): 0.39

F1-Score (Test Set): 0.52

AUC (test-proba): 0.86

AUC (train-proba): 0.93


<img width="292" alt="image" src="https://github.com/Poobetounk/Poobetounk/assets/136213004/834b4e74-bf0c-4b8b-a51d-7906e1f071a7">


5. XGBoost


Accuracy (Test Set): 0.86

Precision (Test Set): 0.76

Recall (Test Set): 0.45

F1-Score (Test Set): 0.56

AUC (test-proba): 0.86

AUC (train-proba): 0.90


As you can see, XGBoost is the best model that gave us the best AUC metric results.


Feature Importance : we selected as below


<img width="637" alt="image" src="https://github.com/Poobetounk/Poobetounk/assets/136213004/158cab85-c593-4dea-bbed-d3be911157d8">


So, this is our suggestion to prevent churn.

Give More Value: Add bonuses and extra benefits when customers buy more than two products together. Also, consider lowering taxes and interest costs, and offer small rewards or vouchers.

Focus on Ages 40-60: Offer special deals like home and car loans to customers aged 40-60. Also, introduce a program to help customers with their financial well-being.

Engage Inactive Customers: Gently remind inactive customers about their accounts. Offer attractive promotions and one-time deals based on what they've used or bought before.

Enhance German Branches: Make branches in Germany more appealing by providing bundled packages, lowering costs, and giving small rewards. Also, improve customer service for easier access.

These steps can make a big difference in keeping customers happy and loyal.























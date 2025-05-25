# Churn in the Telecom Industry
#### The aim of this project is to predict which customers have churned from a fictitious telecommunications company, based on various attributes related to the service that each costumer has consumed. Also, the performance between two classification models was compared to increase the precision of the prediction. You can find the dataset [here](https://www.kaggle.com/datasets/barun2104/telecom-churn/data).
#
1. Summary
* This project developed a predictive model to identify customers at high risk of churning (leaving). By anticipating churn, the company can implement targeted retention strategies, significantly reducing customer loss and protecting revenue.

2. The Problem
* Customer Churn: Customers discontinuing services.
* Impact: Direct loss of revenue; increased customer acquisition costs.
* Goal: Proactively identify at-risk customers to enable adjusted intervention and improve customer retention.

3. Solution Overview
* Data: Historical customer customer service calls, service usage, and billing information.
* Methodology: Machine Learning classification models (K-Nearest Neighbors, Logistic Regression).

4. Key Results
* As we can see in the first graphics below, as the number of calls into customer service increase, the chance of churn also increase. However, the second barplot shows that customers having the contract renewed are likely to continue with the service.
  
![analise_churn_servico_contrato](https://github.com/user-attachments/assets/073f1c1a-238d-4afd-b253-ef1f0ebf7037)

* Best Model: Both models (K-Nearest Neighbors, Logistic Regression) were quite similar in accuracy, precision and F1 Score, but Logistic Regression achieved a slightly superior performance in AUC.

![ROC_Curves](https://github.com/user-attachments/assets/9ef3e94b-d944-45cb-9a52-0aa8d1f62460)

* Comparing with the original Churn data, the model reached aan accuracy score of around 86%, meaning it is a good model to alert decision makers of which type of customer is likely to churn.

5. Next Steps
* Explore other modeling techniques for potential performance gains.

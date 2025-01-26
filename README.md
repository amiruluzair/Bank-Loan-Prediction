# Predictive Modeling for Personal Loan Conversion in The Bank's Customer Base

## Project Background
Thera-Bank, a leading financial institution, primarily caters to a large base of deposit customers. However, the proportion of customers who are also borrowers—referred to as asset customers—remains relatively small. As a strategic initiative, the bank aims to expand this segment to increase revenue from loan interest while retaining its customers as depositors.

Last year, the bank launched a retail loan campaign targeting its deposit customers. The campaign achieved a modest conversion rate of 9.6%. While this was a step forward, it highlighted the need for a more focused and efficient approach to identify potential customers for personal loans.

The retail marketing team at Thera-Bank recognizes the importance of targeted marketing to improve the success rate of these campaigns without exceeding the budget. With limited resources, it is crucial to prioritize high-potential customers, ensuring effective allocation of campaign efforts. By leveraging historical data and advanced analytics, the bank seeks to develop a predictive model that classifies customers likely to accept personal loans.

## Project Objective
The objective of this project is to design, build, and evaluate a machine learning-based classifier capable of identifying potential retail loan customers from Thera-Bank’s deposit customer base. This predictive model will assist the marketing team in:

Enhancing Campaign Efficiency: By focusing on high-potential customers, the bank can improve the success rate of its loan campaigns.
Reducing Costs: Targeted marketing minimizes expenditure by reducing outreach to customers less likely to convert.
Supporting Data-Driven Decision-Making: Providing actionable insights to the retail marketing department to refine their strategies.

## Key Features of the Project
Dataset: The project uses the Thera-Bank dataset, which contains customer demographic, financial, and behavioral data.
Data Preprocessing: Includes cleaning, transforming, and handling imbalanced classes to ensure a robust model.
Modeling Approach: Machine learning classifiers such as Logistic Regression, Random Forest, and Support Vector Machines (SVM) are evaluated.
Performance Metrics: Accuracy, precision, recall, F1-score, and AUC-ROC are used to assess the model’s ability to differentiate between potential borrowers and non-borrowers.
By achieving these objectives, the project will not only support Thera-Bank’s business goals but also serve as a case study in the application of machine learning for targeted marketing in the banking industry.

## Performance Evaluation
Top Performers:

Decision Tree and XGBoost achieved the highest accuracy of 98.4%. Both models showed strong balance between precision, recall, and F1-score for identifying customers likely to take a loan.
XGBoost performed slightly better in classifying minority class (loan buyers), achieving a higher F1-score (0.94) and macro-average metrics.
Logistic Regression:

While relatively simple, Logistic Regression achieved good overall accuracy (94.8%) but struggled slightly in precision for the minority class (loan buyers).
KNN, GBM, and MLP:

These models performed comparably well with accuracies around 98%, showing strong recall and F1-scores for the minority class.
Naive Bayes:

This model had the lowest recall for the minority class (0.38) despite achieving high precision (1.00) for it, indicating significant difficulty in identifying actual loan buyers.
Support Vector Machine (SVM):

SVM achieved an accuracy of 97.6% and maintained a good balance in performance for both classes, though slightly lower precision compared to other models.

## Conclusion
XGBoost and Decision Tree emerge as the most effective models for this dataset, with superior accuracy, precision, recall, and F1-scores for identifying potential loan customers.
Naive Bayes is not recommended for this problem due to its low recall for the minority class.
For practical implementation, XGBoost is preferred due to its robust performance and ability to handle class imbalances effectively.

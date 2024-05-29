# Loan_Status_Prediction

##Performances and Key Insights[Loan_Status_Prediction]

1. Model Performance Metrics:
   - Accuracy Score: The model achieved an accuracy score of 78.86%, indicating that approximately 78.86% of loan statuses were correctly predicted.
   - ROC Score: The ROC score, which measures the model's ability to distinguish between positive and negative classes, was 70.31%. While not exceptionally high, it suggests moderate predictive power.

2. Confusion Matrix Insights:
   - True Positives (TP): The model correctly predicted 18 instances where the loan was approved.
   - True Negatives (TN): It correctly predicted 79 instances where the loan was rejected.
   - False Positives (FP): There was one instance where the model incorrectly predicted a loan approval.
   - False Negatives (FN): It incorrectly predicted 25 instances as loan rejections when they were actually approved.

3. Key Performance Evaluation:
   - Correct Predictions: The model demonstrated a relatively high number of correct predictions for both loan approvals (TP) and rejections (TN), indicating a good understanding of the dataset's patterns.
   - Misclassifications: However, there were some misclassifications, with a small number of false positives and false negatives. These misclassifications could be areas for improvement in future iterations of the model.
   - Overall Performance: With a solid accuracy score and a moderate ROC score, the model shows promise in predicting loan statuses based on applicant and property metrics. However, there's room for refinement to enhance its accuracy and reduce misclassifications.

# Employee-Attrition-Analyzer
My Artificial Intelligence lab project and Google Colab notebook.
## Conclusion

In this project, an **Employee Attrition Analyzer** was developed using the **IBM HR Analytics Employee Attrition dataset**. The dataset was cleaned and preprocessed by checking missing values, removing unnecessary columns, converting the target variable **Attrition** into numerical values and applying **one-hot encoding** to categorical features.

Three machine learning models were integrated and trained: **Logistic Regression, Decision Tree and Random Forest**. Their performance was evaluated using **Accuracy and F1 Score** and confusion matrices were generated to analyze their classification performance. A feature importance graph was also created using the Random Forest model to identify important factors related to employee attrition.

Based on the obtained results, **Decision Tree was selected as the best model according to F1 Score**, achieving an F1 Score of **0.200**. Although Random Forest achieved the highest accuracy of **83.33%**, its F1 Score was only **0.039**. Therefore, Decision Tree was considered more suitable for identifying employees who are likely to leave the organization. Overall, the project successfully demonstrates the use of data preprocessing, multiple machine learning models, and evaluation techniques to analyze and predict employee attrition.

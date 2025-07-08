# Electricity-Theft-Detection

I have used two approach for this
Approach 1
This project applies multi-view ensemble learning to improve classification performance. Different views of Main Steps:
- Data loading and preprocessing
- Splitting features into multiple views
- Training models like Logistic Regression, SVM, and Random Forest on each view
- Combining models using hard/soft voting and stacking
- Evaluating performance with accuracy and confusion matrix

Approach 2
Developed a stacked ensemble model combining Random Forest, XGBoost, and Logistic Regression to detect electricity theft based on consumption behavior.
Applied ADASYN to address class imbalance, achieving high recall and ROC-AUC scores on imbalanced datasets.
Implemented a scalable solution for real-time monitoring and anomaly detection in smart grid environments, helping utility providers minimize revenue losses.
Libraries: pandas, numpy, sklearn, matplotlib, seaborn

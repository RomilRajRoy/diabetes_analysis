Diabetes Prediction Project

Overview

This project explores the predictive power of various health metrics in diagnosing diabetes using the Pima Indians Diabetes Database. The study applied several machine learning and data mining algorithms, including the Apriori algorithm for association rule learning, Random Forest, Gradient Boosting, Logistic Regression, and Support Vector Machine (SVM) for classification tasks.

Dataset

The dataset used in this project is the Pima Indians Diabetes Database, which is publicly available from the UCI Machine Learning Repository. It contains various health metrics for female patients of Pima Indian heritage aged 21 and older. Key features include:

Pregnancies: Number of times pregnant.

Glucose: Plasma glucose concentration.

Blood Pressure: Diastolic blood pressure (mm Hg).

Skin Thickness: Triceps skin fold thickness (mm).

Insulin: 2-hour serum insulin (mu U/ml).

BMI: Body mass index (weight in kg/(height in m)^2).

Diabetes Pedigree Function: A function that scores the likelihood of diabetes based on family history.

Age: Age of the patient.

Outcome: Binary outcome indicating diabetes status (1 if diabetic, 0 if not).

Objectives

Predictive Analysis: To develop predictive models using health metrics to accurately diagnose diabetes.
Model Comparison: To compare the performance of different machine learning algorithms in predicting diabetes.
Feature Importance: To identify the most significant health metrics contributing to diabetes prediction.
Methodology
Data Preparation

Data Cleaning: Missing values were imputed with the mean value. Outliers were detected and handled using the IQR method.
Standardization: Standardized the features to have a mean of 0 and standard deviation of 1.
Dimensionality Reduction: Applied Principal Component Analysis (PCA) for visualization purposes.
Models Used
Apriori Algorithm: Uncovered associations between health metrics and diabetes.
Support Vector Machine (SVM): Achieved the highest accuracy (97.83%) and AUC (1.00).
Random Forest: Provided robust performance with an accuracy of 96.15% and AUC of 0.99.
Gradient Boosting: Similar to Random Forest with high accuracy and AUC.
Logistic Regression: Provided reasonable accuracy (77.86%) and interpretability.
Results
Model Performance

Apriori Algorithm: Revealed significant associations between health metrics and diabetes.
SVM: Outperformed all others with an accuracy of 97.83% and AUC of 1.00.
Random Forest: High accuracy (96.15%) and AUC (0.99).
Gradient Boosting: High accuracy (96.15%) and AUC (0.99).
Logistic Regression: Reasonable accuracy (77.86%) with good interpretability.
Key Findings

Health metrics such as glucose levels, BMI, and age are significant predictors of diabetes.
Ensemble methods (Random Forest, Gradient Boosting) and SVM showed superior performance.
The Apriori algorithm provided valuable exploratory insights into health metric associations.
Conclusion

This project demonstrated the significant predictive power of health metrics for diabetes. Ensemble methods and SVM provided the best performance, while the Apriori algorithm revealed meaningful associations. Future work should focus on enhancing data quality, model optimization, and real-world application to improve diabetes prediction and management.

Files
final_mldm_cw_doc.docx: Detailed documentation of the coursework and analysis.
Healthcare-Diabetes.ipynb: Jupyter notebook containing the code and results of the analysis.
Author
Romil Raj Roy - rajromil5@gmail.com

License
This project is licensed under the MIT License - see the LICENSE.md file for details.

Acknowledgments
Thanks to the UCI Machine Learning Repository for providing the Pima Indians Diabetes Database.

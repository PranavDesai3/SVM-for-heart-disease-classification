Coronary Heart Disease Prediction Using Support Vector Machine (SVM)

This repository provides the code and resources for the project "Classification of patient data using Support Vector Machine to predict coronary heart diseases," authored by Pranav Desai. The project aims to predict the likelihood of coronary heart disease by classifying patient data using different SVM models.

Overview:

Cardiovascular diseases have become increasingly prevalent due to modern lifestyle factors such as sedentary behavior, high stress levels, and poor dietary habits. Accurate prediction and early diagnosis of heart diseases are crucial for effective treatment and management. This project investigates the use of Support Vector Machines (SVM) for the predictive classification of patient data, focusing on critical health indicators like age, resting blood pressure, cholesterol levels, and maximal heart rate.

Classification Models:

SVM 1 (Hard Margin SVM): Attempts to find a hyperplane that perfectly separates the classes in a linearly separable dataset.
SVM 2 (Soft Margin SVM): Introduces a regularization parameter to balance the margin maximization and misclassification penalties.
SVM 3 (Semi-Supervised SVM): Incorporates additional constraints to utilize both labeled and unlabeled data, enhancing model performance in cases of insufficient data.
Metric Description

Results:

The project includes detailed results and analysis of the three SVM models:

SVM 1: Infeasible for non-linearly separable data.
SVM 2: Achieves high accuracy and F1 scores for certain regularization parameters.
SVM 3: Outperforms SVM 2 in terms of precision and recall, making it the recommended model for predicting coronary heart disease.

Conclusion:
This repository provides a comprehensive solution for predicting coronary heart disease using SVM models. The semi-supervised SVM model (SVM 3) is recommended for its superior performance in terms of precision and recall, which are crucial for accurate diagnosis and early treatment.

For more details, refer to the full report in the repository.
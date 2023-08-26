# Heart-Disease-Prediction

Background:
Heart disease is a significant global health concern, affecting millions of individuals each year. Early and accurate prediction of heart disease is crucial for timely intervention and effective patient care. Machine learning techniques offer a promising approach to predict the presence of heart disease based on various medical and lifestyle factors.

Problem Statement:
Develop a machine learning model to predict the presence or absence of heart disease in individuals based on a set of relevant medical and lifestyle features.

Objective:
Build and evaluate predictive models that can accurately classify individuals as having heart disease or being healthy, using a dataset of historical patient data.

Dataset:
You will be provided with a dataset containing a variety of features related to patients' medical history and lifestyle, such as age, gender, blood pressure, cholesterol levels, ECG readings, and exercise habits. Each patient in the dataset is labeled as either having heart disease (positive class) or being healthy (negative class).

Models Used:
1. k-Nearest Neighbors (KNN) Model:
The k-Nearest Neighbors model is a non-parametric classification algorithm that predicts the class of a data point based on the classes of its k-nearest neighbors in the feature space. In the context of heart disease prediction, KNN analyzes the proximity of an individual's feature vector (e.g., age, blood pressure) to those of labeled data points to predict whether they have heart disease or not. The model's simplicity makes it easy to understand and implement.
Accuracy Achieved: 85%

2. KNN Model with Principal Component Analysis (PCA):
Incorporating Principal Component Analysis (PCA) into the KNN model enhances its performance by reducing the dimensionality of the feature space. PCA identifies the most significant directions of variance in the data and projects the original features onto a lower-dimensional space. By eliminating less informative dimensions, KNN with PCA can potentially enhance accuracy and reduce computation time.
Accuracy Achieved: 85%

4. Support Vector Machine (SVM) Model:
The Support Vector Machine is a powerful and versatile classification algorithm that aims to find a hyperplane that best separates the classes in the feature space. In heart disease prediction, SVM seeks to find a decision boundary that maximizes the margin between positive and negative instances. SVM is effective in handling complex decision boundaries and can adapt well to high-dimensional data.
Accuracy Achieved: 86.8%

6. SVM Model with Principal Component Analysis (PCA):
Incorporating PCA into the SVM model reduces the curse of dimensionality by transforming the data into a lower-dimensional space while preserving the most important information. This can lead to improved SVM performance by mitigating overfitting and enhancing the generalization capability of the model.
Accuracy Achieved: 88.5%

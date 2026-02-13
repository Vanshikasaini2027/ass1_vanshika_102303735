Objective
The objective of this assignment is to analyze the impact of different sampling techniques on the performance of machine learning models when working with an imbalanced dataset.

Dataset
The dataset used is a credit card fraud detection dataset.
Since the dataset was highly imbalanced, SMOTE (Synthetic Minority Oversampling Technique) was used to balance the classes before applying sampling techniques.

Methodology

Step 1: Data Preprocessing
Loaded dataset

Checked class distribution

Applied SMOTE to balance the dataset

Step 2: Sampling Techniques
Five different sampling techniques were applied:
Sampling1

Sampling2

Sampling3

Sampling4

Sampling5

Step 3: Machine Learning Models

Five different ML models were trained:
M1 – Logistic Regression

M2 – Decision Tree

M3 – Random Forest

M4 – KNN

M5 – Gaussian Naive Bayes


Results
Model	Best Sampling Technique	Highest Accuracy (%)
M1	Sampling5	94.41

M2	Sampling1	97.82

M3	Sampling5	99.75

M4	Sampling5	85.43

M5	Sampling1	88.82


Conclusion
Sampling technique significantly affects model performance.

Sampling5 performed best for most models.

Random Forest achieved the highest overall accuracy.

Proper balancing and sampling improve classification results in imbalanced datasets.

Tools Used
Python

Google Colab

Scikit-learn

Imbalanced-learn




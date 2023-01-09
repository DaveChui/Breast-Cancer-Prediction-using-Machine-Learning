###Breast Cancer Prediction using Machine Learning
This project aims to predict whether a breast cancer tumor is benign or malignant using machine learning techniques.

Requirements
Python 3.x
NumPy
Pandas
Scikit-learn
Matplotlib
Data
The data used in this project is the Wisconsin Diagnostic Breast Cancer (WDBC) dataset, which is available at the UCI Machine Learning Repository (https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29). The dataset consists of 569 samples of malignant and benign tumor cells, each described by 30 features.

Methodology
The project consists of the following steps:

Data preprocessing: The dataset is loaded and cleaned, and the features are scaled to ensure that they are on the same scale.

Feature selection: The most relevant features are selected using the Recursive Feature Elimination (RFE) method.

Model training: A variety of machine learning models are trained on the preprocessed and selected features, including logistic regression, k-nearest neighbors, and support vector machines.

Model evaluation: The performance of the trained models is evaluated using a variety of metrics, including accuracy, precision, and recall.

Model selection: The best performing model is selected based on the evaluation metrics.


Usage
To use the code in this project, clone the repository and navigate to the project directory. Run the following command to train the model and make predictions:

Copy code
python main.py
License
This project is licensed under the MIT License - see the LICENSE file for details.

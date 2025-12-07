# Brest-Cancer-Detection-Model
This project builds a machine learning model to classify breast tumors as benign or malignant using the Wisconsin Breast Cancer Dataset. It demonstrates the complete workflow of a real-world ML classification problem — from data exploration to model evaluation and interpretation.

# Key Features
Performed extensive EDA with pairplots, correlation heatmaps, distribution analysis, and label exploration.

Preprocessed data using feature scaling and train–test split for stable model performance.

Built and compared multiple classifiers:

  Logistic Regression
  
  Support Vector Machine (SVM)
  
  Random Forest Classifier
  
  K-Nearest Neighbours (KNN)

Tuned hyperparameters using GridSearchCV for improved accuracy and generalization.

Evaluated models with accuracy, precision, recall, F1-score, ROC-AUC, and confusion matrix.

Analyzed feature importance and misclassified samples to understand model behavior.

# Dataset

Wisconsin Breast Cancer Diagnostic Dataset

Available via sklearn.datasets.load_breast_cancer()

Contains 569 samples with 30 features describing cell nucleus characteristics.

# Objective

To build an interpretable and reliable ML model that aids in early detection of breast cancer by accurately classifying tumor types.

# Tech Stack

Python, Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

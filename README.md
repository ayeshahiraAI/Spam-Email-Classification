# Spam-Email-Classification
A Python project that classifies emails as Spam or Ham using TF-IDF vectorization and a Support Vector Machine (SVM). It converts email text into numerical features, trains an SVM model, evaluates accuracy, and can predict new emails as spam or not.

# Features
Uses TF-IDF Vectorization to convert text emails into numerical features.
Splits data into training and testing sets for model evaluation.
Implements Support Vector Machine (SVM) for classification.
Evaluates model performance with accuracy score.
Can predict whether a new email is spam or ham.

# Libraries Used
.1 numpy – for numerical operations
.2 pandas – for data manipulation
.3 matplotlib – for visualizations
.4 scikit-learn – for TF-IDF, model building, and evaluation

# How it Works
  Load the dataset of emails with labels
  Convert text messages into TF-IDF features.
  Split the dataset into training and test sets.
  Train an SVM classifier on the training data.
  Evaluate the classifier on test data using accuracy.
  Predict new emails as Spam or Ham.

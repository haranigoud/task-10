Task 10: KNN – Handwritten Digit Classification
 Internship Task – AI & ML

This project demonstrates handwritten digit classification using the K-Nearest Neighbors (KNN) algorithm on the Scikit-Learn Digits dataset.
The goal is to understand distance-based classification, the importance of feature scaling, and how to tune K for optimal performance.

 Dataset

Primary Dataset:

sklearn.datasets.load_digits()

Dataset Details:

1,797 samples

8×8 grayscale images (64 features per image)

Target classes: digits 0–9

Alternative Dataset (Optional):

MNIST (from Kaggle)

 Tools & Libraries Used

Python

Scikit-learn

NumPy

Matplotlib

Seaborn

 Project Workflow

Loaded the Digits dataset using load_digits()

Verified dataset shape and structure

Visualized sample digit images with labels

Split data into training and testing sets

Applied StandardScaler for feature scaling

Trained KNN classifier with K = 3

Evaluated accuracy on test data

Experimented with K values (3, 5, 7, 9)

Plotted Accuracy vs K graph

Generated Confusion Matrix

Displayed test images with predicted labels

Results

Best K value selected based on highest accuracy

Accuracy vs K graph used for comparison

Confusion matrix used to analyze misclassifications

Model successfully classifies handwritten digits

Outputs Included

Accuracy vs K plot

Confusion matrix heatmap

 Sample digit predictions

 Final accuracy score
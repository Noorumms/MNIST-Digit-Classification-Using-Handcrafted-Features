# MNIST Digit Classification Using Handcrafted Features

## Overview

This project performs handwritten digit recognition on the MNIST dataset using handcrafted statistical image features and a Random Forest classifier.

Instead of using deep learning, the project focuses on feature engineering and traditional machine learning techniques.

---

## Dataset

- Dataset: MNIST
- Images: 28 × 28 grayscale
- Classes: Digits 0–9
- Samples Used: 5000

---

## Extracted Features

The following 14 statistical features are extracted from each image:

1. Mean
2. Median
3. Variance
4. Standard Deviation
5. Skewness
6. Kurtosis
7. Entropy
8. Minimum Intensity
9. Maximum Intensity
10. Median Absolute Deviation (MAD)
11. Local Contrast
12. Local Probability
13. 25th Percentile
14. 75th Percentile

---

## Workflow

MNIST Image
↓
Feature Extraction
↓
Feature Vector (14 Features)
↓
Random Forest Classifier
↓
Prediction
↓
Evaluation

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Machine Learning Model

Random Forest Classifier

Parameters:

- Number of Trees: 100
- Criterion: Gini
- Max Features: sqrt

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Visualizations

- Sample Images
- Feature Vectors
- Confusion Matrix
- Feature Importance Ranking
- Results Summary

---

## Results

| Metric    | Score  |
|---------- |--------|
| Accuracy  | 25.60% |
| Precision | 24.21% |
| Recall    | 25.60% |
| F1 Score  | 24.82% |

---

## Future Improvements

- Support full MNIST dataset
- Compare Random Forest with SVM
- Compare with CNN-based models
- Feature selection techniques
- Hyperparameter optimization

---

## Author

Noor Fatima

Computer Science Student | Machine Learning & Computer Vision Enthusiast

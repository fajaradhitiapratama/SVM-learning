# SVM Kernel Comparison with Different Preprocessing Techniques

This repository contains Python code to compare the performance of SVM kernels (linear, RBF, polynomial) on a dataset with different preprocessing techniques (Normalizer, MinMaxScaler, StandardScaler, RobustScaler) and different test sizes (0.3 and 0.2).

## Prerequisites

Make sure you have the following libraries installed:

- `numpy`
- `scikit-learn`
- `matplotlib`

Example Output
You should see output similar to the following:

lua
Copy code
Results for Scaler: Normalizer, Test Size: 0.3:

Rbf Kernel
Accuracy: 0.85
Classification Report:
               precision    recall  f1-score   support

           0       0.87      0.85      0.86        55
           1       0.84      0.86      0.85        55

    accuracy                           0.85       110
   macro avg       0.85      0.85      0.85       110
weighted avg       0.85      0.85      0.85       110

Confusion Matrix:
 [[47  8]
 [ 8 47]]

==================================================

...

Contributors
This project was developed by:

Alfiah Zalfa Tsabitah
Fajar Adhitia Pratama
Immanuel Putra Timothy Tambun
Muhammad Harits Rahman
Nurfadhilah Putri Bumi
Shafa Tanaya Paramesti

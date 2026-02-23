# AI-Driven Breast Cancer Diagnostic Suite 🩺

## Project Overview
This project focuses on the supervised binary classification of breast mass characteristics to predict whether a tumor is **Malignant** or **Benign**. Utilizing the Breast Cancer Wisconsin (Diagnostic) Dataset, I engineered a high-precision diagnostic tool that prioritizes **Recall (Sensitivity)** to ensure no malignant cases are overlooked.

## Key Engineering Achievements
* **Performance:** Achieved **97.14% CV Accuracy** and a **0.9949 ROC-AUC**.
* **Model Optimization:** Evaluated Logistic Regression, KNN, and Random Forest, ultimately selecting **SVM (RBF Kernel)** for its superior balance of accuracy and inference latency.
* **Latency Benchmarking:** Reduced inference speed to **$9.13 \times 10^{-5}$ s/sample**, making it suitable for real-time clinical integration.
* **Medical Priority:** Optimized the decision threshold to minimize **False Negatives**, acknowledging the life-critical nature of medical diagnostics.

## Tech Stack
* **Language:** Python
* **Libraries:** Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn
* **Algorithms:** SVM (RBF), Random Forest, KNN, Logistic Regression

## Visuals
| ROC Curve | Confusion Matrix |
| :---: | :---: |
| ![ROC Curve](https://via.placeholder.com/300x200?text=ROC+Curve+Plot) | ![Confusion Matrix](https://via.placeholder.com/300x200?text=Confusion+Matrix) |

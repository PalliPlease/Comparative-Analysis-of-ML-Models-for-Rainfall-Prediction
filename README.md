# Comparative Analysis of ML Models for Rainfall Prediction

I have made this project to study and compare different machine learning models to predict rainfall. The goal was simple; to find the best model. Even though the project is simple, it still helps us understand various concepts. You may try to play around with the code (using a different dataset or more models) and try to learn.

## Project Highlights

- **Missing Data Handling**: Categorical columns imputed with mode, numerical columns with Iterative Imputer (MICE).
- **Feature Encoding**: Label encoding for categorical variables.
- **Outlier Removal**: IQR-based filtering.
- **Feature Scaling**: MinMaxScaler and StandardScaler used for normalization.
- **Class Imbalance**: Addressed using oversampling of the minority class.
- **Model Comparison**: Trained and compared Logistic Regression, Random Forest, Neural Network (MLP), and LightGBM classifiers.
- **Evaluation**: Accuracy and ROC AUC score used as performance metrics.
- **Visualization**: Bar plots for model comparison.


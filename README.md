# Lung Cancer Prediction - Model Comparison

This repository contains a comprehensive project for predicting lung cancer using various machine learning models. The focus is on comparing individual model performances and building an ensemble model to enhance prediction accuracy. The dataset includes multiple features relevant to lung cancer, which have been preprocessed, normalized, and used for training several classifiers.

This repository contains the code for data preprocessing, model training, evaluation, and visualization, providing a comprehensive approach to lung cancer prediction using machine learning.

Model Training and Hyperparameter Tuning
- Support Vector Machine (SVM): Training SVM models with different kernels and regularization parameters.
- Random Forest Classifier: Utilizing ensemble methods with varying numbers of estimators and depths.
- Gradient Boosting Classifier: Implementing boosting techniques with different learning rates and numbers of estimators.
- XGBoost Classifier: Employing advanced boosting algorithms with hyperparameter tuning for optimal performance.
- GridSearchCV: Conducting exhaustive search over specified parameter grids for each model to find the best parameters.

Ensemble Learning
- Voting Classifier: Combining the best individual models (SVM, Random Forest, Gradient Boosting, XGBoost) using a soft voting approach to improve overall accuracy.


Model Evaluation
- Cross-Validation: Using cross-validation scores to evaluate model robustness.
- Classification Report: Generating detailed classification reports to understand precision, recall, f1-score, and support.
- Confusion Matrix: Visualizing the performance of the ensemble model with a confusion matrix heatmap.

Visualization and Analysis
- Correlation Matrix: Plotting the correlation matrix to understand feature relationships.
- Accuracy Comparison: Visualizing and comparing the accuracies of individual models using line plots.

Key Findings:
- The ensemble model, which combines SVM, Random Forest, Gradient Boosting, and XGBoost, provided a higher accuracy compared to individual models.
- The confusion matrix and classification report highlighted the performance metrics of the ensemble model on the test set.


![image](https://github.com/Godhuli-De/LungCancerPrediction_ModelComparison/assets/75137558/e45750ba-7204-4d4a-a960-3bf388bccce5)


![image](https://github.com/Godhuli-De/LungCancerPrediction_ModelComparison/assets/75137558/0fbb5c82-9fce-42c1-89ba-eec3e2f7fa1e)


Contact
For any queries or suggestions, please contact [Godhuli De](https://github.com/Godhuli-De)

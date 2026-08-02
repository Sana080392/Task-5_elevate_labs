# Heart Disease Prediction using Decision Tree and Random Forest

## Project Overview

This project applies Machine Learning classification techniques to predict the presence of heart disease using the Heart Disease dataset. Two supervised learning algorithms, **Decision Tree** and **Random Forest**, are implemented and compared based on their predictive performance. The project also demonstrates model visualization, overfitting analysis, feature importance, and cross-validation.

---

## Objectives

* Load and preprocess the Heart Disease dataset.
* Train a Decision Tree Classifier.
* Visualize the Decision Tree.
* Analyze overfitting by varying the tree depth.
* Train a Random Forest Classifier.
* Compare the performance of both models.
* Interpret feature importance.
* Evaluate model performance using 5-fold cross-validation.

---

## Dataset

The project uses the **Heart Disease Dataset**, which contains medical information about patients along with a target variable indicating the presence or absence of heart disease.

**Target Variable**

* **0** – No Heart Disease
* **1** – Heart Disease

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## Machine Learning Models

### Decision Tree Classifier

* Trained using the training dataset.
* Decision tree structure visualized using `plot_tree()`.
* Tree depth adjusted to study overfitting and underfitting.

### Random Forest Classifier

* Ensemble learning method using multiple decision trees.
* Provides improved accuracy and better generalization compared to a single decision tree.

---

## Evaluation Metrics

The models were evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report
* Feature Importance
* 5-Fold Cross Validation

---

## Project Workflow

1. Import required libraries.
2. Load the Heart Disease dataset.
3. Split the dataset into training and testing sets.
4. Train the Decision Tree model.
5. Visualize the Decision Tree.
6. Analyze overfitting by changing tree depth.
7. Train the Random Forest model.
8. Compare model performance.
9. Analyze feature importance.
10. Evaluate both models using cross-validation.

---

## Results

* Decision Tree provides an interpretable classification model but may overfit if the tree grows too deep.
* Limiting the maximum tree depth helps improve generalization.
* Random Forest generally achieves higher accuracy and reduces overfitting by combining predictions from multiple trees.
* Feature importance analysis identifies the most influential medical attributes contributing to heart disease prediction.
* Cross-validation confirms the Random Forest model is more stable and reliable than a single Decision Tree.

---

## Conclusion

This project demonstrates the application of Decision Tree and Random Forest algorithms for heart disease prediction. While the Decision Tree offers simplicity and interpretability, the Random Forest classifier delivers better predictive performance and robustness. The comparison highlights the benefits of ensemble learning for healthcare classification problems.

---

## Future Enhancements

* Hyperparameter tuning using GridSearchCV.
* Compare with additional classifiers such as Logistic Regression, Support Vector Machine (SVM), K-Nearest Neighbors (KNN), and XGBoost.
* Perform feature selection to improve efficiency.
* Build a web application using Streamlit or Flask for real-time heart disease prediction.

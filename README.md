- **Name**: FAICY ANNIE TOM
- **Company**: CODTECH IT SOLUTIONS
- **ID**: CT08DS5797
- **Domain**: DATA SCIENCE
- **Duration**: August to September 2024
- **Mentor**: MUZAMMIL AHMED

# Overview of Project 

Project: Predictive Modeling with Classification

### Objectives:
1. **Classify Iris Species**: Train and evaluate different classification models to predict the species of Iris flowers.
2. **Compare Model Performance**: Assess and compare the performance of various classification algorithms.

### Key Activities:
1. **Data Preparation**:
   - Load the Iris dataset and convert it into a pandas DataFrame.
   - Define features (`X`) and target variable (`y`).
   - Split the data into training and testing sets.
   - Standardize the features using `StandardScaler`.

2. **Model Training and Evaluation**:
   - **Logistic Regression**: Train the model, make predictions, and evaluate using accuracy, precision, recall, F1 score, and classification report.
   - **Decision Tree Classifier**: Train the model, make predictions, and evaluate using the same metrics.
   - **Random Forest Classifier**: Train the model, make predictions, and evaluate using the same metrics.
   - **Support Vector Classifier**: Train the model, make predictions, and evaluate using the same metrics.

3. **Comparison**:
   - Collect accuracy scores for each model.
   - Print and compare the accuracies of the different models.

### Tools Used:
1. **Python Libraries**:
   - **pandas**: For data manipulation.
   - **NumPy**: For numerical operations.
   - **Matplotlib** and **Seaborn**: (Imported but not used in this code; useful for data visualization).
   - **scikit-learn**: For dataset loading, model training, evaluation, and metrics.

2. **Classification Models**:
   - **Logistic Regression**: From `sklearn.linear_model`.
   - **Decision Tree Classifier**: From `sklearn.tree`.
   - **Random Forest Classifier**: From `sklearn.ensemble`.
   - **Support Vector Classifier (SVC)**: From `sklearn.svm`.

3. **Metrics**:
   - **Accuracy**: To measure the proportion of correct predictions.
   - **Precision**: To measure the accuracy of positive predictions.
   - **Recall**: To measure the ability to identify all positive instances.
   - **F1 Score**: To provide a balance between precision and recall.
   - **Classification Report**: To provide a detailed report on precision, recall, and F1 scores for each class.

### Notes:
- The Iris dataset is loaded twice, which is redundant. You can remove the duplicate loading and preparation code.
- The code provides a comprehensive evaluation of different models but does not include data visualization or hyperparameter tuning, which can further improve model performance and insights.

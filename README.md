# Cardiovascular-Disease-Prediction
Built ML models to predict cardiovascular disease using Logistic Regression, LDA, QDA, Decision Trees, Random Forests, Gradient Boosting, KNN, and SVM. Applied EDA, preprocessing, scaling, SFS/BSS, and hyperparameter tuning to compare models by accuracy and sensitivity.

##  Project Objective

To analyze health-related data and predict whether an individual is at risk of developing cardiovascular disease based on clinical and lifestyle features. This model aims to assist in early diagnosis and preventive healthcare.

##  Dataset

- **Source**: [Cardiovascular Disease Dataset –Kaggle](https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset)
- **Features**: Age, gender, blood pressure, cholesterol, glucose, smoking status, alcohol intake, physical activity, etc.
- **Target**: Presence or absence of cardiovascular disease

##  Models Used

- Logistic Regression  
- Linear Discriminant Analysis (LDA)  
- Decision Tree  
- Random Forest  
- Gradient Boosting Classifier  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  
- Quadratic Discriminant Analysis (QDA)

##  Methodology

1. **Data Cleaning & Preprocessing**
   - Handled missing values and outliers
   - Feature scaling using StandardScaler
2. **Feature Selection**
   - Forward selection, backward selection, and correlation analysis
3. **Model Training**
   - Trained 8 classification models with hyperparameter tuning using GridSearchCV
4. **Evaluation Metrics**
   - Accuracy, Sensitivity, F1 Score, and Objective Value
5. **Visualization**
   - Plots for feature importance, confusion matrix, and model comparison

##  Results Summary

| Model                     | Accuracy | Sensitivity | Objective Value |
|--------------------------|----------|-------------|------------------|
| Logistic Regression      | 0.7302   | 0.6749      | 0.8989           |
| LDA                      | 0.7268   | 0.6666      | 0.8934           |
| Decision Tree            | 0.7374   | 0.6816      | 0.9078           |
| Gradient Boosting        | 0.7365   | 0.6951      | 0.9102           |
| KNN                      | 0.7367   | 0.6770      | 0.9059           |
| QDA                      | 0.7199   | 0.5888      | 0.8671           |
| Random Forest            | 0.7354   | 0.6940      | 0.9089           |
| Support Vector Classifier| 0.7341   | 0.6602      | 0.8992           |

##  Structure

- `notebooks/`: Jupyter notebooks for each step of the workflow  
- `data/`: Raw and cleaned datasets  
- `models/`: Saved model files  
- `plots/`: Visualizations and charts  
- `utils/`: Custom functions for preprocessing, evaluation, etc.

##  Future Improvements

- Hyperparameter tuning using Bayesian Optimization  
- Model explainability with SHAP  
- Integration into a simple Streamlit app for demo purposes


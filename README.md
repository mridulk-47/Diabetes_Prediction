# Diabetes_Prediction
This project implements a machine learning model to predict the likelihood of diabetes based on diagnostic measurements. The model uses a Support Vector Machine (SVM) classifier.

Dataset File link: "https://www.dropbox.com/scl/fi/0uiujtei423te1q4kvrny/diabetes.csv?rlkey=20xvytca6xbio4vsowi2hdj8e&e=1&dl=0"

## Features
- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age

## Target Variable
- Outcome (0 = Non-diabetic, 1 = Diabetic)

## Model
The core of this project is a Support Vector Machine (SVM) classifier. The data is first standardized using `StandardScaler` to ensure optimal performance of the SVM.

## Project Structure
- `diabetes.csv`: The dataset used for training and testing.
- `diabetes_prediction.ipynb` (or similar): The Jupyter/Colab notebook containing the full code for data loading, preprocessing, model training, evaluation, and prediction.

Results
The model achieved an accuracy of approximately 78.6% on the training data and 77.2% on the test data.

Future Enhancements
Experiment with different machine learning algorithms (e.g., Logistic Regression, Random Forest, Neural Networks).
Perform hyperparameter tuning for the SVM model.
Explore feature engineering to create more robust predictors.
Deploy the model as a web application.

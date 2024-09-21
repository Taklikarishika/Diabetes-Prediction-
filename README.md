# Diabetes-Prediction-

### Detailed Note for README (GitHub)

This repository implements a Support Vector Machine (SVM) for predicting diabetes using the PIMA Diabetes Dataset from Kaggle. The dataset contains features such as glucose levels, BMI, age, and other health-related data, with the goal of predicting whether a person is diabetic or not. 

The process includes:
1. **Data Preprocessing:** The dataset is loaded, inspected for missing values, and standardized using `StandardScaler` to improve model performance.
2. **Splitting Data:** The data is divided into training and testing sets using `train_test_split`, ensuring a stratified split to maintain the class distribution.
3. **Model Training:** A linear SVM classifier is trained on the training set. The model is evaluated based on its accuracy on both the training and testing sets.
4. **Evaluation:** The training accuracy is around 78.7%, and the test accuracy is around 77.3%, indicating a good balance between underfitting and overfitting.
5. **Prediction System:** The code also includes a predictive system where a user can input their data, and the trained model will predict if the person is diabetic or not.

The SVM model demonstrates the classification capabilities on a medical dataset and serves as a baseline approach for diabetes prediction.


This project implements an SVM-based classifier for predicting diabetes using the PIMA Diabetes Dataset. It includes data preprocessing, model training, evaluation, and a simple prediction system. The model achieves around 78% accuracy on training data and 77% on test data.

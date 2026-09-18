PROJECT STATEMENT
Car Price Prediction Using Machine Learning



Project	Car Price Prediction Using Machine Learning
Primary Algorithm	Random Forest
Project Type	Machine Learning / AIML
Dataset	Car_Details.csv
Submission	Project Report
 
1. Project Title
Car Price Prediction Using Machine Learning
2. Project Statement
The project focuses on developing a machine learning based system for predicting the price level of used cars from historical vehicle information. The system takes vehicle characteristics such as brand, age, kilometres driven, fuel type, seller type, transmission, ownership history, mileage, engine capacity, maximum power and seating capacity as input features. The project applies data preprocessing and feature engineering techniques and uses the Random Forest algorithm to classify vehicles into Low, Medium and High price categories. A numerical regression component is also intended to estimate the actual selling price.
3. Problem Statement
Used-car prices vary according to several vehicle attributes, making manual estimation difficult and potentially inconsistent. The objective is to build a data-driven model that learns patterns from historical car listings and provides an estimated price category for a given vehicle. The project also aims to support numerical price prediction through a suitable regression model.
4. Aim
To develop and evaluate a machine learning system capable of predicting used-car price categories and, after valid regression implementation, estimating the numerical selling price.
5. Objectives
1.	Understand and preprocess the car-price dataset.
2.	Handle missing and inconsistent numerical values.
3.	Extract car brand and calculate car age as engineered features.
4.	Encode categorical attributes for machine learning.
5.	Train a Random Forest classifier for price-range prediction.
6.	Evaluate the classifier using accuracy, precision, recall and F1-score.
7.	Use a confusion matrix to examine classification performance.
8.	Develop a valid Random Forest regression model for numerical price prediction.
9.	Demonstrate prediction on a sample vehicle.
10.	Prepare the project for reproducible command-line execution.
6. Proposed Methodology
The proposed workflow consists of dataset loading, data cleaning, missing-value handling, feature engineering, categorical encoding, train/test splitting, model training and evaluation. For classification, selling prices are converted into three quantile-based categories: Low, Medium and High. For regression, the original selling price remains the continuous target and should be modelled using a regression algorithm.
7. Expected Outcome
The expected outcome is a reproducible machine learning project that can classify a used car into a price range and, using the corrected regression component, provide an estimated numerical selling price. The system should also produce evaluation metrics and visual outputs that allow the performance of the model to be assessed.
8. Existing Project Result
The current notebook reports 0.8679 accuracy, 0.8711 weighted precision, 0.8679 weighted recall and 0.8689 weighted F1-score for the classification task. It predicts the sample Maruti Swift Dzire VDI, 2018 as High price range. The regression values currently present in the notebook are not treated as final results because the existing code uses RandomForestClassifier for a continuous selling-price target.
9. Scope
The project is intended as an AIML academic project demonstrating data preprocessing, feature engineering, supervised learning, model evaluation and prediction. It is not intended to replace professional vehicle valuation or account for every real-world pricing factor.
10. Declaration
I declare that the project titled 'Car Price Prediction Using Machine Learning' is being submitted for academic evaluation as an AIML project. The implementation, dataset handling, analysis and documentation should be reviewed by the student before submission to ensure that the final repository accurately represents their own work and complies with the applicable academic integrity and submission requirements.


STUDENT NAME: ANANDI SHARMA
REG NO: 25MIB10036
DATE: 18/09/2026


# Credit-Card-Risk-Classification-using-Decision-Trees

## Project Overview
This project is focused on building a predictive model for credit card risk classification using Decision Trees. The primary objectives are data preparation, feature engineering, modeling with Decision Trees, model evaluation, and making predictions on production data.

## Objectives
The primary objectives of this project are as follows:

1. **Data Preparation**: We start by exploring, preprocessing, and cleaning the raw credit card data to make it suitable for modeling.
   
3. **Feature Engineering**: We create relevant features, including transforming categorical variables into a suitable format for machine learning.
   
5. **Modeling**: We assess the model's performance using cross-validation, classification reports, confusion matrices, and visualization of the decision tree.
   
6. **Model Evaluation**: Assess the model's performance using cross-validation, classification reports, and confusion matrices.

7. **Making Predictions**: We demonstrate how the trained model can be used to make predictions on new production data.

## Methodology
1. **Data Preparation**: We load the raw credit card data, check for missing values (there are none), and split the data into input features and target variables.

2. **Feature Engineering**: We create dummy variables for categorical features, such as Gender and Card Status, to prepare the data for modeling.

3. **Modeling**: We build a Decision Tree classifier with a specified maximum depth (in this case, 3) and train it using the training data.

4. **Model Evaluation**: We evaluate the model's performance using cross-validation to measure its accuracy. We also create a visual representation of the decision tree and a confusion matrix.

5. **Making Predictions**: We demonstrate how to use the trained model to make predictions on new data, including creating a new CSV file with the predictions.

## Results
The Decision Tree classifier achieved high accuracy in classifying credit card risk levels. It had a mean cross-validation accuracy of approximately 99.70%. The classification report showed excellent precision, recall, and F1-score for each risk class, indicating the model's effectiveness.

## Production Dataset and Output File
For the production phase, a separate dataset named "New_Data.csv" was used. This dataset contains new credit card data that needs risk classification.

The results of the classifier, including the predicted risk classes, were saved to a new CSV file named "ProductionalData.csv" for further analysis and use.

## Credits
This project was implemented by Aleksandar Dimitrov and is licensed under the MIT License. If you have any questions or comments, please feel free to contact me at alexi.zein@gmail.com.


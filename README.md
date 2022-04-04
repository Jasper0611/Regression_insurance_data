# Regression_insurance_data

Analyse the data of insurance charges on how much money they got for insurance based on their Age,Sex,children, smoker,region,bmi.

Algorithms used :- Linear Regression, Decision Tree, Random Forest, KNN(KNearest Neighbours), Support Vector Machine

Visualize the dataset using the seaborn library , used barplot.

Data wrangling : Since the data contains str values converted it using pd.get_dummies and updated it to original data using concat function. Also dropped the null values in the data.

Assigned the values to X and Y , Split the data for training and Testing.

Model Preparation: Created models and fit tranform to predict the output of the model.

Validation the models using Mean Squared Error, RMSE, R2 Score.

Conclusion: Among all the above algorithms used, we got least rmse on Random Forest with score on 83%.

Second most algorithm performed well is KNN with score 79%

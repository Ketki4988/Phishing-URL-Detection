# Phishing-URL-Detection
Machine learning model to identify phishing URL
Objective:Build a model that predicts/classifies whether a website is a Phishing website.

Tools: Jupyter Notebook, Python libraries (numpy, pandas, sklearn, matplotlib)

Approach:

1. Data loading: Given structured data is loaded in Jupyter Notebook using necessary libraries 
2. Data Preparation: The data was already processed with integer values 1, 0, -1. So, no preparation steps were performed. 
3. Exploratory Data Analysis: Performed basic analysis on data to observe distribution, etc 
4. Outliers, Missing Value Treatment: Based on Exploratory Data Analysis, it was found that there are no outliers, no missing values and also data is balanced.
5. Choosing a model: This a supervised classification problem as dependant variable is discrete and has non-linear relationship with input variables. 
6. Model Training: To perform model training, the data was split into 80:20 ratio using random sampling
7. For performing Classification, we have used 5 Techniques:
						a) Logistic Regression
						b) Decision Tree
						c) Random Forest
						d) Gradient Boosting 
						e) XGBoost
8. Model Evaluation: In each technique, model was built, trained and k-fold cross validated. Prediction was done on unseen (test) data.
                    Each model performance was checked using performance measures such as confusion matrix, accuracy, 
                   f1 score, precision, recall. And all metrics of each model are compared to know which technique is best.
                    Feature Importance of Random Forest model is shown which shows the most important features among the rest.
9. Parameter Tuning: To improve the accuracy, I fine tuned model parameters for Gradient Boosing and XGBoost
10. Prediction/Classification: Using the trained ML classifier, I predicted the results on the unseen data (test data).
    This prediction shows that the model was performing 97% accurate classification.
    

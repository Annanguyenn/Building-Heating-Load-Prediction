# Building Heating Load Prediction

Predict building heating load with machine learning techniques and classification models including Linear Regression, Logistic Classficiation Regression, Feature Scaling (Unity Based Normalization). The effect of the amounts of Training data (100, 200, 300, 400, 500, all) to train regression models were also examined. Achieved a MSE score of 0.81 (improved 5% compared to models without Feature Scaling). 

Tools: Python, Scikit-Learn, Feature Scaling, Linear Regression, Logistic Classification Model. 


# Data:

**Data Source:**

* Data file is uploaded to Github and is named: Energy.csv
* The dataset was created by Angeliki Xifara ( Civil/Structural Engineer) and was processed by Athanasios Tsanas, Oxford Centre for Industrial and Applied Mathematics, University of Oxford, UK).

**Data Description:**
The dataset contains eight attributes of a building (or features, denoted by X1...X8) and response being the heating load on the building, y1.
<br>
* X1 Relative Compactness
* X2 Surface Area
* X3 Wall Area
* X4 Roof Area
* X5 Overall Height
* X6 Orientation
* X7 Glazing Area
* X8 Glazing Area Distribution
* y1 Heating Load

# Summary: 

* Build a linear regression and logistic regression classifiction model to predict heating load type of a building and evaluate model performances using Root Mean Square. 
* The effect of amount of data on the performance of prediction model was also examined. 
* Then, to make the training less sensitive to the scale of features, I performed unity based normalization on the above dataset and train the model again, compare model performance in training and validation with my previous model.
* The Logistic Regression Model with Feature Scaling performs beter with the Test Accuracy is 0.81 (5% higher than that of the previous model, which is 0.77).

Please find the attached files for more detailed information. 

Thank you!

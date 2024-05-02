Here’s the proposed methodology to build our prediction model:
A.	Data Collection – Collecting data from different sources and preparing our dataset.
B.	Data Preprocessing – Cleaning the data, performing exploratory data analysis i.e handling missing values, encoding etc. and splitting data into testing and training data sets.
C.	Feature Engineering – Extracting relevant features from the dataset that would be required to implement the prediction algorithms and create new features if required.
D.	Model Selection – Evaluate performance of each algorithm and pick the most accurate one.
E.	Hyperparameter Tuning – Selecting the most accurate hyperparameters from the various algorithms.
F.	Model Implementation – Implementing the best suited model for our project to get accurate results.

We have selected 6 models for performing our comparative study, namely,

A.	Linear Regression
B.	Random Forest Regression
C.	XGB regressor
D.	Decision Tree Regressor
E.	Gradient Boosting Regressor
F.	KNeighbors Regressor

After a comparative analysis of several regression models for Flight fare prediction, 
the model with the highest accuracy among the tested algorithms was the XGBoost Regressor. ]
This outcome shows how well XGBoost can identify intricate patterns and correlations in the aircraft fare information. 
Because XGBoost is ensemble-based, it can handle both linear and non-linear correlations in the data with ease, 
which makes it a reliable option for problems involving fare prediction.

The XGBoost Regressor is the model that performs best out of all of them, 
predicting flight fares with the highest accuracy, and the second most accurate model being the Random Forest Regressor.
Because it takes into consideration a wide range of factors that affect rates, the Random Forest Regressor might also be a useful tool for airlines 
looking to optimize their pricing strategy. By doing this, airlines can maximize income and maintain their competitiveness.

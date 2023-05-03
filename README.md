# Life-Expectancy-Prediction

PROBLEM SETTING
Human health depreciates with an increase in the number of diseases
The emergence and transformation of new diseases are contributing to a decrease in life expectancy rates.
There are various studies and research that indicate a decrease in life expectancy compared to previous times.
This trend is alarming and should be taken seriously by governing bodies, as it indirectly impacts the environment.
Over time, various factors act as barriers for humans to survive, which can cause health issues and reduce life expectancy.
Bad habits of humans also play a significant role in reducing life expectancy.
The ecosystem also plays a major role in determining life expectancy.

PROBLEM DEFINITION
The dataset contains variables that can help determine the life expectancy of a human being based on environmental and health conditions.
Can be used to forecast the future scenario of a particular country regarding life expectancy.
It helps identifying the vaccines that are needed most to increase life expectancy.
Identify the hospital utilities that will be required in the upcoming years to prevent widespread fear among the population.
We can gain insights into the factors that impact life expectancy and take preventive measures to improve it.
Improve decision-making for the betterment of public health.
The Life Expectancy dataset was taken from Life Expectancy Dataset (Kaggle), which is an open source hub to look for datasets.
The dataset contains a total of 22 columns and 3000 rows, where in the output or dependent variable gives life expectancy in age.
The independent variables includes Immunization related factors, Mortality factors, Economical factors and Social factors, 
which are in fact strong factors to identify the outcome we are trying to achieve.

DATA MINING TASKS
Detecting Outliers: Made Box plots for some variables which were out of range in order to detect the outliers and removed it.
Missing Values: After removing of the outliers, used mean in order to fill the missing values, based on different countries.
Standardization: Used Standard scalar in order to make all the dimensions equal for all the variables and not to make a single variable dominate.
Dimension Reduction: After using Standard Scalar, we applied PCA (Principal Component Analysis) in order to reduce the dimension with conserving the same variance. 
Found Covariance Matrix with Eigenvalues and Eigenvectors, selected the eigenvectors, which were of use and applied dot product with the original data values in
order to get PCA values which will be used in model training.

DATA MINING MODELS
Linear Regression: Linear regression is a statistical method used to model the relationship between a dependent variable and one or more independent variables. 
The method assumes a linear relationship between the dependent variable and the independent variable(s),
which means that the relationship can be described by a straight line.

Decision Tree Regression: Decision tree regression is a non-parametric supervised learning method used for
predicting the value of a dependent variable based on the values of one or more independent variables. 
The method involves constructing a tree-like model, where each node represents a decision based on a feature or attribute of the independent variables.

Random Forest Regression: Random forest regression is an ensemble learning method that combines multiple decision trees to make predictions on a dependent variable
based on the values of independent variables.

Support Vector Regression: SVR works by finding the hyper plane in a high-dimensional space that has the maximum margin with respect to the training data points.
The hyper plane is determined by identifying a subset of the training data points, known as support vectors, which lie closest to the hyper plane.

Lasso Regression: It is a type of linear regression that adds a penalty term to the ordinary least squares (OLS) regression to prevent over fitting and improve the model's generalization performance.

Ridge Regression: It is a type of linear regression that adds a penalty term to the ordinary least squares (OLS) regression to prevent over fitting and improve the model's generalization performance.

Elastic Net Regression: It is a combination of both L1 (Lasso Regression) and L2 (Ridge Regression) regularization.

K Neighbours Regression: Predicting the value of a continuous target variable based on the values of the k-nearest neighboring data points in the feature space.

Gradient Boosting Regression: Multiple weak prediction models to create a strong prediction model.

ADA Boosting Regression: Multiple weak prediction models to create a strong prediction model.

Extra Trees Regression: It is a variation of the Random Forest algorithm that builds a large number of decision trees and uses averaging to improve the predictive accuracy and reduce over fitting. 

PERFORMANCE EVALUATION
Mean Squared Error: (1/n) * Σ(i=1 to n) [(yi - ŷi)^2]
Root Mean Squared Error: sqrt((1/n) * Σ(i=1 to n) xi^2)
Absolute Error: |predicted value - actual value|
Mean Absolute Error: (1/n) * Σ(i=1 to n) |yi - ŷi|
R2 Score: 1 - (Sum of Squared Residual / Sum of Squared Total)

PROJECT RESULTS
We can see from the chart that among all the Regression models used, Extra Tree Regression is providing the best possible result.

We can see from the performance results, among multiple regression models used, Extra Tree Regression is giving the best result possible.
Based on the graphs, charts we can see that Life Expectancy does depend on multiple factors and can impact an outcome drastically.
While many factors dominate, there are some which does not harm if removed based on Dimensionality Reduction.












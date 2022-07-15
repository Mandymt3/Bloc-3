# Machine Learning Projects
## Projects Supervised Machine Learning
### 1. Walmart : predict weekly sales
#### Description
The purpose of this project is to build a machine learning model able to estimate the weekly sales in their stores, with the best precision possible on the predictions made.
Such a model would help understand better how sales are influenced by economic indicators and might be used to plan future marketing campaigns.
#### Dataset
The dataset contains information about weekly sales achieved by different Walmart stores. It has been changed compared to the original dataset from a Kaggle competition. 
#### Results
Notebook ML_Walmart.ipynb can deliver:
-         Some visualizations of features about weekly sales
-         A linear regression model predicts the total amount of weekly sales (with regularization to reduce overfitting)
-         The accuracy to assess the performances of the model
-         Important features for the prediction according to coefficients
### 2. Conversion rate challenge
#### Description
The purpose of this project is to build a model to predict if a given user will subscribe to the newsletter, by just using a few users' information. And analyze the parameters of the model to highlight features that are important to explain the behavior of the users.
#### Dataset
The dataset has been taken from a Kaggle competition
#### Results
Notebook ML_Conversion_rate_challenge.ipynb can deliver:
-         Some visualizations of data
-         A F1 score to assess the performance of each model
-         A .csv file contains predictions
-         Recommendations to improve the newsletter's conversion rate by analyzing the model’s parameters
## Projects Unsupervised Machine Learning
### Uber Pickups
#### Description
The purpose of this project is to build a model to recommend hot zones in New York City to be in at any given time of day.
Hot zones: where there are a lot of pickup demands for Uber

#### Dataset
The dataset contains latitudes, longitudes, and times of each pickup point which had been provided by Jedha.
#### Results
Notebook ML_Uber_pickups.ipynb can deliver:
-         A map shows hot zones per day of the week with animation  
-         Different results by unsupervised algorithms: KMeans and DBScan

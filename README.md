## Insurance Premium Prediction-Model Predicts Insurance Premium 
To give people an estimate of how much they need based on their individual health situation. After that, customers can work with any health insurance carrier and its plans and perks while keeping the projected cost from our study in mind. I am considering variables as age, sex, BMI, number of children, smoking habits and living region to predict the premium. This can assist a person in concentrating on the health side of an insurance policy rather than the ineffective part.

_ <b>Data source</b> _: https://www.kaggle.com/noordeen/insurance-premium-prediction
____________________________________________________________________________________________________________________________________________________________________
##<b>Approach</b>
Applying machine learing tasks like Data Exploration, Data Cleaning, Feature Engineering, Model Building and model testing to build a solution that should able to predict the premium of the personal for health insurance.

*<b>Data Exploration</b> : Exploring the dataset using pandas, numpy, matplotlib, plotly and seaborn.
*<b>Exploratory Data Analysis</b> : Plotted different graphs to get more insights about dependent and independent variables/features.
*<b>Feature Engineering</b> : Numerical features scaled down and Categorical features encoded.
*<b>Model Building</b> : In this step, first dataset Splitting is done. After that model is trained on different Machine Learning Algorithms such as:
Linear Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
XGBoost Regressor
Catboost Regressor
KNN
*<b>Model Selection</b> : Tested all the models to check the RMSE & R-squared.
*<b>Pickle File</b> : Selected model as per best RMSE score & R-squared and created pickle file using pickle library.
*<b>Web Application & Deployment</b> : Created a web application that takes all the necessary inputs from the user & shows the output. Then deployed project on the AWS Elastic Beanstalk.

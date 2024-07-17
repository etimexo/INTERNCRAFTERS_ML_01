# INTERNCRAFTERS_ML_01
House Price Prediction Project

**Project Overview:**
This project aims to build a predictive model to estimate house prices using various features related to the properties. 

**Data**
The dataset used for this project includes various features related to the properties such as:

Bedrooms: Number of bedrooms in the house.
Bathrooms: Number of bathrooms in the house.
Sqft Living: Square footage of the living space.
Sqft Lot: Square footage of the lot.
Floors: Number of floors in the house.
Waterfront: Whether the house has a waterfront view.
View: Quality of the view from the house.
Condition: Condition of the house.
Grade: Overall grade given to the house.
Sqft Above: Square footage of the house apart from basement.
Sqft Basement: Square footage of the basement.
Year Built: Year the house was built.
Year Renovated: Year the house was renovated.
Zipcode: Zip code of the location.
Link to dataset: https://www.kaggle.com/datasets/shree1992/housedata


**Data Preprocessing**
The data preprocessing steps included:

Encoding Categorical Variables: Applied encoding to categorical features.
Feature Scaling: Scaled numerical features using StandardScalar.
Outlier Removal: Removed outliers to enhance model performance.
Model Building
We used Linear Regression to build the predictive model. The data was split into training and testing sets with a 80-20 split ratio.


**Model Evaluation**
The performance of the model was evaluated using Mean Squared Error (MSE) and R² score. Here are the results:

Test Accuracy: 99.79514465019871
Linear Regression - Mean Squared Error: 101500909.7470236
Linear Regression - R² Score: 0.9979514465019871

**Conclusion**
The Linear Regression model demonstrated high accuracy in predicting house prices. The preprocessing steps and the choice of features played a crucial role in achieving these results. This model can be further improved and deployed for real-world applications to assist in property valuation.
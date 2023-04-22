# SC1015-Mini-Project

# B124 Team 3
### Contributors
- Benjamin - Data Preparation, Random Forest, Gradient Boosting,
- Jerry - Data Preparation, Results analysis and Evaluation

# Algorithms/Libraries
Pandas\
Linear regression\
Gradient Boosting regression\
Random forest regression\

# Contents
Slides:
A summary of our project for the video. It contains the aims for the project, data preparation , models used and the conclusions.\
\
Video:
The video recording of the summary of our project\
\
Project Jupyter File:
Project file of our project


# Datasets:
Prices of resale flat transactions and some variables
### Variables in the dataset:
- Month - Month and Year of transaction
- Town - Location of flat
- block	- Block number of flat
- street_name	- Street name of flat location
- storey_range - Storey range of flat
- floor_area_sqm - Floor Area of flat in square meter
- flat_model - Model of flat
- lease_commence_date	- Starting Year of lease of flat
- remaining_lease	- Years and months remaining before lease expires (Some entries do not have this variable)
- resale_price - Transaction price of the resale flat


# Problem Definition
- What are the main Factors affecting Resale Prices of HDB Flats
- Which model would be the best to predict the Resale Price?


# Models Used
- Linear Regression
- Multiple Linear Regression
- Random Forest Regression
- Gradient Boosting Regression


# Conclusion
- Main factors in the dataset is Floor Area and Remaining Lease
- Other Factors such as Location and Flat type also affects the resale price
- Gradient Boosting Regression is the best model amongst the 4 models used
- Random Forest does not perform as well as Gradient Boosting under the same hyperparameters
- Number of Estimators and Max Depth of the models affects the accuracy of the models
- The above hyperparameters have a positive relationship with the accuracy of the models
- Model can be improved through further data preparation and more variables such as amenities nearby


# What did we learn from this project?
1. Encoding Categorical Variables
2. Multiple Linear Regression
3. Random Forest Regression
4. Gradient Boosting Regression
5. Some Factors affecting resale price


# References:
### Data Source: 
https://www.kaggle.com/datasets/teyang/singapore-hdb-flat-resale-prices-19902020

### Data Preparation: 
https://pandas.pydata.org/docs/reference/api/pandas.get_dummies.html \
https://sparkbyexamples.com/pandas/pandas-replace-values-based-on-condition/ \
https://www.geeksforgeeks.org/how-to-convert-categorical-string-data-into-numeric-in-python/

### Models:
https://scikit-learn.org/stable/auto_examples/ensemble/plot_gradient_boosting_regression.html \
https://www.analyticsvidhya.com/blog/2021/05/multiple-linear-regression-using-python-and-scikit-learn/ \
https://datatofish.com/multiple-linear-regression-python/ \
https://towardsdatascience.com/random-forest-in-python-24d0893d51c0 \
https://www.geeksforgeeks.org/random-forest-regression-in-python/ \
https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.HistGradientBoostingRegressor.html\
https://www.baeldung.com/cs/gradient-boosting-trees-vs-random-forests#:~:text=Gradient%20boosting%20trees%20can%20be,and%20start%20modeling%20the%20noise \
https://www.analyticsvidhya.com/blog/2021/06/understanding-random-forest/#:~:text=A.%20Random%20Forest%20is%20a,model%20is%20a%20decision%20tree.

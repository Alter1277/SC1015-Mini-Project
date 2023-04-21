# SC1015-Mini-Project
# Tech Stack
Data source: Kaggle
Data wrangling: Python
Data visualisation: Tableau
Presentation: PowerPoint, Premiere Pro
#Algorithms/Libraries
Pandas
Autoregression
ARIMA
Linear regression
Decision tree regression
Random forest regression

# Contents
Slides: FSP5_Team07 Slides
The slides provide a quick summary of our project. It covers the overall aim of our project, data extraction and preparation from the APIs, our analysis using regression and time-series forecasting, and the conclusions we draw from our work.


# Datasets:
Datasets used for this project can be found in this folder. Examples of these include locations of bus stops and MRT stations, demographics of subzones, and passenger volumes of public tranposrtation.

# Contributors
Benjamin - 
Jerry - 
@nicklimmm - Neural Networks, Data Resampling, Data Extraction
@TCaken - Logistic Regression
@coolcoolwhat - Data Visualization, Data Extraction

# Problem Definition
What are the main Factors affecting Resale Prices of HDB Flats
Which model would be the best to predict the Resale Price?

# Models Used
Logistic Regression
Neural Networks

# Conclusion
Popularity and budget have low linear correlation value with ratings (watch out for bandwagons 🤣)
Popularity of the casts and crews have higher linear correlation value with ratings
Resampling imbalanced data improved model performance especially on the minority class
Logistic Regression did not perform well with non-linearly correlated variables
Neural Networks along with SMOTEENN resampling method consistently did well in predicting good movies after 100 training attempts (around 72% accuracy, 70% recall)
Yes, it is possible to predict if a movie is good with acceptable amount of accuracy and recall

# What did we learn from this project?

# References
## Data Source: 
https://www.kaggle.com/datasets/teyang/singapore-hdb-flat-resale-prices-19902020

## Data Preparation: 
https://pandas.pydata.org/docs/reference/api/pandas.get_dummies.html
https://sparkbyexamples.com/pandas/pandas-replace-values-based-on-condition/
https://www.geeksforgeeks.org/how-to-convert-categorical-string-data-into-numeric-in-python/

## Models:
https://scikit-learn.org/stable/auto_examples/ensemble/plot_gradient_boosting_regression.html
https://www.analyticsvidhya.com/blog/2021/05/multiple-linear-regression-using-python-and-scikit-learn/
https://datatofish.com/multiple-linear-regression-python/
https://towardsdatascience.com/random-forest-in-python-24d0893d51c0
https://www.geeksforgeeks.org/random-forest-regression-in-python/
https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.HistGradientBoostingRegressor.htm

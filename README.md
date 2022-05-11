# Restaurant Success Predictor based on Yelp Dataset
In this project, the Yelp dataset was used to predict the success of a restaurant in Tampa, Fl. The notebooks in this project can be used to analyze available restaurant's data across the United States. It can aid local restaurant owners as well as investors/potential restaurant owners in making informed business decisions according to changing consumer expectations.

## Contents
This repository has 5 python notebooks and saved files created by running these notebooks. 

### data folder 
Contains csv files generated in part 1 and 2 notebooks
1. vancouver_restaurants.csv - contains data about vancouver restuarant business - attached
2. vancouver_restaurants_reviews.csv - contains data about reviews related to restaurants in vancouver - could not attach because of size
3. vancouver_restaurants_tip.csv - could not attach because of size
4. restaurants_final.csv - contains the final dataset on which model will be trained and evaluated - attached 

### input folder
Contains json file provided by yelp which can be downloaded from https://www.yelp.com/dataset
1. yelp_academic_dataset_business.json - could not attach because of size
2. yelp_academic_dataset_review.json - could not attach because of size

### Jupyter notebooks
1. Data Extraction- This needs to the first notebook to be run. If required, the analysis and modelling can be done for other cities or smaller samples by changing this notebook.
2. EDA and Feature Engineering - This needs to the second notebook to be run. Explores the dataset and adds several additional useful features for training the model.
3. Data Preparation And Logistic Regression - This needs to the second notebook to be run. Prepares the data for training and trains a logistic regression model.
4. Decision Trees and Random Forests - Decision tree and random forest classifer models are used to gain actionable insights from the data.
5. Model Analysis and GridSearch  - The most successful model is trained by analyzing the 4 models and finding the best hyperparameters using GridSearch.

### Final results
The parquet format is used to store our final datasets, and we use the joblib files to store all the models trained in the notebooks.

### Project Report - Restaurant Success Predictor Using Yelp Dataset.pdf

### References
https://github.com/goelshivani321/Restaurant-Success-Predictor-based-on-Yelp-Dataset

https://github.com/alifier/Restaurant_success_model

https://jovian.ai/learn/machine-learning-with-python-zero-to-gbms

https://en.wikipedia.org/wiki/United_States_restaurant_industry

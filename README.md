# Machine Learning Project Repository

Hi, I'm Katie! I have a software engineering background and am currently working toward my Master's degree in data analytics. Welcome to my Machine Learning project repository. In this repository, you'll find a collection of projects that showcase various machine learning techniques and models I have applied throughout my studies. I have built a strong foundation in both regression and classification methods, experimenting with diverse models for predictive analysis.

I'm excited to expand this repository as I continue to broaden my knowledge and skills in this field!

## Project Overviews

### NYC Property Sales Exploratory Data Analysis
Performed EDA on the [NYC property sales Kaggle dataset](https://www.kaggle.com/new-york-city/nyc-property-salesLinks). Used Python and various Python libraries to identify categorical vs. numerical features, clean up the data, and implement other exploratory data analysis techniques to prepare the NYC property sales data for analysis.

### Econometric Analysis of Days on Market (DOM) in Logan Housing Market
Developed an econometric model to analyze factors affecting Days on Market for Logan Housing. After cleaning and preprocessing the data, I used both DOM and log-transformed DOM, I build and evaluated multiple regression models using metrics like MAE, MSE, and RMSE.

### Linear and Polynomial Regression on NYC Property Sales and Boston Housing Data
This project involved applying linear and polynomial regression on two real-world datasets to analyze property sales in NYC and housing prices in Boston.

For the NYC dataset, I prepared the data by adjusting feature types, log-transforming the target variable (SALE PRICE), and generating dummy variables for categorical features. I then fit the model using an 80/20 train/test split and confirmed model performance using 10-fold and 5-fold cross-validation.

For the Boston dataset, I explored the nonlinear relationship between housing prices and the LSTAT variable using polynomial regression. After transforming LSTAT (lower status population) to a 5th degree polynomial, I trained a model and evaluated it with K-Fold cross-validation. I then assessed the model's performance across polynomial degrees 1-10, identifying 9 as the optimal polynomial degree using the optimal RMSE.

### Penalized Regression on Wage Data
In this project, I applied various penalized regression models to analyze a wage dataset, focusing on model performance and feature significance. I first scaled the dataset, then implemented Ridge, Lasso, and ElasticNet regression models using scikit-learn with alpha=1. I then visualized the coefficients against a range of alpha values and used cross-validation to identify optimal hyperparameters for each penalized model and refitted them. Finally, I evaluated the RMSE of each model on the test set, comparing their performance against an OLS benchmark.

### Logistic Regression on Credit Card Default Data
For this project, I implemented a logistic regression model to analyze credit card default data. After preprocessing the data, I trained the model with default parameters, generating predicted probabilities and classifications, and analyzed the impact of diferent thresholds on false negatives and recall. I then plotted the ROC curve and calcuated the AUC score to confirm tha tthe model outperformed random predictions. Finally, I employed K-Fold compare accuracy across methods.

### KNN Analysis of Capital Bikeshare Data
In this project, I applied the K-Nearest Neighbors algorithm to the Capital Bikeshare dataset, analyzing bike rental patterns in Washington, DC, over two years (2011-2012).

KNN Regression: I predicted the total count of bike rentals using KNN regression. After preprocessing the data, I trained the model, made predictions, and evaluated performance using metrics like RMSE. 

KNN Classification: I also addressed the challenge of bike overload by creating a binary classification model. I defined an overload variable (1 if rentals > 500, otherwise 0) to analyze system efficiency. The model was trained to classify periods of overload, generating predicted probabilities and classifications based on different thresholds.


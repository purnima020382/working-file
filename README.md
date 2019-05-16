
# Used Car Price Predictions
This is a project that is built to predict the prices of used automobiles. It uses a Polynomial Regression model with the dataset created from scratch by web scraping using Beautiful Soup.

## Data
- All of the training data has been scraped from www.cars.com using Beautiful Soup 
- Additional feature engineering implemented using PolynomialFeatures
- Categorical features handled using one-hot encoding

## Modeling
- Ordinary Least Squares, Ridge and Lasso models are used
- L1 regularization is used to prune features

## Visualization
- Matplotlib, Seaborn and Yellowbrick are the packages used for all visualizations in this project

## Results
- Accuracy: 87.1%
- Minimal heteroscedasticity
- Normal distribution of residuals

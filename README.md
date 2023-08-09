# Laptop Price Prediction using Polynomial Regression
In this project, we aim to train a polynomial regression model to predict the price of laptops based on their features. The following steps will be followed, each accompanied by a report:

## Step-by-Step Guide
### a) Loading CSV File and Displaying Random Laptop Information
We will start by loading the CSV file containing laptop price data. We will then display information for 10 randomly selected laptops from the dataset.

### b) Data Visualization
Data visualization plays a crucial role in understanding the relationships between features and the target variable. We will create at least five plots to visualize different aspects of the data, such as the distribution of laptop prices, correlations between features and price, and any other relevant insights. Each plot will be accompanied by an interpretation.

### c) Dataset Cleaning and Feature Engineering
To ensure the quality of our data, we will perform dataset cleaning. This involves handling missing values, outliers, and any inconsistencies. Additionally, we may engineer new features or transform existing ones to improve the model's performance.

### d) Data Preparation for Machine Learning
Preparing the data for machine learning involves encoding categorical variables, scaling numerical features, and splitting the dataset into training, testing, and validation sets. We will explain the techniques used for encoding and scaling and provide details on the data split strategy.

### e) Model Training with K-fold Cross-Validation
To determine the optimal degree of the polynomial regression model, we will employ K-fold cross-validation. The model will be trained with different degrees of polynomials, and the mean squared error (MSE) will be calculated for each degree on the validation data. We will present a plot depicting the changes in MSE with increasing regression degree.

### f) Training the Final Model and Reporting Performance
Using the best degree determined from the previous step, we will train the final polynomial regression model. The model's performance will be evaluated on the test data, and both the MSE and R2 score will be reported. The MSE provides an indication of the average prediction error, while the R2 score measures the proportion of the variance in the target variable explained by the model.

### g) Determining the Most Important Feature
In this step, we will analyze the model's coefficients or feature importances to identify the most important feature for predicting laptop prices. We will provide our opinion on the most important feature and explain why we believe it holds the highest significance.

## Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request on the GitHub repository.

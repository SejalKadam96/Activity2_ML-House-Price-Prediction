# Activity 2 – House Price Prediction Using Linear Regression

## 1. Objective
To build a Simple Linear Regression model to predict house prices based on the area of a house using a supervised machine learning technique.

## 2. Dataset Information
- **Dataset Name:** Housing Price Prediction
- **Dataset Source:** [Kaggle – Housing Prices Dataset](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset)
- **Dataset File:** Housing.csv
- **Description:** The dataset contains information about houses, including area, bedrooms, bathrooms, stories, parking and price.

## 3. Tools and Technologies
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## 4. Feature Selection
- **Input Feature (X):** Area
- **Target Variable (Y):** Price

The area of a house is selected as the input because it can influence the selling price.

## 5. Methodology
1. Imported the required Python libraries.
2. Loaded the Housing.csv dataset.
3. Inspected the dataset and its statistical information.
4. Checked and handled missing values and duplicate records.
5. Selected area as the input feature and price as the target variable.
6. Created a scatter plot to visualize the relationship between area and price.
7. Split the dataset into 80% training data and 20% testing data.
8. Trained the Linear Regression model.
9. Predicted house prices using testing data.
10. Evaluated the model using MAE, MSE, RMSE and R² score.
11. Visualized actual and predicted house prices.
12. Predicted the price of a new house.

## 6. Linear Regression Equation

The model uses the following equation:

**Y = mX + c**

Where:
- Y = Predicted house price
- X = Area of the house
- m = Coefficient (slope)
- c = Intercept

## 7. Evaluation Metrics
The model is evaluated using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## 8. Conclusion
In this activity, a Simple Linear Regression model was developed to predict house prices using the area of a house. 
The dataset was divided into training and testing sets, 
and the model was evaluated using different performance metrics and visualizations.

The model has limitations because house prices also depend on other factors such as location, number of bedrooms and facilities.

## 9. Project Files
- `Activity2_House_Price_Prediction.ipynb` – Complete Python notebook with code and outputs.
- `Housing.csv` – Original dataset (if included in the repository).

## 10. Learning Outcome
Learned how to load and preprocess a dataset, select features and targets, train a Linear Regression model, make predictions and evaluate model performance.

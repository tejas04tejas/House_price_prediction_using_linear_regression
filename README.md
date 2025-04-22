# HOUSE PRICE PREDICTION USING LINEAR REGRESSION
 Project Title: House Price Prediction using Linear Regression
 Project Overview:
This project involves building a machine learning model to predict California housing prices based on features like median income, average rooms, house age, and population. The model is developed using the Linear Regression algorithm from the scikit-learn library. Visualization tools such as Seaborn and Matplotlib are used to explore the data and evaluate model performance.
Technologies and Libraries Used:
Python – Core programming language.


scikit-learn – For machine learning model, dataset loading, splitting, and evaluation.


pandas – For data manipulation and analysis.


NumPy – For numerical operations.


Matplotlib & Seaborn – For data visualization.


Step-by-step Explanation:
Install Required Libraries:
 We install libraries like scikit-learn, matplotlib, and seaborn to run the model on Google Colab.


Import Libraries:
 Import libraries for data handling, model building, and evaluation.


Load Dataset:
 The fetch_california_housing() function loads the real estate dataset that includes various features and target prices.


Convert to DataFrame:
 We structure the data into a tabular format using pandas and name the target column as "Price".


Explore the Dataset:
 Use .info() and .describe() to understand the structure, data types, and summary statistics.


Visualize the Data:
 Use histograms and scatter plots to understand the distribution and correlation between variables like average rooms, income, and price.


Prepare the Data:
 Separate features (X) and target (y) and split the dataset into training and testing sets (80/20 split).


Train the Model:
 Fit a LinearRegression() model on the training data to learn relationships between features and price.


Predict House Prices:
 Use the trained model to predict prices on the test data.


Evaluate the Model:
 Calculate Mean Squared Error (MSE) and R² Score to assess model accuracy and performance.


Visualize the Results:
 Plot actual prices vs predicted prices using a scatter plot to visually inspect how accurate the model is.


Outcome:
 Successfully built a machine learning model that predicts house prices using linear regression with decent accuracy. The project demonstrates data preprocessing, visualization, model training, and evaluation, all essential steps in a real-world ML pipeline.


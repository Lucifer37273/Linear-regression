Linear Regression Model

A simple implementation of Linear Regression for predicting continuous outcomes based on input features. This repository demonstrates the fundamentals of supervised learning using one of the most widely used regression techniques.

Overview

Linear Regression is a statistical method used to model the relationship between a dependent variable and one or more independent variables. This project includes:

- Data preprocessing
- Model training using least squares
- Evaluation metrics (MSE, R²)
- Visualization of results

Technologies Used

- Python 3.x  
- NumPy  
- Pandas  
- Matplotlib / Seaborn  
- scikit-learn (optional for comparison)


Getting Started

1. Clone the repository
git clone https://github.com/Lucifer37273/linear-regression.git
cd linear-regression

pip install -r requirements.txt

python src/linear_regression.py   

 Example Output
• 	Coefficients and intercept
• 	Mean Squared Error
• 	R² Score
• 	Regression line plotted against data


Evaluation
The model is evaluated using:
• 	Mean Squared Error (MSE): Measures average squared difference between predicted and actual values.
• 	R² Score: Indicates how well the model explains the variability of the target variable.


Notes
• 	You can swap out the dataset in the  folder.
• 	For multivariate regression, extend the implementation to handle multiple features.

References
https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html
https://en.wikipedia.org/wiki/Linear_regression






# Predicting Housing Prices Using Linear Regression

## Description
This project implements a linear regression model to predict housing prices based on various features such as average area income, house age, number of rooms, number of bedrooms, and area population. The model is trained using a dataset sourced from Kaggle, and includes data exploration, preprocessing, model training, evaluation, and visualization of results.

### Key Features
- Data loading and preprocessing using pandas.
- Implementation of linear regression using scikit-learn.
- Visualization of predicted vs. actual housing prices using matplotlib and seaborn.

## Dataset
The dataset used in this project contains information about housing attributes and their corresponding prices. It is downloaded from Kaggle using the `kagglehub` library.

## Project Structure
```
.
├── housing_price_prediction.ipynb   # Jupyter notebook containing the project code
├── actual_vs_predicted.png           # Visualization of predicted vs. actual prices
└── README.md                          # Documentation for the project
```

## Installation Instructions
To run this project, you need to have Python installed along with the required libraries. You can set up a virtual environment and install the necessary packages as follows:

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/housing-price-prediction.git
   cd housing-price-prediction
   ```

2. Install the required libraries:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn kagglehub
   ```

## Usage
1. Open the `housing_price_prediction.ipynb` notebook in Jupyter Notebook or Google Colab.
2. Run the cells sequentially to execute the analysis.
3. View the visualizations and evaluate the model's performance.

## Evaluation
The model's performance is evaluated using Mean Squared Error (MSE), which measures the average of the squares of the errors between predicted and actual prices. A scatter plot visualizes the relationship between actual and predicted prices.

## License
This project is licensed under the MIT License.

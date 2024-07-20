
# Simple Linear Regression: Predicting TV Sales

This repository contains a Jupyter notebook that performs a simple linear regression analysis to predict TV sales based on advertising expenditure. The notebook demonstrates how to load a dataset, visualize the data, calculate the line of best fit, plot the best fit line, and make predictions using the regression model.

## Contents

- `regression.ipynb`: The original Jupyter notebook.
- `updated_regression.ipynb`: The updated Jupyter notebook with enhanced Markdown cells.
- `README.md`: This readme file.

## Requirements

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- matplotlib

You can install the required packages using `pip`:

`pip install pandas numpy matplotlib jupyter

## Usage

1. **Clone the repository**:
   bash`
   git clone <https://github.com/azammustafa66/Data-Science-Projects/tree/main/Simple%20Linear%20Regression>`

2. **Open the Jupyter notebook**:
   bash`
   jupyter notebook regression.ipynb`

3. **Run the notebook**:
   Follow the steps in the notebook to load the dataset, visualize the data, calculate the line of best fit, plot the best fit line, and make predictions.

## Notebook Overview

### Loading the Dataset

First, we load the dataset containing the TV advertising budgets and sales figures. We open the CSV file and read it into a pandas DataFrame for easy manipulation and analysis.

### Visualizing the Data

We plot the data to visualize the relationship between TV advertising budgets and sales. This helps us get an initial understanding of the data distribution and any potential patterns.

### Calculating the Line of Best Fit

To quantify the relationship between TV advertising budgets and sales, we use linear regression to find the line of best fit. This involves calculating the slope and intercept of the regression line.

### Plotting the Best Fit Line

Once we have the slope and intercept, we plot the line of best fit on the graph. This helps us see how well the line represents the data.

### Making Predictions

Finally, we use our regression model to make predictions. We take some test values of TV advertising budgets and predict the corresponding sales figures.
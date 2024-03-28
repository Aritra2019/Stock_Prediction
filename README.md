# Stock Price Analysis and Prediction

## Part 1: Stock Price Visualization and Linear Regression Prediction

This section of the project involves the visualization of historical stock prices and the prediction of future prices using linear regression.

### Data Visualization
- Utilized Yahoo Finance API to fetch historical stock price data.
- Visualized the stock prices using matplotlib, seaborn, and Plotly.
- Analyzed the correlation between different stock price attributes.

### Linear Regression Prediction
- Split the dataset into training and testing sets.
- Scaled the features using StandardScaler.
- Trained a Linear Regression model to predict stock prices.
- Evaluated the model's performance using r2_score and mean squared error (MSE).

#### Results
- Achieved an r2_score of 0.81 on the training set and 0.83 on the test set.
- MSE was 246.70 for the training set and 234.70 for the test set.

### Data Overview
- Explored the dataset containing additional stock attributes such as volume.
- Checked data types and ensured non-null values.

### Summary
- Combined data exploration, visualization, and predictive modeling to gain insights into stock price movements.
- Utilized Python libraries such as pandas, NumPy, scikit-learn, matplotlib, seaborn, and Plotly.

## Usage
1. Clone the repository: `git clone https://github.com/your-username/stock-price-analysis.git`
2. Navigate to the project directory.
3. Run the Jupyter Notebooks to view the code and analysis.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

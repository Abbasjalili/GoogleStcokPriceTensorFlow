# Unveiling Google Stock Price Predictions with TensorFlow: A Data-Driven Tale

Welcome to the realm of financial foresight, where an AI-guided Stock Prophet leads the way. Equipped with cutting-edge technology like TensorFlow, embark on a quest to forecast Google's stock movements.

## Overview

This project delves into the captivating realm of predicting the stock market through the prism of data and technology. By leveraging historical data of Google's financial trajectory from Yahoo Finance, we undertake meticulous analysis and employ advanced techniques to uncover insights into future stock prices.

## Project Structure

### Task 1: Importing Google Stock Data
- Gather historical data of Google's stock prices from Yahoo Finance.
- Prepare the dataset for analysis.

### Task 2: Checking for Missing Data
- Ensure data completeness by checking for missing values.

### Task 3: Identifying Duplicate Entries in Stock Data
- Detect and handle any duplicate entries to maintain data integrity.

### Task 4: Checking Data Types in Stock Data
- Review data types of each column to ensure proper interpretation.

### Task 5: Preparing Time Series Data
- Format the date column and set it as the index for time-series analysis.

### Task 6: Removing Unnecessary Columns
- Streamline the dataset by removing unnecessary columns for simplification.

### Task 7: Visualizing Closing Stock Prices
- Visualize closing prices over time to identify trends and patterns.

### Task 8: Normalizing Stock Data
- Normalize the data to ensure all values are on the same scale for effective training.

### Task 9: Splitting Normalized Data for Training and Testing
- Split the data into training and testing sets for model evaluation.

### Task 10: LSTM Model Training for Stock Prediction
- Build, train, and evaluate an LSTM model to predict Google's stock prices.
- Calculate evaluation metrics such as MSE, MAE, RMSE, and R2 score to assess model performance.
- Refine the model to improve its predictive capabilities.

## Model Performance

### Initial Model
- Achieved promising results on the training dataset with low error metrics and high R2 score.
- However, performance on the testing dataset indicated potential overfitting.

### Improved Model
- Enhanced model complexity and regularization techniques.
- Improved performance on both training and testing datasets, with reduced errors and increased R2 score.

## Conclusion

The project provides valuable insights into the application of deep learning techniques, specifically LSTM networks, for stock price prediction. While the initial model showed promise, further refinement and optimization were necessary to improve generalization to unseen data. The improved model demonstrates the potential for leveraging data and technology to forecast stock market trends accurately.

Join us on this enthralling journey, where technology and data converge to unveil the mysteries of financial prognostication.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

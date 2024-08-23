# Forecasting-Bitcoin-Trends

This repository contains a project focused on predicting Bitcoin prices using the Prophet forecasting model. Prophet is well-suited for handling time-series data and provides robust forecasting capabilities.

## Overview

The project involves predicting future Bitcoin prices based on historical data. Using Prophet, the model is trained on past price data and then used to forecast future prices for the next year. This approach can help in understanding potential future trends in Bitcoin pricing.

## Installation

To run this project, you'll need Python and several libraries. You can install the required libraries using pip:

```bash
pip install pandas prophet
```

## Usage

### Data Preparation

1. **Data Loading**: The project uses historical Bitcoin price data, which is loaded from a CSV file.
2. **Data Transformation**: The dataset is transformed to match the format required by Prophet, with columns for dates and corresponding price values.

### Model Training

1. **Model Initialization**: Create an instance of the Prophet model.
2. **Model Fitting**: Fit the model to the historical Bitcoin price data.

### Making Predictions

1. **Future Dataframe Creation**: Generate a dataframe containing future dates for which predictions are to be made.
2. **Forecasting**: Use the fitted model to make predictions and obtain forecast values, including uncertainty intervals.

### Visualization

1. **Plotting Predictions**: Visualize the predictions using Prophet’s built-in plotting functionality to understand the forecasted trends and patterns.

## Conclusion

The project demonstrates how to leverage Prophet for time-series forecasting in predicting Bitcoin prices. By analyzing historical data and making future predictions, users can gain insights into potential price trends and make informed decisions.

Feel free to explore the code and adapt the model for different time-series forecasting tasks. For any questions or discussions, please leave a comment in the issues section of this repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


Description:
This project explores stock price trend prediction using a simple yet effective feedforward neural network built with PyTorch. The model is trained on historical daily closing prices of the S&P 500 and selected stocks from various sectors (technology, finance, airlines, and pharmaceuticals) to forecast the next day's closing price.

Key Features:
Data Preprocessing: Cleaning, formatting, and exploratory analysis using summary statistics and visualizations.

Model Architecture: Two hidden layers (16 & 8 neurons) with ReLU activations and dropout, followed by a single-output neuron for price prediction.

Training Setup: Optimized using the Adam optimizer and MSE loss function, trained for 50 epochs with batch size 64.

Visual Analysis: Includes line plots, actual vs predicted price comparisons, and candlestick charts using mplfinance.

Correlation Insights: Pearson correlation analysis reveals relationships between the S&P 500 and individual stock trends.

Limitations:
The model struggles with abrupt price shifts due to lack of time-series memory.

Slight lag in predictions during rapid market movements.

Future Enhancements:
Use of advanced temporal models like LSTM or GRU.

Integration of macroeconomic indicators for richer insights.

Extended dataset and improved hyperparameter tuning for better generalization.

This project demonstrates how basic neural networks can serve as a foundation for financial forecasting, offering meaningful insights into market behavior with room for further advancement.


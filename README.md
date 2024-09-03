# Nasdock

# NasDock

NasDock is a stock prediction application built using Python and Tkinter. It fetches real-time stock data, preprocesses it, and uses a pre-trained neural network model to predict future stock prices.

## Features

- Fetches real-time stock data using Alpha Vantage API
- Preprocesses data for prediction
- Uses a pre-trained neural network model for stock price prediction
- Displays historical and predicted stock prices using Matplotlib

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/nasdock.git
    cd nasdock
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Ensure you have a pre-trained model saved as `model.h5` in the project directory.

## Usage

1. Run the application:
    ```bash
    python app.py
    ```

2. Enter the stock symbol you want to predict and click on the "Predict" button.

## Dependencies

- Python 3.x
- Tkinter
- Pandas
- Numpy
- Requests
- Scikit-learn
- TensorFlow
- Matplotlib
- tkcalendar

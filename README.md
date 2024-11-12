#  Stock Price Prediction Web Application

This project is a web-based application for predicting different kind of stock prices using a Long Short-Term Memory (LSTM) model. The application is built with [Streamlit](https://streamlit.io/) for the frontend, making it easy to interact with the predictive model and visualize Bitcoin price trends.

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)

## Features
- **Data Visualization**: Plot historical stock price data with customizable stocks.
- **Price Prediction**: Predict future stock prices based on historical data using an LSTM model.
- **Interactive UI**: Streamlit UI for easy user interaction with prediction parameters.

## Tech Stack
- **Frontend**: Streamlit
- **Machine Learning**: LSTM model implemented with TensorFlow/Keras
- **Data Processing**: Pandas, NumPy

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Sankeerth2005/STOCK-PREDICTOR.git
    cd STOCK-PREDICTOR
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    
    ```

3. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

## Usage
1. Launch the app in your browser.
2. Use the provided UI to set the prediction parameters, such as date range and data intervals.
3. Enter the **Stock Sticker** name and press enter to view future price trends based on the trained LSTM model.
4. View historical data and the model's predictions on the interactive chart.

## Project Structure
```plaintext
/
├── app.py                # Main application file with Streamlit UI
├── model/                # Folder containing the LSTM model code and trained weights
├── data/                 # Data folder (optional) for storing historical price data
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation

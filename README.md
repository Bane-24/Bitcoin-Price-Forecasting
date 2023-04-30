# Crypto-Price-Prediction

### This project *CRYPTOCURRENCY PRICE FORECASTING USING MACHINE LEARNING* is conducted under the mentorship of Dr. Mohammad Abualsheikh by Arulnesan Arunan, Vaishali Mishra, Marneni Shourya Teja and Akshay Kumar Ramesh.
------------------------------------------------------------------------------------------------------------------------------------------------------
This project uses Long Short-Term Memory (LSTM), a type of Recurrent Neural Network (RNN), to predict the future prices of Bitcoin based on historical data. The model also incorporates historical data on the S&P 500 index as an additional feature.

The project uses Python and relies heavily on libraries such as pandas for data manipulation, tensorflow and keras for model creation and training, and matplotlib for data visualization.

## Installation
The required libraries can be installed as below:
`pip install pandas numpy matplotlib seaborn sklearn cryptocmd yfinance tensorflow keras keras-tuner`

## Usage
Clone the repository to your local machine.
Run the python script using a python interpreter.
The script will scrape historical Bitcoin and S&P 500 price data, train the LSTM model, make predictions, and visualize the results.

## Results
The model's performance is evaluated using Mean Squared Error (MSE), Mean Absolute Error (MAE), and the coefficient of determination, also known as R² score.


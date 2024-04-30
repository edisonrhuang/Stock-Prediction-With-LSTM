# Introduction

This repository presents an innovative application of Long Short-Term Memory (LSTM) neural networks for forecasting stock market trends. LSTM, a type of recurrent neural network (RNN), demonstrates exceptional proficiency in capturing sequential patterns, rendering it particularly suitable for predicting the intricate dynamics of financial markets.

Within this project, we leverage the capabilities of LSTM to analyze extensive historical stock market data and generate forecasts for future price movements. By training the LSTM model on comprehensive datasets, it learns to discern patterns and dependencies within the data, thereby enabling informed predictions about future market behavior.

# How to Run the Project

To run the Stock Market Predictor project, follow these steps:

1. Clone the repository or download the Jupyter Notebook:

   You can clone the repository to your local machine using the following command:

   `git clone git@github.com:edisonrhuang/Stock-Prediction-With-LSTM.git`

   Alternatively, you can download the Jupyter Notebook directly from the repository.

2. Update file paths for CSV files:

   If you are using Google Colab or have your CSV files stored in a different location, you may need to update the file paths where the CSV files are read from in the Jupyter Notebook. Modify the file paths accordingly to ensure that the data is loaded correctly.

3. Customize the dataset:
   If you prefer to use your own dataset instead of the provided CSV file, you can replace the existing dataset with your own. Ensure that your dataset follows the required format and contains the necessary features for training the LSTM model.

4. Import the proper packages:
   If you are running this project on your local machine, ensure that you have all the required packages installed. To install all the required packages, you can use the following command:

   `pip install pandas matplotlib numpy scikit-learn keras tensorflow`

5. Execute the Jupyter Notebook:

   Once your preferred environment is set up, you can execute the cells sequentially. Follow the instructions provided within the notebook for training the LSTM model, evaluating its performance, and generating stock market predictions.
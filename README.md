# Command-Based-Hotel-Analytics-Application-Using-Static-JSON-Data-

AI Hotel Management Chatbot

A command-line AI chatbot that analyzes hotel sales and predicts cancellation risks using historical data.

Project Overview

This project allows users to:

1.Check today’s sales based on the latest date in the dataset.

2.See payment-wise and room-wise sales summaries.

3.Predict cancellation risk using a simple Logistic Regression model.


Explore the dataset through easy commands.

1.Dataset: 10-day hotel sales in JSON format, including:

2.Bill ID

3.Amount

4.Payment mode (Cash, UPI, Card)

5.Room type (Standard, Deluxe, Suite)

6.Cancellation status


How to Run

1.Clone the repository or download the files.

2.Make sure you have Python 3.9+ installed.


3.Install required packages:

pip install pandas numpy scikit-learn matplotlib


4.Open the Jupyter Notebook hotel_chatbot.ipynb.

Run all cells.


5.Interact with the chatbot in the command-line interface.


Machine Learning Logic: Cancellation Prediction
1 Goal

Predict the likelihood that a booking will be cancelled based on historical booking data.

2️ Algorithm

Logistic Regression was used because:

The target is binary (cancelled: 0 = no, 1 = yes).

It predicts probabilities, which is perfect for estimating cancellation risk.

Simple, interpretable, and effective for small datasets.

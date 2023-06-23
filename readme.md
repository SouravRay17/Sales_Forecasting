# Sales Analysis Project
This project involves analyzing sales data to gain insights and make predictions. The dataset used in this project contains information about product sales, including the quantity, price, date, and address.

## Project Overview
The main goal of this project is to analyze the sales data and provide valuable insights to help improve business strategies and decision-making. The project includes the following steps:

Data Cleaning: The dataset is cleaned by changing the data types of relevant columns, extracting additional information such as month and state, and calculating the total sales for each transaction.

Data Filtering: Partial data entries that do not belong to the year 2019 are removed from the dataset to focus on the relevant timeframe.

Daily Sales Calculation: The cleaned dataset is grouped by date, and the total sales for each day are calculated.

Data Visualization: The daily sales data is visualized using a line plot to identify any trends or patterns.

Stationarity Test: The stationarity of the time series data is tested using the Augmented Dickey-Fuller (ADF) test. The null hypothesis is that the data is non-stationary, and the alternative hypothesis is that the data is stationary.

Differencing: If the data is found to be non-stationary, differencing is applied to make it stationary. The first difference and seasonal difference are calculated.

Autoregressive Integrated Moving Average (ARIMA) Model: An ARIMA model is fitted to the data to make predictions. The model order is determined based on autocorrelation and partial autocorrelation plots.

Forecasting: The ARIMA model is used to forecast future sales by generating predictions for a specified time period.

# Prerequisites
To run this project, you need the following:

Python 3.5 or above
Required libraries: pandas, matplotlib, statsmodels
Installation
Clone the repository:

bash
Copy code
git clone [https://github.com/your-username/sales-analysis-project.git](https://github.com/SouravRay17/Sales_Forecasting/new/main)
Install the required libraries:

Copy code
pip install pandas matplotlib statsmodels
Run the project:

Copy code
python sales_analysis.py
Results
The project generates several outputs, including:

A cleaned and filtered dataset with the necessary columns and calculated total sales.
Daily sales data for the year 2019, represented as a DataFrame.
Visualizations of the daily sales data.
The results of the stationarity test, including the test statistic and p-value.
Differenced data to achieve stationarity.
Summary statistics and diagnostics for the ARIMA model.
Forecasted sales for a specified time period.

# License
This project is licensed under the MIT License.

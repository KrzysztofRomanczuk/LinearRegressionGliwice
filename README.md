Real Estate Price Forecasting
This project contains Python code that forecasts real estate prices based on data from 2000-2022 and predicts their value up to 2040.

Requirements
To run this project, you must have the following libraries installed:

pandas
numpy
matplotlib

You can install them using the pip package manager by typing the following commands in the terminal:

Copy code
pip install pandas
pip install numpy
pip install matplotlib

Input Data
The input data for this project is located in the data.csv file. This file contains the following columns:

year: year
price_m2: real estate price per square meter
inflation: inflation rate
i_rates: interest rate
pkb_usd: GDP per capita in US dollars
sr_wynagrodzenie: average gross salary in Polish zlotys
How It Works
The program code performs the following actions:

Reads the input data from the data.csv file.

Fills in missing data using interpolation.
Calculates annual changes for each independent variable.
Calculates average annual changes for each independent variable.
Predicts input data for the years 2023-2040, taking into account average growth rates.
Calculates real estate price forecasts based on this input data.
Combines historical data with forecasts.

Displays a graph of real estate prices per square meter for the period from 2000 to 2040.
How to Run
To run the code, open the main.py file in a programming environment or terminal and run it.

The result of the program's execution will be a graph showing real estate price forecasts per square meter from 2000 to 2040.

Author
This project was created by Krzysztof Romańczuk.

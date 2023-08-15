## Hotel Bookings Data Analysis
This repository contains a Jupyter Notebook for analyzing hotel bookings data. The analysis is performed using Python and popular data analysis libraries such as Pandas, NumPy, Seaborn, and Plotly Express.

Contents
Introduction
Data Exploration
Guest Origins
Pivot Tables
Market Segments
Introduction
In this analysis, we explore a dataset containing hotel bookings information. The dataset includes details such as lead time, number of special requests, average daily rate (ADR), and more. We aim to gain insights into various aspects of the bookings and guest characteristics.

## Data Exploration
We start by loading the dataset and performing basic exploratory data analysis (EDA). We examine data types, column names, and handle missing or duplicated values. We also perform summary statistics on selected columns to understand their distribution.

## Guest Origins
We investigate the countries from which the guests are coming. A choropleth map is created using Plotly Express to visualize the home countries of guests. The map highlights the number of guests from different countries, providing a visual representation of guest origins.

## Pivot Tables
We create a pivot table that showcases the relationship between reserved room types and assigned room types. The pivot table is normalized to show percentages and helps us understand how room types are allocated.

## Market Segments
The analysis focuses on identifying the most popular market segment for bookings. We create a pie chart using Plotly Express to display the distribution of bookings across different market segments. Custom colors are used to make the chart more visually appealing.

Technologies Used
Python
Pandas
NumPy
Seaborn
Plotly Express
Matplotlib
Usage
To run this analysis, make sure you have the necessary libraries installed in your Python environment. You can install them using the following command:

Copy code
#pip install pandas numpy seaborn plotly matplotlib
Then, simply run the Jupyter Notebook in your preferred environment.


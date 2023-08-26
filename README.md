Introduction

This repository consists of Rental Bike demand prediction required at each hour of the day so that stable supply of rental bikes can be made possible. This is done by applying various Regression Machine Learning Algorithms.

Attribute Information

Date : year-month-day
Rented Bike count - Count of bikes rented at each hour
Hour - Hour of he day
Temperature-Temperature in Celsius
Humidity - %
Windspeed - m/s
Visibility - 10m
Dew point temperature - Celsius
Solar radiation - MJ/m2
Rainfall - mm
Snowfall - cm
Seasons - Winter, Spring, Summer, Autumn
Holiday - Holiday/No holiday
Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

Steps involved-

Importing necessary modules and libraries:

We are importing the following libraries for their respective applications:

Data Cleaning and Null values treatment: Data cleaning is an important step in the data analytics process in which you either remove or update information that is incomplete or improperly formatted. Null values Treatment by different methods. We have our dataset in hand which is raw and unfiltered. This step involves cleaning our data first by eliminating the columns which are not needed for our analysis. We have around 8760 rows × 14 columns in our dataset.Since, there were no null values, we have left it untouched.

Exploratory Data Analysis: Exploratory Data Analysis is the approach of analyzing data, gathering and summarizing the important characteristics of the information, and using simple visualization that makes it easier to understand.

Pandas:- Pandas is used to analyze data. It has functions for analyzing, cleaning, exploring, and manipulating data.

Matplotlib:- Matplotlib is a graph plotting library in python that serves as a visualization utility. Most of the Matplotlib utilities lie under the pyplot submodule.

Numpy:- NumPy is a Python library used for working with arrays. It also has functions for working in the domain of linear algebra, Fourier transform, and matrices.

SciKit:- Scikit-learn (Sklearn) is the most useful and robust library for machine learning in Python. It provides a selection of efficient tools for machine learning and statistical modeling including classification, regression, clustering and dimensionality reduction via a consistent interface in Python. This library, which is largely written in Python, is built upon NumPy, SciPy and Matplotlib.


Seaborn:- Seaborn is a library that uses Matplotlib underneath to plot graphs. It will be used to visualize random distributions.

Datetime:- The Datetime module supplies classes for manipulating dates and times. While date and time arithmetic is supported, the focus of the implementation is on efficient attribute extraction for output formatting and manipulation.

Conclusions:

Bike rental count is mostly correlated with the time of the day as it is peak at 8 am morning and 6 pm at evening.

We observed that bike rental count is high during working days than non-working day.

We see that people generally prefer to bike at moderate to high temperatures and when little windy.

It is observed that highest number bike rentals counts in Autumn & Summer seasons & the lowest in winter and spring season.

We observed that the highest number of bike rentals on a clear day and the lowest on a snowy or rainy day and also increasing humidity, the number of bike rental counts decreases.




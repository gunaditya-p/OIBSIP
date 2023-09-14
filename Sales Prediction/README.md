# SALES PREICTION

This was the fifth and final task assigned under this internship

## PROBLEM STATEMENT

Sales prediction means predicting how much of a product people will buy based on factors
such as the amount you spend to advertise your product, the segment of people you
advertise for, or the platform you are advertising on about your product.
Typically, a product and service-based business always need their Data Scientist to predict
their future sales with every step they take to manipulate the cost of advertising their
product. So let’s start the task of sales prediction with machine learning using Python.

## METHODOLOGY

I have used Python libraries pandas and numpy for data manipulation, matplotlib and seaborn for data visualisation and sklearn for building, training and testing the model.

First, we will go through the dataset to identify any empty data points that may cause discrepancies.
Then, we will rename the columns for our convenience.
A correlation heatmap is generated to get to know which medium can help contribute to sales more.
Next, I have plotted the scatter plots for each of the mediums with the Sales to get an idea about variation in sales with each medium.
Next, we have split our dataset into training and testing data points.
I will be using Linear Regression algorithm for the generation of ML model. 

## RESULTS

The accuracy of  the model came out to be 89.94%.
We also tested the model by putting some random values for the different fields of TV, Radio and Newspaper and generating the sales for the same.
For the values [230.1, 37.8, 69.2] the sales is 20.614.

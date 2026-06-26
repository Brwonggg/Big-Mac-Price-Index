## Preview
<img width="663" height="517" alt="Image" src="https://github.com/user-attachments/assets/8b9d38a5-efcb-49c5-8094-bd8a0a90709b" />

## Intro 
This is a practice project that draws a line of best fit without the help of machine learning libraries so as to better understand the math that goes behind calculating cost, gradient and gradient descent.

## Technologies
- Jupyter Notebook 
- Python

## Running The Project
To run the project in your own local environment, follow these steps:

1. Clone the repository to your local machine
2. Run `pip install -r requirements.txt`
3. Run all the cells

## Features
1. Convert the data to perform linear regression on into a csv file 
2. Tune the hyperparameters of learning rate alpha and number of iterations to minimize the cost function
3. Plot the relationship on a graph along with the line of best fit
4. For predicting the value of a point in the y-axis given a point in the x-axis, use predict() which takes user input and returns a prediction

## Reasoning Behind Certain Choices
I took the Z-score of x as denoted by x = (years - x_mean) / x_std because the value of x which is the year would overpower the other elements of the equation and would render them insignificant so taking the Z-score tones down the influence that x has such that b will be of similar magnitude and have a significant effect on the outcome.

## Limitations
There are possible cases of underfitting as this project only draws a straight line of best fit, so it will not be able to perfectly capture all the data and trends.

The current version of this project requires you to either download or add your data into a csv file manually.

## How It Can Be Improved 
Polynomial regression where x is raised to powers greater than one allows curves to be drawn, combat underfitting and thus better match the data/trend.

You can use the BeautifulSoup and Selenium libraries to parse websites and get live data from there instead of needing to manually download/add the data into a csv file, you can set up a website parser to write the data into your csv file.



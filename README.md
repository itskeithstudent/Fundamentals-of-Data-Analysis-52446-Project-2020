# Fundamentals-of-Data-Analysis-52446-Project-2020
Project on Linear Regression for predicting wind turbine power output as a result of wind speed using the provided dataset (which is included in the repository under powerproduction.csv). This is for the 2020 Project in the Fundamentals of Data Analysis module out of GMIT.

## Requirements for Project
Any required packages can be found in the requirements.txt file in this repository.

## Overview of Jupyter Notebook
For a more detailed view of the notebook please look at the Markdown sections throughout the notebook as they contain the most detail on the what's and why's of what is being done.

The notebook is ran linearly from top to bottom, at the start of the notebook are any imports required furthen down, the notebook first starts with a section quickly exploring the data in the csv file. After it was determined what the data looked like I moved on to using numpy's polyfit to generate an equation for the linear regression line and get it's coefficients and r squared score.
Following the numpy example I did the same using sklearn's LinearRegression and compared the results of this with the polyfit output.
After these pieces I take a tangent to implement splitting the data into testing and training sets to validate the model and compare it with the previous scores (unsurprisingly the model performs worse due to it being fitted with less data).
I also looked at improving the score of the model by cleaning up the dataframe and removing outliers.

Finally I encapsualted the earlier work on polyfit and with sklearn into their own respective functions, that take in dataframe columns as arguments.

## Commit practice
For commit messages I am following the convention laid out in this article - https://www.freecodecamp.org/news/writing-good-commit-messages-a-practical-guide/
Also from this thread - https://hashnode.com/post/which-commit-message-convention-do-you-use-at-work-ck3e4jbdd00zyo4s1h7mc7e0g
Following this practice is probably superflous but thought it would be a nice little extra to practice on with this project, this structure is to be followed from this readme commit onwards.

# Predictive-Analytics-with-Linear-Regression-Model
## Project Objective
The goal of this project is to run a linear regression model to predict the GPA score of students based on their SAT and Attandance. 

# Data
Our data comes from https://www.kaggle.com/luddarell/103-dummiescsv

# Important libraries used in this project:
1. Numpy
2. Pandas
3. Matplotlib.pyplot
4. Seaborn

# Exploratory Data Analysis
Our dataset contains 3 variables: GPA, SAT and Attandance. It also contains 84 observations. Initially, the Attandance variable is coded as "YES" for students who attended more than 75% or "NO" for those with attandance less than 75%. However, for the purpose of our Linear Regression Model, we needed to convert the Attandance to a dummy variable of 1 and 0, respectively. Summary statistics was also recorded and our data set doesn't have missing variables.

![no missing values](https://github.com/vimpicode/Predictive-Analytics-with-Linear-Regression-Model/blob/main/1.png)


# Data Visualization

[pairplot using seaborn]()

# Regression Model 


# Results and Clonclusion
The prediced GPA for Bernardo is 3.02 while for Maria is 3.2. Maria scored lower on her SAT but she attended 75% or more of the classes and she is expected to graduate with a GPA significantly higher than Bernardo. That makes sense.

If we used our previous model without the Dummy variable (GPA= 0.275 + 0.0017 * SAT) we would have predicted that Bernardo would have graduated with a GPA of 3.17 and Maria with 3.12. This would have be misleading. Therefore, it makes a lot of more sense why we needed the dummy variable to predict the GPA based on SAT scores factoring in "Attendance". 

Also, our study could be improved by expanding the number of observations and also the number of variables as such Male or Female, year at school and other features that would expand our analysis for a multiple linear regression. Perhaps that would also compell us to get a different data set given that the one used here is confined to those three variables.

# References

Kaggle for data source: https://www.kaggle.com/luddarell/103-dummiescsv

Linear Regression Analysis: http://onlinestatbook.com/2/regression/intro.html 
Pyhthon Documentation Guide: https://www.python.org/doc/av/




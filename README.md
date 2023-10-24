# Assignment - Advanced Regression 
> This assignment contains two parts. Part-1 is a programming assignment (to be submitted in a Jupyter notebook) whereas part-2 includes subjective questions (to be submitted in a PDF file).An assignment for coursework in the course Executive PG in Machine Learning and AI from IIIT Bangalore. 


## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Linear regression is performed on the dataset(train.csv).
- The project is done as part of coursework in the Machine Learning 2. 
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual value and flip them at a higher price. For the same purpose, the company has collected a data set from house sales in Australia. The data is provided in the csv file below.

The company is looking at prospective properties to buy to enter the market.

YoWe are required to build a regression model using regularization, so as to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

  - Which variables are significant in predicting the price of a house

  - How well those variables describe the price of a house

Also, determine the optimal value of lambda for ridge and lasso regression.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Optimal value of alpha of lasso regression is 50 and r2 score for optimal value of alpha is given below

R2 score for train : 0.9372405328256925
R2 score for test : 0.9254664123086983

Optimal value of alpha of ridge regression is 4 and r2 score for optimal value of alpha is given below

R2 score for train : 0.9371096095852764
R2 score for test : 0.9253982765709686

Optimal value of alpha is 1 for ridge regression on variables selected by lasso regession and r2 score for optimal value of alpha is given below

R2 score for train : 0.9392476999525955
R2 score for test : 0.9231948226312643

Lasso has successfully reduced variables by shrinking the variable coefficient to 0.There are 134 variables selected by lasso regression out of 255 variables.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used

- Pandas - version 1.5.3
- NumPy - version 1.23.5
- Seaborn - version 0.12.2
- MatplotLib - version 3.7.1
- Jupiter - 1.0.0
- Git - 2.41.0
- Github
- statsmodels
- sci-kit learn
- lasso regression
- ridge regression

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contributors

Arjun Kumar

<!-- Optional -->

<!-- ## License -->

## License

This project is open source and available without restrictions.

<!-- You don't have to include all sections - just the one's relevant to your project -->

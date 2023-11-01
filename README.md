# House Price Prediction Using Advanced Regression

> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house. Also, determine the optimal value of lambda for ridge and lasso regression.

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

- US-based housing company Surprise Housing is expanding into the Australian market using data analytics. They collect data from Australian house sales to buy properties below market value and sell them for a profit. To assess potential investments, a regression model with regularization is needed to predict property values accurately. This model will address two key questions: identifying significant variables affecting house prices and assessing their predictive power. Additionally, the optimal lambda values for ridge and lasso regression will be determined to fine-tune the model's performance. This analysis aims to help Surprise Housing make informed decisions about investing in Australian properties and maximize their returns in the new market.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- The optimal value of LAMBDA we got in case of Ridge and Lasso is :
  Lasso - 0.001
  Ridge - 7.0
- The r2 value we got in case of Ridge and Lasso is:
  Ridge - Train = 0.87 , Test = 0.86
  Lasso - Train = 0.88 , Test = 0.87
- We can clearly observe that the Mean Squared Error of Lasso is slightly lower than that of Ridge.
- Also since Lasso helps in feature reduction (as the coefficient value of one of the lasso's feature to be shrunk toward 0) and helps to increase model interpretation by taking the magnitude of the coefficients thus Lasso has a better edge over Ridge.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

Pandas - version 1.5.3
NumPy - version 1.23.5
Seaborn - version 0.12.2
MatplotLib - version 3.7.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course.

## Contact

Created by [Priyanshu Kumar](https://github.com/priyanshu966106) - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

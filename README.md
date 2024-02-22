# Random Forest vs. Decision Tree in Loan Repayment Prediction

## Project Overview
This project focuses on using LendingClub.com data from 2007-2010 to predict loan repayment outcomes. By analyzing borrower information, the goal is to assist investors in making informed decisions by identifying the likelihood of loan repayment.

## Decision Trees
- **Simplicity and Interpretability**: Decision Trees offer a straightforward approach for classification, making them easily interpretable.
- **Overfitting Prone**: They tend to overfit on the training data, which can reduce their effectiveness on unseen data.

## Random Forests
- **Accuracy**: By aggregating predictions from multiple decision trees, Random Forests generally achieve higher accuracy.
- **Overfitting Control**: They are less prone to overfitting compared to individual Decision Trees due to their ensemble approach.
- **Computational Complexity**: Requires more computational resources due to multiple trees, which can be a trade-off for improved accuracy.

## Comparison and Use Case
- **Use Case**: For the Lending Club project, where predicting loan repayment involves complex relationships and high-dimensional data, Random Forests are preferred for their robustness and ability to handle overfitting.
- **Decision Trees vs. Random Forests**: While Decision Trees provide a good starting point for understanding the factors influencing loan repayment, Random Forests offer a more accurate and generalizable model, making them better suited for this project.

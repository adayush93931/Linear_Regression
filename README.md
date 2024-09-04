# Linear Regression

Linear Regression is a statistical method used to model the relationship between a dependent variable and one or more independent variables by fitting a linear equation to observed data. It's one of the simplest and most commonly used regression techniques in machine learning.

## Table of Contents
- [Introduction](#introduction)
- [Mathematical Formulation](#mathematical-formulation)
- [Implementation in Python](#implementation-in-python)
- [Visualization](#visualization)
- [Applications](#applications)
- [References](#references)

## Introduction

Linear Regression aims to find the best-fitting straight line through the data points. This line is known as the regression line and is represented by the equation:

\[
y = mx + c
\]

where:
- \( y \) is the dependent variable
- \( x \) is the independent variable
- \( m \) is the slope of the line
- \( c \) is the y-intercept

## Mathematical Formulation

Given a dataset with \( n \) observations, the goal is to minimize the residual sum of squares between the observed targets and the targets predicted by the linear function:

\[
\text{Cost} = \frac{1}{n} \sum_{i=1}^{n} (y_i - (mx_i + c))^2
\]

Where:
- \( y_i \) is the actual value
- \( x_i \) is the input value
- \( m \) and \( c \) are the slope and intercept to be determined

The solution involves finding \( m \) and \( c \) that minimize the cost function using methods like Gradient Descent or Normal Equation.

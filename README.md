# Linear-Regression-with-NumPy-and-Python

## Project-Based Course Overview
Welcome to Project: Linear Regression with NumPy and Python. This is a project-based course which should take approximately 1.5 hours to finish. Before diving into the project, please take a look at the course objectives and structure:

## Course Objectives
In this course, we are going to focus on three learning objectives:

## Implement the gradient descent algorithm from scratch.
Perform univariate linear regression with Numpy and Python.
Create data visualizations and plots using matplotlib.
By the end of this course, you will be able to build linear regression models from scratch using NumPy and Python, without the use of machine learning frameworks such as scikit-learn and statsmodels.

## Course Structure
This course is divided into 3 parts:

## Course Overview: This introductory reading material.
Linear Regression with NumPy and Python: This is the hands on project that we will work on in Rhyme.
Graded Quiz: This is the final assignment that you need to pass in order to successfully complete the course and earn a Course Certificate.
Project Structure
The hands on project on Linear Regression with NumPy and Python is divided into the following tasks:

## Task 1: Introduction and Import Libraries
Introduction to the data set and the problem overview.
See a demo of the final product you will build by the end of this project.
Introduction to the Rhyme interface.
Import essential modules and helper functions from NumPy and Matplotlib.
## Task 2: Load the Data and Libraries
Load the dataset using pandas.
Explore the pandas dataframe using the head() and info() functions.
## Task 3: Visualize the Data
Before starting on any task, it is often useful to understand the data by visualizing it.
For this dataset, we can use a scatter plot using Seaborn to visualize the data, since it has only two variables: the profit and population.
## Task 4: Compute the Cost 𝐽(𝜃)
Let’s now take a look at the machinery that powers linear regression: Gradient Descent. 
We want to fit the linear regression parameters 𝜃 to our dataset using gradient descent.
The objective of linear regression is to minimize the cost function J(𝜃).
You can think of the cost as the error your model made in estimating a value.
## Task 5: Implement Gradient Descent from scratch in Python
Recall that the parameters of our model are the 𝜃_j values.
These are the values we will adjust to minimize the cost J(𝜃).
One way to do this is to use the batch gradient descent algorithm.
In batch gradient descent, each iteration performs the following update.
With each step of gradient descent, the parameters 𝜃_j come closer to the optimal values that will achieve the lowest cost J(𝜃).
## Task 6: Visualizing the Cost Function J(𝜃)
To better understand the cost function J(𝜃), we will plot the cost over a 2-dimensional grid of 𝜃_0 and 𝜃_1 values.

The purpose of this graph is to show you how J(𝜃) varies with changes in 𝜃_0 and 𝜃_1.
We can see that the cost function J(𝜃) is bowl-shaped and has a global minimum.
## Task 7: Plotting the Convergence
Let’s plot how the cost function varies with the number of iterations.
When we ran gradient descent previously, it returns the history of J(𝜃) values in a vector “costs”.
We will now plot the J values against the number of iterations.
## Task 8: Training Data with Univariate Linear Regression Fit
Now that we have correctly implemented and run gradient descent and arrived at the final parameters of our model, we can use these parameters to plot the linear fit. 
## Task 9: Inference using the optimized 𝜃 values
In this final task, let’s use our final values for 𝜃 to make predictions on profits in cities of 35,000 and 70,000 people.

## STA631 Portfolio

- Name: Durga Tummalapalli
- [Professor - STA631 Course](https://github.com/dykesb)

***This report provides an overview of my proficiency and understanding of the chapters covered in STA631 course***

## Regression Concepts

[Git Link for my repo](https://github.com/tdurgasaranya/activity01-course-tools)


In this chapter, I have learned about the fundamental concepts of regression analysis.
Regression is a statistical method used to create any relationship between a dependent variable and one or more independent variables. It helps us understand how changes in the independent variables affects the dependent variable.

## Simple Linear Regression

[Simple linear regression work Git Link](https://github.com/tdurgasaranya/activity02-slr)


In this chapter, I explored the concept of a simple linear regression, which is interdependent relation between a single independent variable and a dependent variable.
I learned how to fit a linear equation using Rscript with the data using the method of least squares. The key parameters in simple linear regression are the slope and the intercept of the regression line, which help us make predictions and understand the relationship between the variables.


## Multiple Linear Regression

[Multiple Linear Regression work Git Link](https://github.com/tdurgasaranya/activity03-mlr)

This chapter introduced me to the concepts of multiple linear regression, where we apply the concept of simple linear regression to include multiple independent variables rather than one variable.
I've learned how to fit a multiple regression model, interpret the coefficients and perform hypothesis tests to validate the significance of the variables.
Multiple linear regression helps to make accurate predictions when multiple factors influence the dependent variable.

Throughout these chapters, I gained practical knowledge with working on Git repository for sharing code files and inputs, working with R studio workbench by applying regression analysis concpets taught in this course.


# Logistic Regression

## Introduction to Logistic Regression

[Logistic regression model work Git link](https://github.com/tdurgasaranya/activity06-logistic-regression/tree/main/day01-logistic)


Logistic regression is a powerful statistical method used for binary classification tasks, where the outcome variable is categorical with two classes. I learned how logistic regression models the probability of an event occurring based on one or more predictor variables.


## Multinomial Regression

[Multinomial regression work Git Link](https://github.com/tdurgasaranya/activity06-logistic-regression/blob/main/day02-multinomial/Durga_activity06-multinomial.Rmd)

In this section, I explored the concepts of logistic regression to handle multi-class classification problems. Multinomial regression is used when the outcome variable has more than two categorical values or variables.
I've learned how to set up and interpret multinomial logistic regression models, which help us understand the relationships between the predictors and multiple response categories.


## Generalized Linear Models (GLMs)

Generalized Linear Models (GLMs) provide a flexible framework that includes both linear regression and logistic regression as special cases. I learned about the theoretical foundation of GLMs and how they handle different types of response variables (e.g., continuous, binary, count data).

Throughout these chapters, I gained a deep understanding of logistic regression, multinomial regression, and generalized linear models.


# Resampling & Cross-validation

## Introduction to Resampling & Cross-validation

[Mini project work Git Link](https://github.com/tdurgasaranya/activity08-mini-competition)

In this chapter, I explored the concepts of resampling methods, which are drawing sample data points to obtain more estimates of model performance. Cross-validation is a widely used resampling technique that partitions the data into training and testing sets, allowing us to evaluate the model on unseen data.

## Model Selection & Multiple Testing

- Model Selection:
Model selection is an important step in any prediction testing, where we compare and choose the best-performing model from a set of candidate models. I've learned about model selection techniques, such as stepwise regression.
This method helps us to identify the most appropriate model that balances complexity and predictive accuracy of the model.

- Multiple Testing:
I've explored multiple testing correction methods like "False Discovery Rate (FDR)".
I gained practical working examples in resampling techniques, cross-validation, model selection, and multiple testing corrections.


## Inventory - prediction

[Inventory project work Git Link](https://github.com/tdurgasaranya/activity08-mini-competition/blob/main/competition-files/mini-competition.Rmd)

- Challenging task with a depth of conceptual learning although results arent well done, on a future work completion basis:

Here are some key takeaway pointers on predicting inventory from this project from my learnings:
  
- Time series modeling is useful for forecasting future inventory needs based on historical demand data.

- We can fit a separate time series model for each product or item number, taking advantage of R's grouping and piping workflow. This accounts for trends and seasonality unique to each product.

- Good inventory forecasts require sufficient historical data. More data points lead to more robust models and accurate predictions.

- Forecasts need frequent retraining as new demand data comes in. Models should be refreshed periodically to effectively capture latest trends.


# Bootstrap Modeling

[Boot Strapping work Git link](https://github.com/tdurgasaranya/activity09-bootstrapping)

Bootstrap modeling, is a resampling technique used to estimate the variability of a statistical model's parameters and predictions. Bootstrap is particularly useful when the underlying data distribution is complex or unknown.

## Key Concepts learnt from Bootstrap Sampling chapter:

- Bootstrap Statistics:
  With the bootstrap samples we can compute mean, standard deviation, confidence intervals.
- Bootstrap Confidence Intervals
- Model Validation:
   Bootstrap is used to assess the performance of any prediction model. Through bootstrap-based validation, we can
   estimate the model's predictive accuracy and assess its ability to generalize to unseen data.

From this chapter, I gained the fundamentals understanding of the principles and applications of bootstrap modeling. This resampling technique is a valuable addition to my statistical toolkit, helping me to validate the performance of complex models in real-world data analysis.


***Challenges encountered while working on the below concepts of the course***

- Regression Concepts:

   Understanding and interpreting regression coefficients and statistical significance tests might be challenging for beginners in R
   scripting with statistics.
   Additionally, grasping the concept of multicollinearity and dealing with it appropriately in multiple regression can be complex.
  
- Simple Linear Regression:
   While the concept of simple linear regression is relatively straightforward, accurately interpreting the regression output and
   determining whether the model fits the data well might be a little task to successfully accomplish prediction model.

- Multiple Linear Regression:
   Extending simple linear regression to multiple predictors can be challenging, especially when dealing with high-dimensional data or
   correlated predictors. Selecting the most relevant variables and addressing potential multicollinearity can be complex tasks.

- Logistic Regression:
   Interpreting odds ratios, handling imbalanced datasets and understanding the output of logistic regression can be challenging.

- Multinomial Regression:
   Understanding the theory behind multinomial regression and interpreting its results can be difficult, especially when dealing with more
   than two response categories.
  

- Model Selection & Multiple Testing:
   Deciding on the best model among many candidates and avoiding overfitting can be difficult in model selection.
   Similarly, understanding and implementing multiple testing corrections to control false discoveries can be complex.


Ways to integrate my learnings from STA631 course in my current/future job:

- Applying these statistical techniques like regression, hypothesis testing to gain  more insights from organizational data.

- Improving data visualizations and reporting solutions by integrating concepts like statistical significance, confidence intervals.

- Identifying opportunities to provide statistical consulting to my colleagues.


### Data Feminism learnings:


- A new feminist approach to data science and AI that challenges existing biases, power imbalances, and inequities in how data is collected, analyzed, and used. 

- Argues that data and algorithms are not objective - they reflect the priorities, biases, and values of those who create them.

- Suggests 7 principles for ethical data science: 1) Examine power 2) Challenge power 3) Elevate emotion and embodiment 4) Rethink binaries and hierarchies 5) Embrace pluralism 6) Consider context 7) Make labor visible.

- To include diverse perspectives and lived experiences results in better, more ethical and just data science for society.


### Overall Summary:

I am confident and proficient in these below concepts:
- Data loading, Data manupulation in R studio, Data transforming with Git to R
- Linear Regression concept, Data dimensions
- Distribution of values with two variable comparisions
- Scatter plot, Histogram distribution
- Multilinear regression, logistic regression
- Testing and accuracy in prediction
- Timeseries modeling
- To find the coefficiency of two variable determining the strength of linearity
- To find the error rate and prediction


***My statistics portfolio reflects my proficiency in regression concepts and applications, showcasing my ability to handle data analysis
tasks and draw valuable conclusions, my ability to handle diverse data analysis tasks using statistical models***


I've consistently engaged and demonstrated my ability to apply the knowledge and concepts learnt from the class and the textbook.

I have been actively engaging in the Teams, online class discussions and trying to contribute to class activities (Breakout rooms),
  solidifying my understanding and enhancing my learning experience.

### References of my statistical learnings and future resources:

- [STA 631 course textbook](https://www.statlearning.com/)
- [Towards Data Science](https://towardsdatascience.com/)
- [Excercise solutions](https://github.com/asadoughi/stat-learning)
- [Libre Text Stats](https://stats.libretexts.org/Bookshelves/Introductory_Statistics/Introductory_Statistics_(Shafer_and_Zhang)/10%3A_Correlation_and_Regression/10.01%3A_Linear_Relationships_Between_Variables)

- Youtube learnings, AI based learning
  

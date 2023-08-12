## STA631 Portfolio

- Name: Durga Tummalapalli

- [Professor - STA631 Course](https://github.com/dykesb)

***This report provides an overview of my proficiency and understanding of the chapters covered in STA631 course***

### Course Learning Objectives:

1. ***Describing probability as a foundation of statistical modeling, including inference and maximum likelihood estimation:***
   

- Example: For an inventory prediction mini project, I tried to create a prediction model for future inventory product sales by analyzing historical sales data for different products.
  
- I tried to create a predictive model using regression, including multiple linear regression. I tried to estimate coefficients to model how variables like products of different categories are sold in maximum number of weeks. I am working on to inlcude Maximum Likelihood Estimation (MLE), and trying to find the coefficient values that maximizes the probability of observing the given historic sales data.
  
- In this project, I leveraged to leaen and implement probability theory to interpret historic product sales patterns and guide the model estimation process.
- My analysis demonstrates skills in demand forecasting, statistical inference, and predictive modeling for inventory optimization.


2. ***Determine and apply the appropriate generalized linear model for a specific data context***
   
- Example: "Resume Shortlisting" candidate experience based on years of experience, race and demographic factors to illustrate the
  generalized linear model (GLM) for a resume data context.

- I analyzed applicants data using a generalized linear model (GLM) based on a csv file provided on survey demographic information from candidate experiences. The goal was to predict highest number of resume shortlisting based on candidate experience and other factors
- I knew a GLM was appropriate as taught in course because the outcome was binary (shortlisted or not) and the predictor was a numerical variable (years of experience). 
- I used statistical software to fit a GLM on the data, which estimated mathematical relationships between experience and the probability of being shortlisted. 

By interpreting these estimated relationships, I could understand how experience impacts the likelihood of shortlisting. I am also trying to include the model to predict shortlisting probabilities for candidates with different levels of experience. 

This demonstrates my learning skills in applying statistical learning techniques to build models that drive business processes and decisions. The GLM enabled me to predict outcomes based on applicants


3. ***Conduct model selection for a set of candidate models***

Example: For a sales inventory prediction project, I am developing models to forecast future products inventory. 
- So far, I have collected historical sales data and promotional information to train candidate models. 

I tried to fit a Linear Regression model on the training data and evaluated its performance on a validation set using error metrics like Mean Absolute Error. 

- Going forward, I plan to train and evaluate additional models, like Random Forest, to compare against the Linear Regression approach. By systematically evaluating multiple models, I aim to determine the best statistical learning method for accurately forecasting inventory demand.

The additional steps to this project would be to:

- Preprocess and split the data into training/validation sets
- Train a Random Forest model and tune hyperparameters
- Evaluate and compare performance to the Linear Regression model
- Use cross-validation to further validate the top model

By completing a structured model selection process, I will select the approach that minimizes forecasting errors on new data. This will help the retailer optimize their inventory planning.

In summary, this project demonstrates my ability to find best practices to determine the optimal modeling technique for a business forecasting need. I am applying these statistical learning methods to achieve an effective inventory prediction model.

4. ***Communicate the results of statistical models to a general audience***

- Inventory Prediction: I tried to fit a line chart to demonstrate how the model accurately forecasted product demand based on historical sales data, predicting inventory planning. 

- Logistic Regression: I used a bar chart to explain how the model predicts candidate resume shortlisting based on demographics, years of experience.

- Multilinear regression model: Quantitative explanatory analysis:
I tried to create 3D plots while working on a Multiple Linear Regression example that represents the estimated model prediction data points on the plot that would help the general audience to understand 3D plot visualization.

- Bootstrapping: Trying to incoporate histogram illustrations, to convey how bootstrapping provides confidence intervals for inputs to the dataset.

In summary, I am trying to leverage various visualization types for statistical analysis performed like - line charts, bar charts, scatter plots, histograms, 3D plot and box plots - to communicate model results, insights, and business impacts across these projects in a simplified yet compelling way. The specific visuals help to convey key information to general audiences.


5. ***Efficient use of  programming software (R Studio/workbench) to achieve the results for works done:***

- Inventory Product sales prediction
  I used R to visualize and evaluate forecasts based on historical sales data to predict product demand.

- Resume shortlisting candidates experience project
  I am using R workbench to assess a model predicting shortlisting based on resume skills using accuracy metrics.
  I am trying to leverage R scripting to evaluate a model forecasting using graphics and charts.

- Bootstrapping Confidence Intervals
  I used and learnt how to estimate confidence intervals for sales forecasts on R studio workbench

In summary, I am  trying to demonstrate fundamental skills in R including data visualization, model evaluation, forecasting, estimation, and statistical testing for mini projects like involving sales prediction inventory, resume shortlisting.
I focused on fundamental techniques to prepare, assess, and interpret statistical models.


### Team collaboration/contribution:

1. I actively participated in team channels, exchanging ideas and insights with team members on mini projects. We reviewed each other's work, celebrated accomplishments, and provided constructive feedback to help improve our individual work results.

2. I collaborated with peers on course projects, pairing up to complete assignments. We divided up tasks, combined our work, and learned from each other's approaches. These collaborations allowed us to produce higher quality deliverables.

3. I shared a job opportunity and relevant article with one of the program peers that matched their skills and interests, helping connect her with openings.

4. I did not just speak up with my own perspectives during team discussions but also made an effort to listen to others' viewpoints. Reflecting on diverse opinions leads to better solutions. 

5. I received feedback from teammates to strengthen my analysis and communication skills. Incorporating their suggestions helped me substantially improve my projects and presentations.

Overall, I leveraged the collaborative environment to exchange knowledge, motivate peers, provide mutually beneficial feedback, and learn from the diversity of backgrounds and thoughts. 



## Regression Concepts

[Git Link for repo](https://github.com/tdurgasaranya/activity01-course-tools)


In this chapter, I have learned about the fundamental concepts of regression analysis.
Regression is a statistical method used to create any relationship between a dependent variable and one or more independent variables. It helps us understand how changes in the independent variables affects the dependent variable.

## Simple Linear Regression

[Simple linear regression Git Link work](https://github.com/tdurgasaranya/activity02-slr)


In this chapter, I explored the concept of a simple linear regression, which is interdependent relation between a single independent variable and a dependent variable.
I learned how to fit a linear equation using Rscript with the data using the method of least squares. The key parameters in simple linear regression are the slope and the intercept of the regression line, which help us make predictions and understand the relationship between the variables.


## Multiple Linear Regression

[Multiple Linear Regression Git work Link](https://github.com/tdurgasaranya/activity03-mlr)

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

- Validations on data and algorithms are not objective - they're based on the priorities, biases, and values of those who create them.

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
  

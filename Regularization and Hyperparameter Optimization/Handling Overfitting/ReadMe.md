
## Situation
The objective of this exercise involves applying the concepts learned in Ridge and Lasso models to address overfitting within a real-world dataset. The dataset aims to predict the number of shares a news article might accumulate, considering diverse attributes encompassing the article's content, structure, and publication timings.
## Task
Perform the appropriate preprocessing steps on the dataset and subsequently train a model that avoids overfitting.
## Action
Initially, I delved into understanding various aspects of the dataset, including the target variable, column types, presence of missing values, and the distribution of columns alongside the target variable. Additionally, I employed a logarithmic function to address skewness in the target variable.

Proceeding with preprocessing, I identified and resolved colinearity issues by dropping one of the columns in colinear pairs. Following these steps, I trained a linear regression model, but the achieved score was unsatisfactory due to overfitting.

To mitigate overfitting, I turned to the Ridge model and implemented GridSearchCV to determine the best alpha value. Subsequently, I conducted cross-validation to evaluate score variation.

Despite the score remaining suboptimal, successfully mitigating overfitting was noteworthy. This issue stemmed from the dataset having fewer rows than columns, which was an interesting discovery.

## Result
The goal here was to work with a real-world dataset, sorting out the necessary preprocessing steps, and training a model while tackling overfitting. This was achieved by employing the Ridge model with an appropriate alpha value in the next exercises I will focus on having a good score and no overfitting.
 
## Acknowledgements

 - [This exercise comes from my training in Jedha Bootcamp](https://www.jedha.co/formations/formation-data-scientist)
 




## Situation

In this exercise, I worked with a real-world dataset that focused on wine quality. The task was to predict or estimate the quality of the wine using its specific characteristics. Essentially, the goal was to use the dataset's information on various aspects of the wine, like acidity, residual sugar, alcohol content, etc., to create a model that could accurately predict the quality rating of the wine.
## Task
Getting to know the dataset I am handling . Then, teach a model to recognize different quality types od wine.
## Action

Initially, I delved into understanding various aspects of the dataset, such as the target variable, the types of columns present, and whether there were any missing data. I used histograms to explore how different characteristics of the wine might affect its quality. Handling an imbalanced dataset, I kept this in mind throughout the model evaluation process.

Next, I prepped the data for analysis. I began by training a baseline model, focusing on the column that was most predictive of wine quality. Then, I constructed a dummy model that predicted the most frequently occurring wine quality, comparing its performance to the baseline model. The dummy model didn't perform as well, indicating the baseline model's score. However, I noticed a room for improvement in the baseline model's score. By incorporating all the wine characteristics into a new model, I observed a significant improvement in the score and identified the coefficients contributing to this interesting result.

Unsatisfied with stopping there, I decided to enhance the score further. Employing feature selection using SequentialFeatureSelector library , the score increased, validating the efficacy of the approach! 

## Result


The goal was to predict wine quality based on its characteristics. To achieve this, I conducted exploratory data analysis (EDA) to understand the dataset better. I trained multiple models to find one with an interesting score that effectively addressed the problem of predicting wine quality based on its features.

## Acknowledgements

 - [This exercise comes from my training in Jedha Bootcamp](https://www.jedha.co/formations/formation-data-scientist)
 



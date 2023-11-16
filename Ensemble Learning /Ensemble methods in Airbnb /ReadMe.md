
## Situation
The goal of this project is to predict the price of the airbnb based on the characteristics of the dataset. 

## Task
Getting to know the dataset I am handling . Then, train models using bagging and boosting techniques in order to predict the right price of the airbnb.

## Action

I started by getting acquainted with the dataset, dropping irrelevant columns, handling missing values, and ensuring that the columns' types corresponded accurately to their data. If there was a mismatch, I performed the necessary preprocessing steps to rectify it, also addressing the skewness in the target variable by applying a logarithmic function to preserve data integrity.

During my exploratory data analysis (EDA), I identified columns strongly correlated with the target variable. Subsequently, I trained various models: AdaBoost with and without GridSearchCV, XGBoost with default parameters, and a decision tree regressor. The model that stood out with the highest score was XGBoost.

In addition, I experimented with ensemble methods like voting and stacking. For this, I used SVM with an RBF kernel, linear regression, and decision tree as base estimators. Ensuring the stacking results were not redundant, I thoroughly evaluated and compared these models. My conclusion was that XGBoost outperformed the others, delivering the most promising results.



## Result
The goal of this project was to utilize bagging and boosting techniques, alongside voting and stacking methodologies, to predict Airbnb prices. This objective was successfully achieved, yielding an intriguing score.

## Acknowledgements

 - [This exercise comes from my training in Jedha Bootcamp](https://www.jedha.co/formations/formation-data-scientist)
 



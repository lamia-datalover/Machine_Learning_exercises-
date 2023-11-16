
## Situation
The goal of this project is to predict uber prices based on many characteristics. 

## Task
Getting to know the dataset I am handling . Then, teach a model to predict the uber price and display the important features that led to that prediction.

## Action
Initially, I delved into understanding various aspects of the dataset, like the target variable, column types, and checking for any missing data or skewness in the target variable distribution.

Following this, I performed preprocessing steps, which involved removing unnecessary columns, handling outliers, and excluding rows with negative values. Subsequently, I trained a baseline model that didn't perform satisfactorily. To improve the results, I opted for a bagging technique using a decision tree regressor, which exhibited better performance. However, it showed signs of overfitting, prompting me to address this issue through GridSearchCV. This helped me find the best hyperparameter values, mitigating the overfitting problem.

Finally, I showcased the coefficients that contributed significantly to achieving remarkable results in the model predictions.

## Result

The objective was to accurately predict the price of Uber rides. To achieve this, I focused on implementing the necessary preprocessing steps to ensure the data was meaningful for analysis. Subsequently, I trained two models, with the latter demonstrating an impressive score that successfully met the goal of predicting Uber ride prices.

## Acknowledgements

 - [This exercise comes from my training in Jedha Bootcamp](https://www.jedha.co/formations/formation-data-scientist)
 



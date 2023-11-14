## Situation 
The dataset of this exercise contains all the data about the californian housing market , the goal was to predict the price of the housing in the californian state  .
## Task
My task was to train a model using the right columns and a logical approach to predict the price of the housing.
## Action
To begin, I acquainted myself with the dataset by understanding its shape, the available columns, and detecting the percentage of missing values in each column. Additionally, I employed a correlation matrix and a scatter matrix to identify columns strongly correlated with the target variable.

Initially, I trained a baseline linear regression model using the column most strongly correlated with the target variable as the explanatory variable. However, the resulting score was unimpressive. Consequently, I pivoted to another approach, training a different linear regression model using the remaining columns. This strategy proved more promising as the score increased. This improvement stemmed from the model's ability to explore and leverage the best combination of all available columns.
## Result 
Attaining a high score with the trained model signifies its successful comprehension of the dataset's crucial characteristics and its potential to generalize findings to unseen data. This experience taught me the importance of not settling for a score but consistently striving to improve it. I learned to think logically about what could contribute to achieving a more interesting score, which, in my case, involved incorporating additional columns.

Ultimately, I presented the feature importance in a DataFrame to illustrate which columns significantly influenced the model to achieve the high score, offering insights into their impact.
## Acknowledgements

 - [This exercice comes from my training in Jedha Bootcamp](https://www.jedha.co/formations/formation-data-scientist)
 

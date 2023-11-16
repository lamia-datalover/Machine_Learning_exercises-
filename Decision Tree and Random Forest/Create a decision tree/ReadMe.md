
## Situation
The goal of this exercise is to learn how to train a decision tree classifier model using entropy and gini impurity criteria also fight overfitting using the right hyperparameters. 
## Task
Getting to know the dataset I am handling . Then, teach a model to recognize different  types of balance using the characteristics of the dataset.
## Action

Initially, I delved into understanding various aspects of the dataset, such as the target variable, the types of columns present, and whether there were any missing data.
Then I trained a decision tree classifier using entropy and gini impurity criteria. Finally, I compared the two scores and found them kind of equal but I had an overfitting problem .
That I solved by using a GridSearchCV to find the best max_depth and max_simple_split values .

## Result
The goal was to predict the balance of the tree based on its characteristics.The final score is interesting for all the categories of the balance (target variable) but the category 0 due to the fact that the model does not have enough examples to learn to classify correctly this category .

## Acknowledgements

 - [This exercise comes from my training in Jedha Bootcamp](https://www.jedha.co/formations/formation-data-scientist)
 



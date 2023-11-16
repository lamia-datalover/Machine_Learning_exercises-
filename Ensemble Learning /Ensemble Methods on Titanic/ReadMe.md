
## Situation
The goal of this project is to predict if a passenger survived in the titanic or not. 

## Task
Getting to know the dataset I am handling . Then, train models using bagging and boosting technics.

## Action

Initially, I familiarized myself with different aspects of the dataset, similar to the process I followed while working with the Titanic dataset in this exercise: https://github.com/lamia-datalover/Machine_Learning_exercises-/tree/main/Preprocessing .

Following that, I trained a random forest classifier and utilized GridSearchCV to fight overfitting. Subsequently, I trained a bagging of decision tree classifier with the same parameters as the random forest classifier to compare their scores.

Moving forward, I trained additional models including an AdaBoost classifier, a Gradient Boosting classifier, and an XGBoost classifier. For each model, I employed hyperparameter tuning to address potential overfitting issues common in bagging and boosting methods.

The goal of training these diverse models was to compare their respective scores and determine the most effective performer. In my case, I found that the Random Forest Classifier exhibited the best score on unseen data.

## Result

The objective of this project was to apply bagging and boosting techniques to a previous project (Titanic survival) to assess model performance and address overfitting using GridSearchCV. This objective was successfully achieved.

## Acknowledgements

 - [This exercise comes from my training in Jedha Bootcamp](https://www.jedha.co/formations/formation-data-scientist)
 



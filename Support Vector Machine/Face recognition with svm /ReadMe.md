
## Situation
The goal of this project is to classify pictures in the category representing the subject present in the picture . 

## Task
Getting to know the dataset I am handling . Then, teach the SVM model to classify the pictures.

## Action
Initially, I delved into understanding different aspects of the dataset obtained from 'fetch_lfw_people', focusing on the target variable and the relevant data for classifying the target variable.

Next, I trained an SVM model using the RBF kernel, implementing a balanced criterion to ensure equal importance across all categories. While the initial model showed promising scores, it suffered from overfitting. To address this, I used GridSearchCV to find the appropriate values for C and gamma, resulting in improved scores without overfitting. 

## Result

The SVM model, employing an RBF kernel and GridSearchCV to combat overfitting, effectively classified the majority of the images

## Acknowledgements

 - [This exercise comes from my training in Jedha Bootcamp](https://www.jedha.co/formations/formation-data-scientist)
 



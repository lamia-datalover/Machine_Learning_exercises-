
## Situation
The goal of this exercise is to apply the concepts covered in theoretical classes, such as bootstrapping, hold-out score, resubstitution score, cross-validation, hyperparameter optimization, and the three-way hold-out method . 
## Task 
Evaluating the model using different techniques datailed in action section.
## Action
In the initial phase of the exercise, the focus was on exploratory data analysis (EDA) to understand the distribution within the well-known Iris dataset. The subsequent steps involved checking for missing values or useless columns before proceeding to training a model for flower type classification. To minimize model bias, it was crucial to use the stratify keyword while splitting the data into test and train sets, ensuring equal distribution for a fair hold-out score and resubstitution score while avoiding bias.

Exploring bootstrapping, the exercise covered the creation of various dataset samples and evaluating models trained on these samples using out-of-bag data.

Lastly, using a validation set for model evaluation demonstrated the efficiency of this method, particularly with large datasets. This approach proved faster than relying solely on a test set to assess model performance .

## Result
The objective of this exercise was to explore and grasp new techniques for evaluating a model. It was an engaging experience to understand when and how to effectively apply these techniques in practice.

## Acknowledgements

 - [This exercise comes from my training in Jedha Bootcamp](https://www.jedha.co/formations/formation-data-scientist)
 



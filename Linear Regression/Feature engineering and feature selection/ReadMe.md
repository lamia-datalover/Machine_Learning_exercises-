
## Situation
The dataset used in this exercise encompasses comprehensive data concerning the Californian housing market. The primary objective wasn't solely to predict housing prices in California, as in the initial phase, but also to engage in feature engineering aimed at selecting the most optimal features .
## Task
My assignment involved training a model to predict housing prices using various approaches from the initial section (found in the other folder) as well as employing a logical approach to achieve accurate price predictions for the housing dataset.
## Action
Initially, I addressed outliers by employing a mask on the dataset, omitting them from the analysis. Following this, I augmented the dataset by adding columns that encompassed mathematical transformations (such as X^2, X^3, X^4, 1/X, 1/X^2) for each column in the dataset. The intent was to enhance the model's performance based on previous attempts, but this strategy didn't yield the desired improvement.

Subsequently, I explored an alternative method using the SequentialFeatureSelector library. This approach involved selecting the best columns that contributed to improved model performance. Notably, employing this technique resulted in an increased score without causing overfitting, making this approach particularly intriguing.
## Result
Achieving a compelling score with the trained model indicates its ability to grasp essential dataset characteristics and potentially generalize findings to new, unseen data. This experience emphasized the significance of feature selection in enhancing the model's performance. It underscored the importance of enabling the model to autonomously determine the columns it utilizes to learn dataset traits, ultimately improving its predictive capabilities.
 
## Acknowledgements

 - [This exercise comes from my training in Jedha Bootcamp](https://www.jedha.co/formations/formation-data-scientist)
 


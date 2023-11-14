
## Situation
The dataset comprises genetic data, a substantial collection spanning 20,532 columns. The objective centered around comprehending Ridge and Lasso regression techniques by comparing and studying the impact of the regularization parameter, alpha, in both methods. 
## Task
Train both a Ridge and Lasso model to understand the distinctions between the two and know the significance of selecting the appropriate alpha value.
## Action
Initially, I familiarized myself with the dataset components: the target variable, column types, and the presence of missing values. Subsequently, I trained a Ridge model using various alpha values. I observed that as alpha increased, the model's score decreased due to reduced variance and increased bias.

Similar conclusions arose when training a Lasso model with different alpha values. However, unlike Ridge, the Lasso model employs fewer coefficients by zeroing some, effectively conserving memory.

To determine the best alpha value for optimal performance, I employed GridSearchCV, which identified the alpha value associated with the highest score .

## Result
Obtaining an impressive score with the trained model demonstrates its capacity to capture crucial dataset characteristics and potentially apply these insights to new, unseen data. This experience underscored the critical role of selecting the appropriate alpha values when employing Ridge and Lasso models. By doing so, we achieve a balance between variance and bias. It's essential to note that the objective isn't solely to decrease variance to combat overfitting, as overfitting tends to be more common than underfitting. The ultimate aim is to strike a balance between these two factors for optimal model performance!
 
## Acknowledgements

 - [This exercise comes from my training in Jedha Bootcamp](https://www.jedha.co/formations/formation-data-scientist)
 



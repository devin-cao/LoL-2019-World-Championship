# LoL-2019-World-Championship
A logistical regression model is created to determine the most important game variables in a victory.
The datasets are from Kaggle: https://www.kaggle.com/ilyadziamidovich/league-of-legends-world-championship-2019.

Two of the datasets are joined and analyzed to determine which factors heavily correlates to a game victory.
The dataset is from Kaggle and is fairly clean and organized. Some values were missing but easily deleted.

Conclusions:
This logistical regression model has an accuracy of approximately 97% in predicting game result using the chosen independent variables. 
The results are expected as Baron kills and Towers destroyed correlate greatly to a victory. 
With Baron, teams are able to siege effectively and overwhelm the opponents. 
Number of towers destroyed are expected to increase once the base is open. 
However, there are some variables that have a higher p-value than 0.05, and therefore is insignificant. 
It is also interesting that the dragon with the highest odds of victory is Air Drake.

Future Works:
More feature engineering should be performed.
Add more visualization plots.
Create a multiple linear regression model to find other underlying relationships.

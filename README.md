## PubG
BATTLEGROUNDS is a competitive survival shooter. Players are dropped into a wide, open area, and they must fight to the death - all while the battlefield shrinks, adding pressure to all in its grip. Use a variety of interesting weapons and vehicles amid the BATTLEGROUNDS. Player Unknown's Battlegrounds is an online multiplayer battle royal game. The game features the last man standing deathmatch mode, in which one hundred players fight against each other in a battle royal.

People can play as individuals or as a team of up to 4 players. There are various strategies that people follow in order to win the game. We as a team aim to analyze these features of the game for every individual in our dataset and answer 2 important questions:

1) To predict the final ranks of players based on their characteristics.

2) To identify the strategies used by top rank players to survive in the game.




# Dataset
Obtained dataset from Kaggle, it has almost 4.45 million rows and 29 columns in the training dataset. And 1.93 million rows and 28 columns in testing dataset. The columns in the dataset are features of the game example boosts - it is the number of boost items used.
headshot kills - this indicates the number of times an enemy member was killed because of being shot in the head. Each row consists of the post-games statistics of individual players in the game.

# Problem Statement
1) What are the top 3 causes of death?
For example: Is it bleeding to death (Down and out) or because they have been hit by a certain weapon.
2) The players are prone to death in which particular area of the battlefield.
3) To observe a common pattern between the winners of the game.
4) To detect the cheaters in the game.
5) To find the correlation between variables.
6) To observe the number of enemies that have to be killed in a particular mode(solo,duo,squad) to win the game.

# Models
We will be implementing the following models for our analysis and predictions:
Linear Regression: Since there are many continuous variables in the dataset we chose this method to predict the value of target variable. 
LightGBM: As our dataset is in millions we chose this method because of lower memory consumption and higher accuracy result.
Principal Component Analysis: Since we have 29 variables in our dataset we need to perform dimension reduction, hence we chose this method.
Random Forest: We used Random Forest to built multiple decision trees and merged them together to get an accurate and stable mean prediction.






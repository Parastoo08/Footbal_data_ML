# Footbal_data_ML
There are two notebooks in jupyter. 
1. EXPLORING THE FIRST SEASON
2. PREDICTING THE SECOND SEASON
As it is mentioned there are many techniques to predict the outcome of professional football
matches. Traditionally the number of goals scored by each team was used as a base measure
for evaluating a team’s performance and estimating future results. 
There are two main approach for that: Poisson distribution and the Fenwick rating based on shots and missed shots.
However, the number of goals possesses an important random element which leads to large
inconsistencies in many games between a team’s performance and number of goals scored or
conceded. Hence, I modeled match results (win/draw/loss) directly rather than predicting
the match scores and using them to create match result probabilities. I used a four different
classifier model. In order to increase the accuracy of the models I created new features,
 namely, the attack and defense home and away team strength, Home and away team chance to win.
ANYTHING ELSE?
In the second notebook, I used a completely different method to create a detailed table league

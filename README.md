# pokemon_data
Analyzing the pokemon dataset from:
https://www.kaggle.com/abcsds/pokemon

Skill Keywords: Python(Jupyter, Pandas, Matplotlib/Seaborn, Numpy), Data Cleaning, Exploratory data analysis (Bivariate analysis)

Questions asked:
# 1. Do the stats of each pokemon generation inflate? Are generations balanced against eachother?
# 2. Are the pokemon balanced between "type1", eg. fire/grass etc.

# EDA (Exploratory data analysis):
# - Bivariate analysis: Pairwise plot of relationship between variables



Conclusions:
1. There is stat inflation between generations 1-6, therefor the generations are not balanced. Future Work: How rare Pokemon are has not been considered. Perhaps the stronger Pokemon of later generations are more rare, meaning the mean pokemon by probability of each generation might be balanced.

2. Pokemon are not balanced between the "Type 1" characteristic (Fire/Grass/Dragon etc..) Dragon was the strongest Type, while bug was the weakest.

Exploratory data analysis:
From the Pairplot it can be seen that there are no strong relations between any variable. In general: "If a Pokemon's stat is high, it is likely all its other stats are high as well". I expected Pokemon with high "Attack" to have low "Defense", but it seems the opposite is true.

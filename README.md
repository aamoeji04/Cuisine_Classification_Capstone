# Cuisine_Classification_Capstone
By: Ijeoma N. Akamnonu

![img](./images/food_security.png)

## Business Problem
Build a model that can accurately classify a cuisine based on key words in a given recipe.
WHY?
Gain insights and make patterns between different cuisines through classification
Use those insights and patterns to generate novel, possibly delicious recipes


## Data
The data used for this classification project was scrapped and concatenated from 2 different websites, both of which are affilitated with [British Broadcasting Corporation](https://www.bbc.com/). 900 recipes were collected in total from [BBC Good Food](https://www.bbcgoodfood.com/recipes/category/all-cuisines) and [BBC Food](https://www.bbc.co.uk/food/cuisines). 

When we first take a look at our data, we can see the distribution of class that we have. 
**Cuisines Class Distribution**
![img](./images/cuisines_dist.PNG)

From the bar graph above, we can clearly see that a majority of our data consists of mexican recipes and comparitavelty there is a severe lack of caribbean recipes. Through further exploratory data analysis, we can generate more insights about our data. 

### Insights

## Methods
## Results
## Conclusions
# Next Steps 
### More Data Collection
1. Collecting more data is always a great way to enchance any model 
2. More data will lead to more, better features to help our model
3. Meticulous remove more useless stopwords (further data cleaning)
4. From more cleaning, generate more insights to, again, help our model
### Neural Networks
After bettering what our model has to work with and optimizing it to get the best F1 or accuracy score, we can move onto the creating a handy web app.
5. Implement Naural Language Generation with the use of Markovify
6. Utilize StreamLit to launch a simple web app that can take in a list of ingredients and out put a novel recipe
# Big-Basket-Cart-Prediction Using Association Rule Learning:

GOAL: To develop a Machine Learning algorithm to predict which two food products is the consumer going to buy together based on the given dataset.

STEPS :
Using the APRIORI Algorithm to predict the food product consumers might buy.
1. Data Pre-Processing:
   1. Importing Libraries.
   2. importing Dataset,.
2. Importing Apriori from Apyori.
3. Setting a minimum SUPPORT and CONFIDENCE.
4. Collecting all the subsets in transactions having higher support than minimum support.
5. Collecting all the rules of these subsets having higher confidence than minimum confidence.
6. Sorting the rules by decreasing LIFT.
7. Printing the raw results.
8. Printing results in a proper format.
9. Displaying the Top 10 food products with the highest relationship with each other.

CONCLUSION:
The top 3 food products that have the highest possibility of being bought together based on APRIORI algorithm are:
1. neck rest & trolly bag
2. pasta & mushroom
3. ginger garlic paste & chicken

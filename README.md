# Big-Basket-Cart-Prediction

GOAL : To develop a Machine Learning algorithm to predict which food product is the consumer going to buy based on the previous food product bought based on the given dataset.

STEPS :
Using APRIORI Algorithm to predict the food product consumer might buy.
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
9. Displaying Top 10 food products with highest relationship between each other based on the LIFT.

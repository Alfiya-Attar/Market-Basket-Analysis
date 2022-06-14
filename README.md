# Market-Basket-Analysis
## Introduction:
While browsing any eCommerce platform, you must have encountered the frequently bought together section. Many businesses add this section to improve sales, which leads to increased income. Market Basket Analysis, also known as Association analysis, is a method for understanding client purchase trends based on historical data. In other words, Market Basket Analysis enables merchants to find links between the products that customers purchase.
## Objectives:
•	Analyze the bakery data of 20k orders with the list of items bought by customers.           

•	Find out hidden association between products for better selling. 
## Dataset Description:
•	The dataset is a collection covering all transactions of customers who ordered different items from this bakery online and the time period of the data is from 2016  and 2017.

•	The shop primarily distributes one-of-a-kind all bakery products.

•	The dataset has 20507 entries, over 9000 transactions, and 5 columns. The five columns or features are:

•	Transaction :    Transaction id which is unique for each order

•	Item :           List of items to be ordered/placed by customer

•	date_time :      Date and time of the transaction. format: dd-mm-yyyy hh:mm

•	period_day :    Which period of a day when customer placed ordered

•	weekday_weekend : Is the day is weekend (sat or sun) or weekday

## We have performed:
1) EXPLORATORY DATA ANALYSIS
2) VISUALIZATION
3) MACHINE LEARNING ALGORITHM
## Apriori Algorithm:
Apriori algorithm assumes that any subset of a frequent item set must be frequent. Its the algorithm behind Market Basket Analysis.Say, a transaction containing {Grapes, Apple, Mango} also contains {Grapes, Mango}. So, according to the principle of Apriori, if {Grapes, Apple, Mango} is frequent, then {Grapes, Mango} must also be frequent.
## Association Rule Mining:
Association Rule Mining is used when we want to find an association between different objects in a set, find frequent patterns.
The most common approach to find these patterns is Market Basket Analysis, which is a key technique used by large retailers like Amazon, Flipkart, etc to analyze customer buying habits by finding associations between the different items that customers place in their “shopping baskets”. The discovery of these associations can help retailers develop marketing strategies by gaining insight into which items are frequently purchased together by customers.
## Association VS Recommendation:
 “Frequently Bought Together” → Association
 
 “Customers who bought this item also bought” → Recommendation
## Conclusions:
 We’ve done a Market Basket Analysis using bread basket data. The result of this market basket analysis could be used for a data-driven marketing strategy and decision making. In this datasets, we could generates several business insights as follows :

1) Item Placements: We could put Toast ,Bread and Coffee in a closer place, maybe in a same shelf .

2) Products Bundling: We could put put Toast, Bread and Coffee as a single bundle of product with a lower price compare to each price combined. This way will attract more sales and generates more income.

3) Customer Recommendation and Discounts: We could put Toast ,Bread in the cashier, so that every time a customer bought Coffee, we could offer and recommend them to buy Toast , bread with a lower price.

4) Items frequently bought together with Toast are Bread , Coffee , Tea.












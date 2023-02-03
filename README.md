# Identyfying-recommending-best-Restaurants
A restaurant consolidator is looking to revamp the B2C portal using intelligent automation tech. This requires a different matrix to identify the star restaurants and generate recommendations. To make sure an effective model can be achieved, it is important to understand the behavior of the data in hand. There are 2 datasets, data and Country-Code. Dataset data has 19 attributes and Country-Code has two attributes. 

Approach:
1. Data Preliminary analysis:
2. Prepare a preliminary report of the given data by answering few questions.
 Expressing the results using graphs and plots 

My analysis:

•	New Delhi has maximum of  5473 Restaurants
•	Café Coffee Day franchise has most national presence with 83 restaurants across countries.
•	Majority of 87% restaurants do not allow table booking. Ratio between restaurants that allow table booking vs those do not allow table booking is 0.13
•	Around 25.7% restaurants allow online delivery option.
•	The difference in votes for the restaurants that deliver & don’t deliver is 459322
•	Restaurants which do not provide online delivery are voted the most while those with online delivery has less votes.
•	Top 10 cuisines are as follows: North Indian, Chinese, Fast food,  Mughlai, Italian, Bakery, Continental, Café, Desserts, South Indian. 
•	Maximum of 8 cuisines & minimum of 1 cuisine is served by a restaurant.
•	North Indian is the most served cuisine
•	Distrution cost across restaurant based on different currencies is analysed. Found out that maximum cost for two is 8651 Indian Rupees.
•	Distribution of Ratings among various factors
1.	Overall 61 Restaurants has highest ratings & 2148 restaurants have zero ratings.
2.	India has the most highest rated(4.9 rating) restaurants followed by US.
3.	Only 300 Restaurants have Excellent Ratings.
4.	India has the most Excellent rated Restaurants,followed by United States. Out of 13,12 countries have at least 2 or above excellent Rated Restaurants.
•	Correlation between ratings & various factors
1.	Poor positive correlation between Rating & average cost for two.
2.	Rating & Votes has a good positive correlation. So ‘Votes’ can be a deciding factor.
3.	Table booking has an impact on rating. 
4.	There is low positive correlation between rating & Online delivery.
5.	Rating & Price range has a moderate positive correlation. It can be a deciding factor
6.	Relation between Rating & Number of cuisines is poor. Hence number of cuisines cannot be the deciding factor for restaurant rating.
7.	No factors have strong correlation with Rating. However, Votes & price range can be considered of having moderate impact on Rating

All the information gathered here will lead to a better understanding of the data and allow for a better implementation of ML models.

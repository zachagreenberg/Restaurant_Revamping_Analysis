# Opportunity in the NYC Restaurant Scene

Authors: Donna Lee & Zachary Greenberg

<p align="center"><img src="https://github.com/zachagreenberg/Restaurant_Revamping_Analysis/blob/main/Images/readme_cover.jpg" width="600" height="250" /></p>


# Overview 

This project analyzes the Chinese and Italian restaurant scene in New York City to narrow down the location and cuisine type of a possible new restaurant. There's definitely no shortage of either type of restaurant in the city which indicates high demand. We used Yelp data to analyze the ratings, location, modality, and more to narrow down the options.

# Data Collection

The data for this project comes from the Yelp Restaurant API. A total of 489 Chinese restaurants and 546 Italian restaurants in New York City are used in our analysis. We looked at the following data points to figure out what type of restaurant would be most innovative:

* *Location*
* *Price Range*
* *Ratings*
* *Sample of 3 Reviews per Restaurant*
* *Delivery Options*  

*This data was taken from the Yelp API using a private API Key. To get data from this API simply sign up for an API Key [here](https://www.yelp.com/developers/documentation/v3/authentication).

# Data Analysis

![rating by type](https://github.com/zachagreenberg/Restaurant_Revamping_Analysis/blob/main/Images/avg_rating_by_type.png)
Our data showed that Chinese restaurants on average had lower ratings than Italian restaurants in New York City. We saw this as a challenge to increase the overall average ratings for Chinese restaurants. 

![delivery and rating](https://github.com/zachagreenberg/Restaurant_Revamping_Analysis/blob/main/Images/chinese_delivery_and_rating.png)
When comparing delivery vs rating, we found that Chinese restaurants with no delivery option actually yielded higher ratings.


# Conclusions

After analyzing the Yelp data, we decided it would be best to open a high end Chinese restaurant in the Upper West Side.

* **There is a huge open opportunity for high-end Chinese restaurants in New York City.** Of our sample size, only 0.41% of Chinese restaurants had 4 dollar signs, signifying a majority of lower price point Chinese restaurants.

* **To maintain the exclusivity and experience of the restaurant, there will be no delivery option.** The difference in average rating for restaurants that had a delivery option versus no delivery option was insignificant. We decided that it would be wiser to not offer a delivery option because it provided no extra value in terms of better ratings and would allow the restaurant to cut costs.

* **The Upper West Side has a lower density of Chinese restaurants.** This area would be great for our new restaurant due to the lack of surrounding competition.

# Next Steps
 - Perform NLP on the text reviews to truly understand the ratings more.    
 - Narrow down the zip codes to get a more specified area for ideal restaurant relocation.  
 
------------------------------------------------
 
## *Repository Structure*
|_ Code  
|_ Data  
|_ Visualization  
|_ .gitignore  
|_ EDA_Evaluation.ipynb    
|_ init.py  
|_ README.md  
|_ Restaurant_Presentation.pdf  

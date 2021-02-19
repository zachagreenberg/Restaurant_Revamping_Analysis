# Restaurant Revamping

Authors: Donna Lee & Zachary Greenberg

## Overview of Business Problem

This project analyzes the Chinese and Italian restaurant scene in New York City to narrow down the location and cuisine type of a possible new restaurant. There's definitely no shortage of either type of restaurant in the city which indicates high demand. We used Yelp data to analyze the ratings, location, modality, and more to narrow down the options.

## Data & Methods

This project analyzes a sample of 489 Chinese restaurants and 546 Italian restaurants in New York City. We looked at the following data points to figure out what type of restaurant would be most innovative:

* *Location*
* *Price Range*
* *Ratings*
* *Sample of 3 Reviews per Restaurant*
* *Delivery Options*

## Results

![rating by type](https://github.com/zachagreenberg/Restaurant_Revamping_Analysis/blob/main/Visualization/avg_rating_by_type.png)
Our data showed that Chinese restaurants on average had lower ratings than Italian restaurants in New York City. We saw this as a challenge to increase the overall average ratings for Chinese restaurants. 

![delivery and rating](https://github.com/zachagreenberg/Restaurant_Revamping_Analysis/blob/main/Visualization/chinese_delivery_and_rating.png)
When comparing delivery vs rating, we found that Chinese restaurants with no delivery option actually yielded higher ratings.


## Conclusions

After analyzing the Yelp data, we decided it would be best to open a high end Chinese restaurant in the Upper West Side.

* **There is a huge open opportunity for high-end Chinese restaurants in New York City.** Of our sample size, only 0.41% of Chinese restaurants had 4 dollar signs, signifying a majority of lower price point Chinese restaurants.

* **To maintain the exclusivity and experience of the restaurant, there will be no delivery option.** The difference in average rating for restaurants that had a delivery option versus no delivery option was insignificant. We decided that it would be wiser to not offer a delivery option because it provided no extra value in terms of better ratings and would allow the restaurant to cut costs.

* **The Upper West Side has a lower density of Chinese restaurants.** This area would be great for our new restaurant due to the lack of surrounding competition.

### *Repository Structure*


>Code 
* DATA_COLLECTION.ipynb
* EDA_Notebook.ipynb
* __ init __ .py
* helper.py  

>Data  
* Restaurant.csv
* Review.csv

>Visualization
* Viz_Code.ipynb
* avg_rating_by_type.png
* chinese_delivery_and_rating.png
* Chinese_Restaurant_Map.html
* restaurants_by_price.png

>__ init __ .py  

>Phase 1 Presentation.pdf    

>README.md


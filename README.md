# Miniproject 2 - Yelp vs Foursquare API


## Project/Goals
Goals: to retrieve data from Yelp and Foursquare APIs for the chosen area(Lakewood, CO - I will be moving soon!) and compare the results(restuarants, bars, parks, dog parks, animal hospital, supermarket, etc.)  from those two APIs. 


## Process
1) Getting relevant data using Postman (term: restaurant, park, pet store, etc.) and save them as json file. 
2) Open the file in python and print the information by using json_normalize funcion and select columns that I wanted to see for comparison purpose (name, address, category, rate, number of reviews, etc.) 
3) Save it in SQL database

## Results
1) Yelp gives better/more accurate category information. (i.e. Chick-fil-a (fast food for Chicken sandwich) : Ramen(Foursquare)/fast food(yelp)) 
2) Yelp has a rating and number of reviews information, so it generally gives better information for decision making. 
3) In Park information Foursquare listed more parks(5), but the addresses were not shown accurately.  


## Challenges 
category has a nested dictionary under the set, so breaking up and pulling the first category (head category) from the dictionary and add it back to the dataframe was the most difficult part. 

## Future Goals

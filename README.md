# Miniproject 2 - Yelp vs Foursquare APIs Comparison


## Project/Goals
This project aims to practice retrieving data from a variety formats of APIs and save it in the local SQLite database.
I have retrieved data from Yelp and Foursquare APIs for city of Lakewood in Colorado (I will be moving soon!) and compare the results(restuarants, bars, parks, dog parks, animal hospital, supermarket, etc.) from those two APIs. 


## Process
1) Getting relevant data using Postman (term: restaurant, park, pet store, etc.) and save them as json file. 
2) Open the file in python and print the information by using json_normalize funcion and select columns for comparison purpose (name, address, category, rate, number of reviews, etc.)
3) Save it in SQL database
4) Compare the two results from Foursquare and Yelp 


## Results
1) Yelp gives better/more accurate category information. (i.e. Chick-fil-a(Chicken sandwich fast food restaurant): Ramen(Foursquare)/fast food(yelp)) 
2) Yelp has a rating and number of reviews information, so it generally gives better information for a decision making. 
3) In Park information Foursquare listed more parks(5), but the addresses were not shown accurately (insufficient/wrong information).  


## Challenges 
category has a nested dictionary under the set, so breaking up and pulling the first category (head category) from the dictionary and add it back to the dataframe was the most difficult part. 


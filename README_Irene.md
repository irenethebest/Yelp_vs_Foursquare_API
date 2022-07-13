# Miniproject 2

### [Assignment](assignment.md)

## Project/Goals
(fill in your description and goals here)
Goals: to retrieve data from those APIs for the area I might be moving (restuarants, bars, parks, dog parks, animal hospital, supermarket, etc.) 


## Process
1) Getting relevant data using Postman (term: restaurant, park, pet store, etc.) and save them as json file. 
2) Open the file in python and print the information by using json_normalize funcion and select columns that I wanted to see for comparison purpose (name, address, category, rate, number of reviews, etc.) 


## Results
(fill in what you found about the comparative quality of API coverage in your chosen area)

For restaurant, yelp gives better/more accurate category information. (i.e. Chick-fil-a (fast food for Chicken sandwich) : Ramen(Foursquare)/fast food(yelp)) 
yelp has a rating and number of reviews information, so it generally gives better information for decision making. 

## Challenges 
(discuss challenges you faced in the project)
category has a nested dictionary under the set, so breaking up and pulling the first category (head category) from the dictionary and add it back to the dataframe was the most difficult part. 

## Future Goals
(what would you do if you had more time?)
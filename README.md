# Final Project Team 13
## A Restaurant Recommendation System based on Yelp Information ##

**Project Goals**: 
* Scrape NYC restaurant information from Yelp
* Create an NYC restaurant information database 
* Build a restaurant recommendation engine that use our database to recommend users restaurants which match with their preferences

**Data Acquisition**:

 * Use "Yelp Restaurant Info Scraper.ipynb" to get search urls and scrape information for restaurants with different cuisine type from Yelp webiste. The script iterates through all locations in NYC. 
 * After getting the csv for each cuisine type, we use "Dataframe Cleaner.ipynb" to clean and merge all the csv files into a final dataframe. 
 
     We use this final dataframe (final_df.csv) as our database.
 * Our final dataframe has about 2500 NYC restaurants.

**Recommendation Engine**: 
The recommendation engnine enables users to input features that indicate their preferences.Our machine can output top 5 restaurants with highest yelp rating from as our recommendation for the user.
* User input features: 
1. Restaurant name keyword
2. Cuisine type
3. Restaurant neighborhood
4. User's expcected rating
5. User's expected price range
6. Party

* Recommendation engine output: (5 restaurants with following features) 
1. Restaurant name
2. Yelp rating
3. Hygiene rate
4. Restaurant address
5. Attire
6. Price range
7. Parking info
8. Reservability
9. Restaurant Ambience


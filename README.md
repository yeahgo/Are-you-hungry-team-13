# Final Project Team 13
## A Restaurant Recommendation System based on Yelp Information ##
**Project Goal**: 

* Create an NYC restaurant information database and use the database to recommend users restaurants which match with their preferences.

**Data Acquisition**:

 * Use "Yelp Restaurant Info Scraper.ipynb" to get search urls and scrape information for restaurants with different cuisine type. The script iterates through all locations in NYC. 
 * After getting the csv for each cuisine type, we use "Dataframe Cleaner.ipynb" to clean and merge all the csv files as a final dataframe. We use this final dataframe (final_df.csv) as our database.
 * Our final dataframe has about 1800 NYC restaurants.

**Recommendation Engine**: 
The recommendation engnine enables users to input features that indicate their preferences.Our machine can output top 3 restaurants with highest yelp rating from as our recommendation for the user.
* User input features: 
1. Restaurant name keyword
2. Restaurant neighborhood
3. User's expcected rating
4. Restaurant ambience
* Recommendation engine output: (3 restaurants with following features) 
1. Restaurant name
2. Yelp rating
3. Hygiene rate
4. Restaurant address
5. Attire
6. Price range

#### Yelp Dataset Challenge ####

###### Project Overview:
Utilized big data tools including Spark and AWS to optimize business strategy through EDA and sentiment analysis, and reduced communication and transference cost by building an Apache Zeppelin dashboard.
Apache Zeppelin is a web-based notebook system for sharing interactive data analytics. It currently supports various languages such as Python, SQL, and Spark (many others as well). These notebooks can be shared very easily using a link and additional analytics can be performed on the shared notebook. Using Apache Zeppelin and other big data tools such as AWS and Spark to build a market-entry/expansion research dashboard for businesses.

###### Dataset used:
Yelp Dataset (Business, Reviews, Checkins, Users) / 8.69 GB
- 6,685,900 reviews
- 192,609 businesses
- 200,000 pictures
- 10 metropolitan areas
- 1,223,094 tips by 1,637,138 users
- Over 1.2 million business attributes like hours, parking, availability, and ambience
- Aggregated check-ins over time for each of the 192,609 businesses

###### Steps Followed:
  1. Pre-process the data (Data filtering & feature engineering)
  
    a. Transformed business categories(for restaurants) in business dataset(having multiple tags) to 18 restaurant categories
    b. Transformed day of week & time attributes in checkin dataset from json format
    c. Transformed business attributes in business dataset from json format
    
  2. Merge business, checkin and reviews dataset into one

  3. Visualise the following
  
    a. Identify the most popular areas for restaurants in the business dataset
    b. Identify the top restaurant categories by number
    c. Compare the average ratings across the restaurant categories and pick the lowest one
    d. Identify specific zipcodes that perform the worst
    e. List the number of reviews for each restaurant in the worst performing zipcodes 
    f. List the potential demand by day of week(based on checkins data)

  4. Sentiment analysis of 
  
    a. The reviews of all restaurants of the worst performing category in the worst performing zipcodes
      i. 1-gram
      ii. bi-gram
      iii. tri-gram
    b. Exploring further on the detail of some complaints
    
  5. Location visualization of the various chinese restaurants in those zip codes
  
###### Code: 
Yelp_dataset_Analysis_for_building_market_entry_or_expansion_research_for_restaurant_businesses.ipynb
###### Languages: 
pySpark, Python, SQL

##### Big Data Tools:
AWS, Spark, Aphache Zeppelin

###### Contributors: 
Muyu Yan yan00108@umn.edu, Phoebe Chang chan1760@umn.edu, Dingruo Yang yang6548@umn.edu, Siva Lochan Kallur kallu016umn.edu, Stephen Champagne champ183@umn.edu, Sushanth Gaddam gadda010@umn.edu

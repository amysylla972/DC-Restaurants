## Group-Project-1

Our project goal is to answer those questions using our programming knowledge.


##What is the most competitive restaurant type in each DC Quadrant?
This data will help us find out which restaurant type may have been exhausted in DC and which restaurant types have the opportunity to grow.

##What is the average restaurant quality for restaurant types in each DC Quadrant?
This data will help identify if there is a particular restaurant type that may be associated with lower food quality. If so, this may present an opportunity to stand out.

##Does ethnic groups in DC impact restaurant types in each DC Quadrant?

With this question, we can identify any trends that may be related to DC's ethnicity. This will help us understand if a particular group of people impact the amount of a restaurant type in DC. If there is a trend, the new restaurant may have to serve those groups of people in some way with the new restaurant.


#Questions & Data

What is the most competitive restaurant type in each DC Quadrant?
Data needed by Quadrant: total number of Restaurants in DC

What is the average restaurant quality for restaurant types in each DC Quadrant?
Data needed by Quadrant: total number of Restaurants type ratings in DC
Does ethnic groups in DC impact restaurant types in each DC Quadrant?

Data needed by Quadrant: total number of Ethnic groups in DC
Data Cleanup & Exploration


Steps: 

#Find a good data source 
We used Yelp Api for our food data. 
Data on ethnicity from the census were split into many pieces without location data attached to each data. So we choose DC Health's data which was already broken out by Ward and zipcodes

#Determine quadrants 
We used Google maps to get the outline of the 4 quadrants in DC. Based on the outline, we picked the Wards and Zipcode data that is in each quadrant.

#Load in Data
We read our food data using Json. 
We read in the CSV data for each quadrant by Non-Hispanic and Hispanic groups

#Clean data: 
We used Pandas to clean the extra categories. 

#Summarize and Join Groups 
We summarized the Hispanic groups into one row of data and joined the Hispanic groups with Non-Hispanic data for each zip code and Ward.

#Combine Data 
We combined the data for the zipcodes and wards and used it as our quadrant.

#Plot Data 
We plotted the ethnic data for the quadrant. We plotted data for food. 

#Repeat - We followed steps 2-6 for each quadrant for DC.



Conclusion: 

We were able to answer each of these questions with our data but we better there is more research to be done to build a stronger recommendation. We found that the most competitive restaurant types across each quadrant are Asian and American restaurants. The least competitive market for restaurant types are foreign and niche restaurants. We also found that all restaurant types have an average rating of 3 stars or more but the restaurant types in Southwest DC have lower average ratings than any other quadrant. Lastly, we found that despite the competitive nature of Asian restaurants, few Asians are living in DC when to white or African American races. African Americans are the majority in every DC quadrant except in Northwest DC which is majority white. In Northwest DC, there were more European restaurants than any other quadrant.
In conclusion, the client should consider building a restaurant that serves a niche food like African Food in Southwest DC.

#Insights

We didn't anticipate African Americans being the majority in every quadrant of DC except Northwest.
An interesting find is that Asian food is just as competitive as American Restaurants
Another find is that Southeast DC is the only location without much diversity in restaurant types but yet as the highest amount of African Americans.


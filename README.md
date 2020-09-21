## Group-Project-1


What is the most competitive restaurant type in each DC Quadrant?

This data will help us find out which restaurant type may have been exhausted in DC and which restuarant types have oppurtunity to grow
What is the average restuarant quality for restaurant types in each DC Quadrant?

This data will help indentify if there is a particular restuarant type that may be associated with lower food quality. If so, this may present an oppurtunity to stand out.
Does ethnic groups in DC impact restuarant types in each DC Quadrant?

With this question, we can identify any trends that may be related to DC's ethnicity. This will help us understand if a particular group of people impact the amount of a restaurant type in DC. If there is a trend, the new restaurant may have to serve those groups of people in someway with the new restuarant.
Describe whether you were able to answer these questions to your satisfaction, and briefly summarize your findings
We were able to answer each of these questions with our data but we better there is more research to be done to build a stronger recommendation. We found that the most competitive restuarant types across each quadrant are Asian and American restaurants. The least competitive market for restaurant types are foreign and niche restaurants. We also found that all restuarant types have an average rating of 3 stars or more but the restuarant types in Southwest DC have lower average ratings than any other quadrant. Lastly, we found that despite the competitive nature of Asian restuarants, there are few Asians living in DC when to white or African American races. African Americans are majority in every DC quandrant except in Northwest DC which is majority white. In Northwest DC, there were more european restuarants than any other quadrant.
In conclusion, the client should consider build a restaurant that serves a niche food like African Food in Southwest DC.

#Questions & Data

Elaborate on the questions you asked, describing what kinds of data you needed to answer them, and where you found it
What is the most competitive restuarant type in each DC Quadrant?

Data needed by Quadrant: total number of Restaurants in DC
What is the average restuarant quality for restaurant types in each DC Quadrant?

Data needed by Quadrant: total number of Restaurants type ratings in DC
Does ethnic groups in DC impact restuarant types in each DC Quadrant?

Data needed by Quadrant: total number of Ethnic groups in DC
Data Cleanup & Exploration

Describe the exploration and cleanup process -steps for Ethnic Data:

#Find a good data source 
We used Yelp Api for our food data. 
Data on ethnicity from the census were split into many pieces without location data attached to each data. So we choose DC Health's data which was already broken out by Ward and zipcodes

#Determine quadrants 
We used Google maps to get the outline of the 4 quadrants in DC. Based on the outline, we picked the Wards and Zipcode data that is in each quadrant.

#Load in Data
We read our food data using Json. 
We read in the CSV data for each quadrant by Non-Hispanic and Hispanic groups

Summarize and Join Groups - We summarized the Hispanic groups into one row of data and joined the Hispanic groups with Non-Hispanic data for each zipcode and Ward.

Combine Data - We combined the data for the zipcodes and wards and used it as our quadrant.

Plot Data - We plotted the ethnic data for the quadrant.

Repeat - We followed steps 2-6 for each quadrant for DC.

Discuss insights you had while exploring the data that you didn't anticipate

We didn't anticipate African Americans being the majority in every quadrant of DC except Northwest
An interesting find is that Asian food is just as competitive as American Restaurants
Another find is that Southeast DC is the only location without a much diversity in restuarant types but yet as the highest amount of African americans.
Discuss any problems that arose after exploring the data, and how you resolved them

The Ethnicity Data was only limited to Zipcodes and Wards which made it difficult to get a very accurate representation of the four quadrants. Some wards and zipcode spanned across multiple quadrants.

We resolved it by using zipcodes when the wards span too much into the next quadrant. Also we elimated a zipcode if it is split evenly across both quadrants. Lastly, if the zipcode or ward spans alot more into one quadrant than the other, we give the zipcode to the quadrant the larger
Data Analysis

Discuss the steps you took to analyze the data and answer each question you asked in your proposal
Does ethnic groups in DC impact restuarant types in each DC Quadrant?

We compared the ethnic plots of each quadrant with the number of restuarants to determine if there is a pattern in a particular restuarant type.

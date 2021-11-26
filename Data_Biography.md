# Data Biography

### Declaration of Authorship

I, Hadiyan Wijaya, confirm that the work presented in this assessment is my own. Where information has been derived from other sources, I confirm that this has been indicated in the work.

Hadiyan Wijaya

Date of signature: 25-Nov-21
Assessment due date: 26-Nov-21
Student Number: 20148357

_Please write your answer immediately below the level-3 headers and delete the guidance prior to submission._

---

### 1. Who collected the data?

The data inside Airbnb mainly sourced from Airbnb’s publicly available data, then filtered, compiled, and analysed by Murray Cox under ‘inside Airbnb’ project platform, in purpose to share his taught and prove. [1]

---

### 2. Why did they collect it?

The Author of Inside Airbnb data is clearly stated the objective behind Inside Airbnb project is to providing data to quantify short-renting property impacts by Airbnb. This objective also leads to supporting advocacy for policy in order to implement protection against the impacts of short-renting properties. [2]

---

### 3. How was it collected?

Mostly, the data is collected by scraping method using multi-source code. In the near end of the project, The Inside Airbnb author significantly using Airbnb code from Tom Slee from GitHub site [3]. Overall, the scraping code run in these steps: (1) Checking the connection to the database (Airbnb database; (2) Add searching area of survey such as city name; (3) then running the ‘scraping’ steps which bounded into 3 categorize: by neighbourhood, by bounding box, or by zip-code. The result of the scraping is a database in the form of table which has lists of rented property via Airbnb as a row, and its attribute as column. [4]

---

### 4. What useful information does it contain?

The Inside Airbnb project mainly wants to show by the data the indication of gentrification in the area which many properties are rented via Airbnb. To bring that context, several data has been scrapped. The London listings data contains general data such as listings ID, the time the listings scrapped, listings description, and more importantly the information of listings such as type, location, price, and its room detail. The data also contains the hosts information such as name, their location, and details related to contacting them. These Airbnb data, linked with government data could give picture or indication about how short-rent impact to the housing in the London area. [5]

---

### 5. To what extent is the data 'complete'?

The completeness of the data means how much the data fully filled in terms of describing the population, in this case is describing Airbnb listings in London Area. The completeness of the data also can be perceived vertically (completeness of the row) and horizontally (completeness of the column). 
Firstly, for vertically completeness it means how complete the number of data compare to the number of population or if the data is sample, it means the sample is big enough to describe whole population. In this category the London listings data contains 74,189 number of the data. Meanwhile the latest of London listings data [6] should contain about 87,235 data that considered of 100% population of listings in London area. That means the data that is provided is only 85% of the listing population, which is quite good but not good enough to describe common standard 95% of population.
Secondly for horizontally completeness of the data there are some groups of data that has many blank, there are within description and neighbourhood overview, host response and acceptance rate, accommodation facilities, and reviews. Some of the empty data can be ignored because its is randomly blank pr don’t have correlation with other blank data. The example is listings description or number of facilities of the accommodation. It can be perceived as the host doesn’t yet fill description for the accommodation or the accommodation doesn’t have the facilities. Meanwhile there are likely structured blank data like reviews data where if there are no review, it means the review score and rate will not occur. This kind of blank data should be avoided.

---

### 6. What kinds of analysis would this support?

The data can be used to detect early housing problem. One of the critics is the full-time home or appartement considered reducing London’s housing supply and could change the characteristics of neighbourhood. [7]. By knowing the amount and comparing it to other accommodation we can get the picture how much idle housing in London area. Giving the fast fact that 55% or about 41 thousand of the rented properties in London are entire home or appartement. and only 1% rent type shared room. This shows that how many idle properties to solve housing problem in London if it can be cheaply rented by the homeless or some people who really need it. Instead, the properties are owned privately to raise profits by renting it. This leads to second question about how profitable open the rent house in the London area? The more profitable the more tendency to open new listings in the area, that means more people will idling their property and it will give more impact to housing problems. The data shows that by indicating the active review inside Airbnb estimate the listings have 85 days within a year to be rented [8]. By calculating the average price each type listings and multiplies it by average yearly night spend with average yearly contract price in London, we get the information if yearly contract is still 4,000-13,000 more profitable than Airbnb. By this result we can estimate the Airbnb listings will not significantly grow because of comparative profit reason. 

---

### 7. Which of the uses presented in Q.6 are _ethical_?

Considering the analysis mentioned in Q.6 I argue that none of them against the ethical. Usually, ethical issue is related when mentioned some privacy such as name, or age, or living location. Or maybe valuating some properties that can changed the property values. Also, some ethical related to some analysis try to unequally show fact that benefiting some groups. In both analysis which show how many idle houses and benefitable degree of opening listings in London don’t have significant issue that against the ethical. Both are only showing aggregate and average value of the number of house and the property rent price without mentioning thing considered as privacy, discriminating, or benefiting particular group.

Word count: 979 word
## Bibliography

[1]
[2]
[3]
[4]
[5]
[6]
[7]
[8]

## Appendix

Count of listings and estimated profit within day cap base on listings type
rent type	count	%count	average price per night	30 cap days	60 cap days	90 cap days	180 cap days
Entire home/apt	40853	55%	164.47	 13,929.84 	 8,995.67 	 4,061.51 	-10,740.99 
Private room	32163	43%	61.70	 17,013.11 	 15,162.22 	 13,311.34 	 7,758.67 
Hotel room	576	1%	129.58	 14,976.61 	 11,089.23 	 7,201.84 	-4,460.32 
Shared room	592	1%	56.31	 17,174.71 	 15,485.42 	 13,796.14 	 8,728.27 
all_type	74184	100%	118.78	 15,300.68 	 11,737.36 	 8,174.05 	-2,515.91 


column name	data missing	column name	data missing	column name	data missing
id	2	neighbourhood	26981	availability_60	2
listing_url	1	neighbourhood_cleansed	2	availability_90	2
scrape_id	1	neighbourhood_group_cleansed	74186	availability_365	2
last_scraped	1	latitude	2	calendar_last_scraped	4
name	21	longitude	2	number_of_reviews	2
description	2859	property_type	2	number_of_reviews_ltm	2
neighborhood_overview	26980	room_type	2	number_of_reviews_l30d	2
picture_url	0	accommodates	2	first_review	20285
host_id	0	bathrooms	74186	last_review	20285
host_url	0	bathrooms_text	159	review_scores_rating	21903
host_name	9	bedrooms	4594	review_scores_accuracy	21955
host_since	9	beds	989	review_scores_cleanliness	21946
host_location	182	amenities	2	review_scores_checkin	21994
host_about	31694	price	2	review_scores_communication	21954
host_response_time	36407	Price_number	3	review_scores_location	21991
host_response_rate	36409	minimum_nights	2	review_scores_value	21992
host_acceptance_rate	22591	maximum_nights	2	license	74188
host_is_superhost	11	minimum_minimum_nights	2	instant_bookable	4
host_thumbnail_url	11	maximum_minimum_nights	2	calculated_host_listings_count	4
host_picture_url	11	minimum_maximum_nights	2	calculated_host_listings_count_entire_homes	4
host_neighbourhood	17628	maximum_maximum_nights	2	calculated_host_listings_count_private_rooms	4
host_listings_count	13	minimum_nights_avg_ntm	2	calculated_host_listings_count_shared_rooms	4
host_total_listings_count	11	maximum_nights_avg_ntm	2	reviews_per_month	20287
host_verifications	2	calendar_updated	74186		
host_has_profile_pic	11	has_availability	2		
host_identity_verified	11	availability_30	2		

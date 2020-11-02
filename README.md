Coffee beans - Mae Mu @picoftasty
Coffee ratings
The data this week comes from Coffee Quality Database courtesy of Buzzfeed Data Scientist James LeDoux. The original data can be found on James' github. The data was re-posted to Kaggle.

"These data were collected from the Coffee Quality Institute's review pages in January 2018."

Thrillist has an article on the top coffee-producing countries.

Yorgos Askalidis analyzed this data as well.

There is data for both Arabica and Robusta beans, across many countries and professionally rated on a 0-100 scale. All sorts of scoring/ratings for things like acidity, sweetness, fragrance, balance, etc - may be useful for either separating into visualizations/categories or for modeling/recommenders.

Wikipedia on Coffee Beans:

The two most economically important varieties of coffee plant are the Arabica and the Robusta; ~60% of the coffee produced worldwide is Arabica and ~40% is Robusta. Arabica beans consist of 0.8–1.4% caffeine and Robusta beans consist of 1.7–4% caffeine.

Wiki on Cupping

Coffee cupping, or coffee tasting, is the practice of observing the tastes and aromas of brewed coffee. It is a professional practice but can be done informally by anyone or by professionals known as "Q Graders". A standard coffee cupping procedure involves deeply sniffing the coffee, then loudly slurping the coffee so it spreads to the back of the tongue. The coffee taster attempts to measure aspects of the coffee's taste, specifically the body (the texture or mouthfeel, such as oiliness), sweetness, acidity (a sharp and tangy feeling, like when biting into an orange), flavour (the characters in the cup), and aftertaste. Since coffee beans embody telltale flavours from the region where they were grown, cuppers may attempt to identify the coffee's origin.

Data Dictionary
coffee_ratings.csv
Note full description/examples at: Coffee Quality Institute

variable	class	description
total_cup_points	double	Total rating/points (0 - 100 scale)
species	character	Species of coffee bean (arabica or robusta)
owner	character	Owner of the farm
country_of_origin	character	Where the bean came from
farm_name	character	Name of the farm
lot_number	character	Lot number of the beans tested
mill	character	Mill where the beans were processed
ico_number	character	International Coffee Organization number
company	character	Company name
altitude	character	Altitude - this is a messy column - I've left it for some cleaning
region	character	Region where bean came from
producer	character	Producer of the roasted bean
number_of_bags	double	Number of bags tested
bag_weight	character	Bag weight tested
in_country_partner	character	Partner for the country
harvest_year	character	When the beans were harvested (year)
grading_date	character	When the beans were graded
owner_1	character	Who owns the beans
variety	character	Variety of the beans
processing_method	character	Method for processing
aroma	double	Aroma grade
flavor	double	Flavor grade
aftertaste	double	Aftertaste grade
acidity	double	Acidity grade
body	double	Body grade
balance	double	Balance grade
uniformity	double	Uniformity grade
clean_cup	double	Clean cup grade
sweetness	double	Sweetness grade
cupper_points	double	Cupper Points
moisture	double	Moisture Grade
category_one_defects	double	Category one defects (count)
quakers	double	quakers
color	character	Color of bean
category_two_defects	double	Category two defects (count)
expiration	character	Expiration date of the beans
certification_body	character	Who certified it
certification_address	character	Certification body address
certification_contact	character	Certification contact
unit_of_measurement	character	Unit of measurement
altitude_low_meters	double	Altitude low meters
altitude_high_meters	double	Altitude high meters
altitude_mean_meters	double	Altitude mean meters

Importantly - there is the concept of ethical or Fair Trade coffee - we'll be covering more of the production numbers of Coffee in a future dataset.

Based on the simple idea that the products bought and sold every day are connected to the livelihoods of others, fair trade is a way to make a conscious choice for a better world.

Fair Trade Coffee definition from Wikipedia:

Fair trade coffee is coffee that is certified as having been produced to fair trade standards by fair trade organizations, which create trading partnerships that are based on dialogue, transparency and respect, with the goal of achieving greater equity in international trade. These partnerships contribute to sustainable development by offering better trading conditions to coffee bean farmers. Fair trade organizations support producers and sustainable environmental farming practices and prohibit child labor or forced labor.

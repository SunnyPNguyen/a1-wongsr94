CEE 224X | Released: 180925 | Due: 181002
Name:

#### Q1: What are the “Combined” fields referring to? How do you think this information may affect our analyses?

Q1 The public datasets must meet the standards for aggregating and anonymizing customer data pursuant to CPUC Decision 14-05-016, as follows:  a minimum of 100 Residential customers; a minimum of 15 Non-Residential customers, with no single Non-Residential customer in each sector accounting for more than 15% of the total consumption.  If the aggregation standard is not met, the consumption will be combined with a neighboring ZIP code until the aggregation requirements are met. This will mean that the zip code might not correspond exactly to its actual residing customers. The data will be from a wider area.

Peer Review - SN: Shi Rui's response differs from mine as I had no previous knowledge of the combined data field; however, from reading this response to Q1, data under the "Combined" field now makes more sense in terms of what actual values were used.

#### Q2: Why are the “Average” fields likely not useful for our analyses?

Q2 Due to the customer composition of each postal code and the definite difference in usage between different types of customers, the 'Average' field will not give a good indicator. 

Peer Review - SN: Both Shi Rui and I had the same response for this question.


#### Q3: What type of calculations should "X" and "Y" be in the step above? Why?

Q3 Response Here (<100 words)



#### Q4: What is the total KBTU combined electricity and gas consumption in PG&E territory in 2017? What is the average annual electricity consumption per customer, and average annual gas consumption per customer?

Q4 5.32306E+11KBTU. Avr annual electricity consumption per customer is 55861.27422 KBTU, average annual gas consumption per customer is 52486.3199 KBTU. 

Peer Review - SN: My response is different from Shi Rui's as this could be due to a difference in the conversion of energy units into kBTU. The setup of the pivot table might have also resulted in this differnce.



#### Q5: How would you explain the results of this chart to an average property owner in Northern California? What would be the value of conducting further "seasonal" analyses of energy use, compared to "year-long" analyses, and how would you define seasonal boundaries?

Q5 Gas consumption increases in colder seasons. Electricity consumption while to a lesser extent goes in the opposite way. Seasonal analysis would give greater accuracy due to the differences in consumption patterns as opposed to year-long analyses, which might be skewed by the various peaks of consumption patterns. I would define the seasonal boundaries by 3 sets perhaps, the colder, Nov-Feb, the the warming, Mar-Jun and the cooling Jul-Oct. 

Peer Review - SN: Both Shi Rui and I shared a very similar response and explained the energy consumption patterns based on external factors such as weather. Our seasonal boundaries are also similar as we both agreed that the boundaries should include and group months in which the weather and overall temperature are consistent to one another.


#### Q6: Explain your choice of formula for "avgkbtu".

Q6 Divided totalkbtu by totalcustomers, multiplied by 12 to account for double-counting customers across 12 months in totalcustomers.

Peer Review - SN: Shi Rui's formula used to determine the average values was different from mine as mine is directly calculated based on the average values provided by PG&E and were simply converted to KBTU. The two different formulas would have resulted in different results for the subsequent maps produced on ArcGIS.


#### Q7 Paste a publicly viewable link to your Slides.

Q7 https://docs.google.com/presentation/d/1UMLJbgXY5KmQrfIEI4T3-gbQ7pdElxSKZCIspQGdqc0/edit?usp=sharing

Peer Review - SN: While our total KBTU maps were very similar, the average kBTU map had a significantly different legend values and representation due to the different formulas used in calculating these values.

#### Q8 In what ways do the results in or in the vicinity of your chosen zip code validate or contradict your expectations?

Q8 The total consumption of electricity in 94305 is similar to my expectations as it is a school area that while classified as residential, does not have a siginificant population density. This is as opposed to a city area like the vicinity of San Jose.

The average consumption of electricity per customer is unsurprising in terms of the Palo Alto vicinity as most customers would be of a similar demographic (student, academics) as opposed to the sparsely populated areas such as the parks and reserves where likely customers would be a managing company/agency. 

Peer Review - SN: In contrast to Shi Rui's response, I examined zip code 95112 where I actually am living, due to the difference in zip code, the map and resulting symbology was different which further emphasizes the correlation between locality (zip code) and energy consumption.


#### Q9 Any other reactions to completing Pass One? What was especially challenging or surprising in the workflow? How might you expand on this analysis if you had more time?

Q9 It is interesting to see how the numbers in an excel file can be visually displayed on ArcMaps. It was surprising to find out that significant amount of time was spent on managing the data into a usable format for ArcMaps to process. I also found the initial part where we were just asked to compute totalkbtu without creating a separate column for total therms confusing. But I eventually understood once the pivot table was put in place. I think it would be interesting to figure out electricity usage during different times of the day and also to perform the similar visualizations of usage during the differing seasons.

Peer Review - SN: While Shi Rui and I agree on the challenge of using excel's pivot table, I found that the tech setup took significantly longer due to being off campus. Additionally, the second pass also took a large chunk of time in debugging the missing file which was not a problem for Shi Rui. Both of our expansion on the analysis were similar in the detailed sense in an effort to obtain a more accurate usage pattern.

#### Q10 How would you compare the experienced or apparent work involved, as well as the usefulness of the outcome, of Pass One vs. Pass Two? How would you rate the difficulty of this assignment?

Q10 I think Pass One has a higher chance of calculation error along the way as opposed to Pass two even though i did not do pass two by myself (design the R), mainly due to the amount of human effort needed to move things around in excel. The ArcMaps portion is relatively manageable. I would rate say the assignment was difficult for me as I have not used excel in a long time.

Peer Review - SN: In comparison to the response above, I found Pass Two to be more difficult as I have very limited coding knowledge; however, I completely agree that Pass One has a lot of room for calculations error.

#### Q11 In total, how long did Assignment 1 take?

Part 1: Tech Setup: 1 day

Part 2: Pre-Assessment: 20 minutes

Part 3: Readings: 30 minutes

Part 4: Practice Data Dive: Pass 1: 4 hours

Part 4: Practice Data Dive: Pass 2: 20 minutes

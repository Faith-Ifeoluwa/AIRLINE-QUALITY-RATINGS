# AIRLINE QUALITY RATINGS

## Table of Content

- [Overview](#overview)
- [Dataset](#dataset)
- [Data Preparation Steps](#data-preparation-steps)
- [Age Grouping](#age-grouping)
- [Tool Used](#tool-used)
- [Data Visualization](#data-visualization)
- [Key Findings](#key-findings)
- [Recommendations](#recommendations)

### Overview
---
This is an analysis of the level of satisfaction of a number of airline passengers. It aims to provide insight into what key factors are responsible for passenger satisfaction or dissatisfaction.

### Dataset
---
The dataset originally contains information about 129,880 passengers. To ensure data integrity and reduce errors, 393 of them which were found to be containing missing data were taken out, leaving 129,487 rows and 24 columns of working data.

**The Columns in this dataset include:**

**ID:** Passenger ID

**Gender:** Passenger gender

**Age:** Passenger age

**Customer Type:** Customer type

**Type of Travel:** Purpose of the flight of the passengers

**Class:** Travel class in the plane of the passengers

**Flight Distance:** Flight distance

**Departure Delay:** Minutes delayed before departure

**Arrival Delay:** Minutes delayed upon Arrival

**Departure & Arrival Time Convenience:** Convenience of Departure and Arrival times for passengers

**Ease of Online Booking:** Ease in booking

**Check-in Service:** Ease of registration

**Online Boarding:** Convenience of online registration

**Gate Location:** Gate Location Estimation

**On-board Service:** Service on board

**Seat Comfort:** Comfortable seating

**Leg Room Service:** Legroom service level

**Cleanliness:** Cleanliness level

**Food and Drink:** Quality of food and drinks

**In-flight Service:** Level of service on board

**In-flight Wifi Service:** Wifi quality level on board

**In-flight Entertainment:** Rating of in-flight entertainment

**Baggage Handling:** Opinion on baggage handling

**Satisfaction:** Airline satisfaction level


### Data Preparation Steps
---
- Checked to ensure consistent data format.

- Cleaned out rows of data containing missing values to ensure data integrity.

- Created a new column named Age Range using power query, to classify the different age numbers under specific age groups.

### Age Grouping 
---

|AGE GROUP|AGE RANGE (years)|
|---------|-------|
|Adolescent|7 - 12|
|Teenager|13 - 19|
|Young Adult|20 - 35|
|Middle Age|36 - 64|
|Elderly| 65 and above|


### Tool Used
---
This analysis was performed using Excel. Special functions in Excel like the Power query and the data analysis functions were also utilized.

## Data Visualization

<img width="669" alt="2024-07-01 (11)" src="https://github.com/Faith-Ifeoluwa/AIRLINE-PASSENGERS-ANALYSIS/assets/171179494/8dd8d1b1-c589-430d-a033-5f098db9cd97">
<img width="624" alt="2024-07-01 (10)" src="https://github.com/Faith-Ifeoluwa/AIRLINE-PASSENGERS-ANALYSIS/assets/171179494/c9dd3959-8916-41b5-85c9-14b24c39422e">


### Key Findings
---
The key findings in this analysis include the following:

- 57% of passengers were dissatisfied with the airline services, while 43% showed some level of satisfaction. The analysis of different travel classes shows that both the male and female passengers in the Business class are largely satisfied with the airline services in comparison with the other classes.

- Overall, passengers in all travel classes are not pleased with the online booking service and the top 3 dissatisfactory services are the _in-flight services, baggage handling, and departure and arrival time convenience_. This is however not true of Business class travelers who seem to enjoy more benefits with baggage handling and in-flight services.

- There is also a significant difference in the satisfaction levels of different age groups, with the Middle-aged group having 53.29% of its population showing satisfaction with the airline services, far outnumbering other age groups, especially the Adolescent group with the lowest count of 13.46% of its whole population.

- The analysis further shows a strong positive correlation between arrival delay and departure delay. It also reveals that the experience of delay either on arrival or departure is seen to greatly reduce satisfaction levels by a significant 10%.

- First-time customers of the different travel classes show very low satisfaction with services rendered by the airline. The Business class tops the list, however, with a satisfaction level significantly below average.

- More than an average count of returning customers of the Economy and Economy plus travel class have a very strong dissatisfaction with the services offered by the airline too.

### Recommendations
---
- The airline can adopt a more flexible online booking system to improve passenger activities on its website.It could also invest in a mobile application with a simple-to-use and interactive/conversational interface.

- It is a general notion that passengers flying economy or economy plus class are treated poorly. This can however be corrected by making sure that passengers are clearly aware of the services available to them in each travel class and then the airline also delivers its services as promised. Also, it should be ensured that passengers flying lower classes aren’t treated unfairly or with a bias in favor of the Business class flyers.

- Other silent and underlying factors affecting passenger satisfaction like the attitude of airline employees towards passengers could also be vetted to ensure the delivery of quality and professional services. This can also be done by investing in employee training.

- The causes of delays should be examined and improved upon to improve customer satisfaction. In the event of delays caused by natural or unavoidable causes such as weather conditions and unforeseen maintenance problems, passengers should be notified promptly of the cause of the delay.

- Boarding assistance and support can also be provided for a better travel experience.

- Baggage handling can be improved upon by admitting more trained staff to tackle the influx of passengers with an emphasis on their responsibility for passengers’ baggage.

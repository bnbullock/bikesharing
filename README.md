# Bike Sharing Analysis


## Project Overview

Two friends have recently returned from a trip to New York and throughly enjoyed their experiences exploring the city. The primary reason for their successful vacation experiences was their reliance on citi bike-sharing service for their daily trips and destination adventures. By using this service, it gave them the time and opportunity to interact with people who live there and use bikes regularly for their commute and also allowed them to get to know the city on a very personal level.

As they return home to Des Moines, they have decided to explore the possibility of creating a business venture with a similar bike sharing service to see if they can capture this same appeal in their local community. Thankfully, they have a successful service and personal experience with citi bikes which they can study to determine if a similar local service can be sustainable and successful.

With this task in mind, we are asked to retrieve more information from the citi bike sharing service in New York City, which is publically available, and prepare visualizations that can be presented to potential investors. A determination needs to be made as to the viability of the data in Des Moines as it relates to New York City and we need to ensure that the integrity of the presented visualizations are valid for our local community. The core issue we need to think about is what we absolutely need to know in order to create our bike-sharing program in Des Moines. We have cultivated a number of potential investors who have agreed to an in-person pitch. So we are now tasked with creating suitable visualizations and framing a bike sharing business venture that investors will want to support and invest in locally. We will make a comparative analysis and provide information and charts with the results we have found in the NYC ride sharing data.

- Deliverables:
  1. Using Python, update the CSV bike trips CSV file.
  2. Create 5 different visualizations in Tableau
  3. Create 2 additional custom visualizations
  4. Craft a Tableau Story based on the visualizations
  5. Written Analysis
------------------------------------------------------------------------------------------------------------

## Resources
- Software: Visual Studio Code 1.56.2, Python 3.7.10, Jupyter Notebook Server 6.3.0, Tableau Public 2021.2
- Browser : Google Chrome v91.0.4472.124 
- Data Source: https://s3.amazonaws.com/tripdata/index.html#:~:text=ZIP%20file-,201908-citibike-tripdata.csv.zip,-Sep%2018th%202019

------------------------------------------------------------------------------------------------------------

## Results

To see the presentation story please click the link below:

[Link to dashboard](https://public.tableau.com/app/profile/barney.bullock/viz/Challenge14v2/CitiBikeStory?publish=yes)

### Trip Duration
- The peak trip duration is usually seen to be between 5 and 6 minutes. This means citi bike clients are using the service for very short term travel as shown below.

![Image1](images/1UserCheckout1.png)

### Trip Duration by Gender
- Further breaking down the trip duration by gender, we see that males use the bike sharing service predominantly more at a ratio of 3 to 1.

![Image2](images/2GenderCheckout1.png)

### Breakdown by Day Usage
- The bike sharing service usage peaks at the following periods:
  - 7AM - 9AM Monday to Friday
  - 5PM - 7PM Monday to Friday
  - 10AM - 6PM Saturdays
  - 12AM - 5PM Sundays
- This breakdown indicates that bikes are used for commuting to and from work on weekdays and also used on weekends for leisure pursuits or tourist destinations.

![Image3](images/3Trips1.png)

### Breakdown by Day and Gender Usage
- The above peak times are further qualified by the image below that shows all genders using the service in a similar fashion. However, male usage is 3 times more pronounced within those peak times.

![Image4](images/4TripsbyGender1.png)

### Breakdown by Usertype and Gender/Weekday Usage
- Further refinement of the bike sharing usage brings us to the visualization below that shows subscribers as the primary users of the service versus walk in customers. Male subscribers again making up for the majority of users throughout the week.

![Image5](images/5TripsType1.png)

### Trips taken by Birth Year and Gender
- The age group of all users that have the most usage impact on bike trips is from 24-40 year olds. Also, we see a big jump in usage for users that turn 50 years old.

![Image6](images/6BirthGender1.png)

### Potential Pilot Group
- Based on the image below we can see how important subscribers are to the bike sharing service. Female subscribers show 5 times more usage than walk up clients and for males its 10 times.

![Image7](images/7TypeGender1.png)

### Additional Visualizations that could be Useful
- Further refinement of the peak 5 minute usage could be helpful in identifying if subscribers are using trains or buses to get to the downtown area and then utilizing the bike sharing service for the short commute to their office location or if subscribers are commuting from home directly.
- It would also be great to understand if the bike sharing service can be marketed from an exercise/health point of view. We see a signifigant jump in usage when users turn 50, why is the data showing this? Is biking an exercise alternative that can be another form of revenue?

------------------------------------------------------------------------------------------------------------

## Overall Summary
- The downtown area of Des Moines which has many attractions, some of these are art and historical museums, downtown farmers market, botanical gardens, science centre, performing arts centers, Wells Fargo arena, Civic center, etc. There are many places of interest that tourists and locals find endearing with rivers to the East and South and plenty of activities within a short distance of the downtown area. This feels like an ideal location to pilot a local bike sharing service that can be modelled after citi bike in New york City. We have identified that bike trips from citi bike have the following characteristics based on the data analysis above.
  - Peak trip usage is 5 minutes
  - The ratio of males to females in terms of usage is 3 to 1
  - There is a clear and defined usage pattern for commuting and weekend leisure/tourist use
  - Subscribers tend to use the service at a much higher level than walk-in customers
  - There are specific demographic groups identified showing we should target age groups 24-40 and 49-50
  - Finally we can see the importance of recruiting subscribers early and on an on-going basis to grow the business

In order for a bike sharing service to be successful, subscribers will need to be cultivated early from the age groups identified. It's also important to look for subscribers who live within the five minute commute radius of downtown or those using bikes for the last leg of their commute. Further, there are many attractions within a short distance of the downtown area that can add incremtal revenue, whether it's the local population or visitors to Des Moines. There also pre-existing bike trails and paths located in the downtown vicinity that are used today. There are many positive attributes identified above that point to Des Moines as a viable destination for piloting a bike sharing service. I believe this presentation adds merit to why a succefful pilot can be realized in this community.

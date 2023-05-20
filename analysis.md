# Citi Bike Challenge

<img width="341" alt="Screen Shot 2023-05-18 at 6 26 05 PM" src="https://github.com/therahgithub/citi-bike-challenge/assets/119986667/c16e532d-c9f0-4125-ad76-dfd3434d8d5b">

<img width="707" alt="Screen Shot 2023-05-18 at 6 32 57 PM" src="https://github.com/therahgithub/citi-bike-challenge/assets/119986667/76aa7381-9b2e-462f-bd14-db08795d2133">

## Hypothetical Background
#### I am the new lead analyst for the New York Citi Bike program, and am now responsible for overseeing the largest bike-sharing program in the United States. In my new role, I will generate regular reports for city officials looking to publicize and improve the city program.

#### Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the Citi Bike Data webpage. However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so my first task is to build a set of data reports to provide the answers.

## Task
### Aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.
* Choose a dataset from [Citi Bike Data](https://citibikenyc.com/system-data). Design 2–5 visualizations for each discovered phenomenon (4–10 total).
* Use the visualizations to design a dashboard for each phenomenon. The dashboards should be accompanied by an analysis explaining why the phenomenon may be occurring.
* Create one of the following visualizations for city officials:
  * Basic: A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey, with zip code data overlaid on top.
  * Advanced: A dynamic map that shows how each station's popularity changes over time (by month and year). Again, with zip code data overlaid on the map.
  * The map you choose should also be accompanied by a write-up describing any trends that were noticed during your analysis.

## Visuals and Analysis
#### For my initial ride 🚲 through the data, I chose to analyze trends in weekday versus weekend ridership; paying special attention to popular start and end stations, subscribers versus customers, common start and end times, total and average trip duration, and a brief glimpse into ridership age.

#### My Citi Bike Story uses data from July 2018 and contains three dashboards: Weekday bike stats, 

### Weekday bike stats: 
![Screen Shot 2023-05-20 at 12 55 49 AM](https://github.com/therahgithub/citi-bike-challenge/assets/119986667/eefb5474-1a4f-4b4b-ab85-b9173040ce54)

#### During the week, commuters rule the bikes. The most common start and end times coincide with the classic 9-5 work schedule, subscribers far outpace customers in number of rides, and a closer look at popular start and end stations below further supports heavy commuter utilization of the bike program during the week.

#### The most popular start and end stations are Pershing Square North, E17th & Broadway, and West St & Chambers St. 
 * Pershing Square North is home to Grand Central Station. Heavy flows to and from this bike station no doubt are commuters continuing on to work after arriving to and traveling from this iconic hub. 
 * The E17th & Broadway station is right in the middle of the residential neighborhoods of Union Square and the surrounding Flatiron District to the north, Chelsea to the west, Greenwich Village to the southwest, East Village to the southeast, and Gramercy Park. Users of this station likely are traveling between work and home. 
 * The West St and Chambers St area includes commuter destinations like, municipal buildings, couthouses, law firms, etc. Examples are: The Manhattan Muncipal Building, the Tweed Courthouse, and New York City Hall. 

### Weekend bike stats:
![Screen Shot 2023-05-20 at 12 59 30 AM](https://github.com/therahgithub/citi-bike-challenge/assets/119986667/9178771b-82d9-44ba-911c-e5dc29701b0e)

#### The weekends tell a more leasurely story. The most common start and end times peak between 1PM and 5; while relatively low at all other hours. In regards to ride count, customers outpace subscribers at the more popular stations, but subscribers maintain the highest frequency overall.

#### The most popular start and end stations are cultural and recreational centers with parks, museums, theaters, restaurants, etc.
 * Grand Army Plaza & Central Park South (start only, did not make the top 10 of end stations)
 * West St & Chambers St
 * 12th Ave and 40th St
 * Central Park South and 6th Ave

### Trip duration stats:
![Screen Shot 2023-05-20 at 1 24 29 AM](https://github.com/therahgithub/citi-bike-challenge/assets/119986667/fb16b405-2363-4a69-90a4-13f05847234c)

On weekdays, subscribers account for a vast majority of total cycle time; while more balance exists between user types on weekends. Interestingly, customers far outpace subscribers in average trip duration for all periods.

When broken down by age, users born in 1969 leave all others in the dust with average trip duration and ride count--only users born in 2001 come close in duration but the 69ers dwarf them in total number of rides. Data below from USA Cycling--showing (as of 2020) the highest percent of cyclists are in the 45-54 age range--sheds some light on the phenomenon but further investigation is necessary to determine the cause of the vast disparity. 

<img width="1071" alt="Screen Shot 2023-05-20 at 1 31 54 AM" src="https://github.com/therahgithub/citi-bike-challenge/assets/119986667/e904d42f-9b1b-40cc-9c0a-eee636425f8c">
<img width="1099" alt="Screen Shot 2023-05-20 at 1 33 16 AM" src="https://github.com/therahgithub/citi-bike-challenge/assets/119986667/17046bc5-115e-4512-b3d7-0733d4508520">

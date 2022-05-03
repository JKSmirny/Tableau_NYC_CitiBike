# Tableau Homework - Citi Bike Analytics

# Tableau Homework - Citi Bike Analytics
My Tableau story:

NYC CitiBike has an extensive data, so I picked up middle of the pandemics, April 2020

Question 1: Which parts of the city are considered to be safe eniugh to pick up a bike late at night? 
Dashboard 1, Dashboard 2
My criteria: 25 or more bike rentals at that hour. 
The time up to 30 min before the hour and 30 mon after the hour.
Late night time range I picked is from 11 pm (22:30) to 1 am (1:29). 
There were not enough trips registered after 1 am to warrant their inclusion in the data set. 
I did not include 10 pm (22:00) trips becuase it enlarged my dataset enourmously, making it impossible to draw any conclusions.

Answer 1: The area from 4st up to 96st in Manhattan looks crowded enough at light night to warrant a bike rental. 
There is also a large cluster of bike rentals around 11 pm (23:00) next to The Continental Army Plaza in Brooklyn. 
Looks like people living tin that area pick up bikes when they arrive there via either subway of a bus.

Question 2a: Is there a gender difference in late night bikes' pick up numbers in NYC??
Dashboard 2,  Sheet 4A, Table_1, Sheet 5A
Late night time range I picked here is from 10 pm (22:30) to 1 am (1:29)

Answer 2a: There are 3 times more male bike riders during late night hours as female ones.

Question 2b: What is a gender difference in early morning bikes' pick up numbers in NYC?
Sheet 4B, Table_2, Sheet 5B
The time up to 30 min before the hour and 30 mon after the hour.
Early morning time range I picked is from 4 am (3:30) to 6 am (6:29). 
Note: I have excluded the riders who have not specified their gender (none before 5:30, 5% between 5:30 and 6:30)

Answer 2b: There is a significant difference in number of female and male riders 
in the early morning hours in NYC: on average there are 3 times more male riders than females (75% vs 25%).

Additionally, there is a drastic increase in the riders' numbers after 5:30: 
there are 3 times more bikes pick-up's at 5 am than at 4 am,
there are 4 times as many bike pick-up's at 6 am than at 5 am,
there are 8 times as many bike pick-up's at 6 am than at 4 am. 

Interesting that the most early morning bike riders in the early morning rent their bikes monthly. 
Hourly renters do not appear at all until 5:30 am and even then they only account for 5%.

Question 3: Is there a difference in the peak hours of bike rental during weekday and weekend? 
Sheet 7A, Sheet 7B, Sheet 9A, Sheet 9B

Answer 3: The peak hours of bike rental on the wekends are from 2pm to 5 pm (13:30-17:29), 
while during weekdays the most bikes are picked ap at around 6pm (17:30-18:29).

Interesting that theare significantly more bike rentals from Tue to Thu than on Mon and Fri. 
The peak hour remains the same, 6pm (17:30-18:29).

Curious fact 1: The most bikes in NYC during April of 2020 were rented by the people, born in 1969.
Explanation: People who rent bikes hourly are not required to specify their age, so they are assigned a default birth year of 1969.
If you look at monthly bike renters, there is not such phenomenon. 
Dashboard 2, Sheet 3

Curious fact 2: 
Female riders tend to pick up bikes in the middle of the day, so do the hourly renters. 
Sheet 6A, Sheet 6B




### Before You Begin

* This assignment will be saved to your Tableau Public account rather than GitHub. 

* If you haven't already, be sure to create a Tableau Public account [here](https://public.tableau.com/s/).

* The free tier of Tableau only lets you save to their public server. This means that each time you save your file it will be uploaded to your Tableau Public profile. 

* You are able to load and continue working on the same workbook.

* When you are finished with your assignment, you will turn in the URL to your Tableau Public workbook along with any additional files used for your analysis. 

## Background

![Citi-Bikes](Images/citi-bike-station-bikes.jpg)

Congratulations on your new job! As the new lead analyst for the [New York Citi Bike](https://en.wikipedia.org/wiki/Citi_Bike) Program, you are now responsible for overseeing the largest bike sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Through the team's efforts, each month bike data is collected, organized, and made public on the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have a number of questions on the program, so your first task on the job is to build a set of data reports to provide the answers.

## Task

**Your task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.** 

**Design 2-5 visualizations for each discovered phenomena (4-10 total). You may work with a timespan of your choosing. Optionally, you may merge multiple datasets from different periods.** 

**The following are some questions you may wish to tackle. Do not limit yourself to these questions; they are suggestions for a starting point. Be creative!**

* How many trips have been recorded total during the chosen period?

* By what percentage has total ridership grown?

* How has the proportion of short-term customers and annual subscribers changed?

* What are the peak hours in which bikes are used during summer months?

* What are the peak hours in which bikes are used during winter months?

* Today, what are the top 10 stations in the city for starting a journey? (Based on data, why do you hypothesize these are the top locations?)

* Today, what are the top 10 stations in the city for ending a journey? (Based on data, why?)

* Today, what are the bottom 10 stations in the city for starting a journey? (Based on data, why?)

* Today, what are the bottom 10 stations in the city for ending a journey (Based on data, why?)

* Today, what is the gender breakdown of active participants (Male v. Female)?

* How effective has gender outreach been in increasing female ridership over the timespan?

* How does the average trip duration change by age?

* What is the average distance in miles that a bike is ridden?

* Which bikes (by ID) are most likely due for repair or inspection in the timespan?

* How variable is the utilization by bike ID?

**Next, as a chronic over-achiever:**

* Use your visualizations (does not have to be all of them) to design a dashboard for each phenomena.
* The dashboards should be accompanied with an analysis explaining why the phenomena may be occuring. 

**City officials would also like to see one of the following visualizations:**

* **Basic:** A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey with zip code data overlaid on top.

* **Advanced:** A dynamic map that shows how each station's popularity changes over time (by month and year). Again, with zip code data overlaid on the map.

* The map you choose should also be accompanied by a write-up unveiling any trends that were noticed during your analysis.

**Finally, create your final presentation**

* Create a Tableau story that brings together the visualizations, requested maps, and dashboards.
* This is what will be presented to the officials, so be sure to make it professional, logical, and visually appealing. 

## Considerations

Remember, the people reading your analysis will **NOT** be data analysts. Your audience will be city officials, public administrators, and heads of New York City departments. Your data and analysis needs to be presented in a way that is focused, concise, easy-to-understand, and visually compelling. Your visualizations should be colorful enough to be included in press releases, and your analysis should be thoughtful enough for dictating programmatic changes. 

## Submission 

Your final submission should include:

* A link to your Tableau Public workbook that includes: 
  * 4-10 Total "Phenomenon" Visualizations 
  * 2 Dashboards
  * 1 City Official Map
  * 1 Story 
* A text or markdown file with your analysis on the phenomenons you uncovered from the data.

## Sharing Your Work
In order to share your work, we are asking that you will save your workbook as a .twbx file so that your TA's can grade them.

To save your workbook as a .twbx file, you will just need to select "Save As..." from the "File" dropdown. Then, select the .twbx option.

## Assessment

Your final product will be assessed on the following metrics:

* Analytic Rigor

* Readability

* Visual Attraction


## Hints

* You may need to get creative in how you combine each of the CSV files. Don't just assume Tableau is the right tool for the job. At this point, you have a wealth of technical skills and research abilities. Dig for an approach that works and just go with it.

* Don't just assume the CSV format hasn't changed since 2013. Subtle changes to the formats in any of your columns can blockade your analysis. Ensure your data is consistent and clean throughout your analysis. (Hint: Start and End Time change at some point in the history logs).

* Consider building your visualizations with small extracts of the data (i.e. single files) before attempting to import the whole thing. What you will find is that importing all 20+ million records of data will create performance issues quickly. Welcome to "Big Data."

* While utilizing all of the data may seem like a nice power play, consider the time-course in making your analysis. Is data from 2013 the most relevant for making bike replacement decisions today? Probably not. Don't let overwhelming data fool you. Ground your analysis in common sense.

* Remember, data alone doesn't "answer" anything. You will need to accompany your data visualizations with clear and directed answers and analysis.

* As is often the case, your clients are asking for a LOT of answers. Be considerate about their need-to-know and the importance of not "cramming in everything". Of course, answer each question, but do so in a way that is organized and presentable.

* Since this is a project for the city, spend the appropriate time thinking through decisions on color schemes, fonts, and visual story-telling. The Citi Bike program has a clear visual footprint. As a suggestion, look for ways to have your data visualizations match their aesthetic tones.

* Pay attention to labels. What exactly is "time duration"? What's the value of "age of birth"? You will almost certainly need calculated fields to get what you need.

* Keep a close eye for obvious outliers or false data. Not everyone who signs up for the program is answering honestly.

* In answering the question of "why" a phenomenon is occurring, consider adding other pieces of information on socioeconomic or other geographic data. Tableau has a map "layer" feature that you may find handy.

* Don't be afraid to manipulate your data and play with settings in Tableau. Tableau is meant to be explored. We haven't covered all that you need -- so you will need to keep an eye out for new tricks.

* Treat this as a serious endeavor! This is an opportunity to show future employers that you have what it takes to be a top-notch analyst. 

* Good luck!

## Rubric

[Unit 18 Rubric - Tableau Homework - Citi Bike Analytics](https://docs.google.com/document/d/11hlhJnKmEJgRYL3mUxRcdrz4AIxBU5PXW5fYrRYvgW8/edit?usp=sharing)

- - -

© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.

# DADS5001_Mini-Project
Success rate and trend of Space Mission since 1957 to 2022

# Author
Natchapat Youngchoay <br/>
ID: 6420422013 <br/>
Subject: DADS5001 <br/>

# Dataset Information
File Name: space_missions.csv <br/>
Source: https://www.kaggle.com/datasets/mysarahmadbhat/space-missions <br/>
Total:
- 4630 Rows
- 9 Columns
   - Company
   - Location 
   - Date 
   - Time
   - Rocket
   - Mission
   - RocketStatus
   - Price
   - MissionStatus 

# Analysis
What insight can we get from this dataset if we would like to know which country is a space technology leader and worth investing in with an acceptable success rate of 80%?

First of all, we can analyze the worth of investing by comparing mission status success and failure (failure, partial failure, prelaunch failure).
We can see the result plotted in graph 1, as the success rate is around 89.89%, which is well over the acceptable ratio.

The revolving amount that causes success cases in the space industry will be 96.78%, or around 157084 billion dollars (refer to graph 2).

Especially in 2021, which will be the year with the most spending as well as the most success, as you can see in graph 3 and graph 5 respectively.
However, in graph 5, we can see that the space challenges were lower in 1980–2010 and have come back to bustling again in 2020.

The last analysis point is plotted in graph 4, which is the success rate per country graph. We can see that the most successful country is Russia, followed by USA, Kazakhstan and China.

Moreover, in case we would like to know more information, we can consider via graph 6, which displays the relationship between mission success rate and country compared year by year.

In conclusion, we can decide to invest in the space industry field with an acceptable success rate of 80% in Russia or USA, which can confirm a higher success rate than other countries, especially in 2021.
   
# Graph
</br>
- Graph01: Mission Success Rate
<img src="images/01_SuccessRate.png"
     style="float: left; margin-right: 10px;"
     width="420px" height="400px" />
</br>
- Graph02: Success Rate per Price
<img src="images/02_SuccessRate_Price.png"
     style="float: left; margin-right: 10px;"
     width="420px" height="400px" />
</br>
- Graph03: Price per Year
<img src="images/03_Price_Year.png"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />
</br>
- Graph04: Success Rate per Country
<img src="images/04_SuccessRate_Country.png"
     style="float: left; margin-right: 10px;" />
</br>
- Graph05: Success Rate per Year
<img src="images/05_SuccessRate_Year.png"
     style="float: left; margin-right: 10px;" />
</br>
</br>
- Trend of mission success rate per country year by year
<img src="images/06_Year_Country_SuccesRate.gif"
     style="float: left; margin-right: 10px;" />

# Journey
- Look for datasets related to an interesting topic (satellite) and select dataset 'space_missiion' from kaggle.
- Explore a column and look for a question in the data.
- Create draft version of plotted graph from question.
- Start doing programming
   - Separete Year from Date column.
   - Separate Country from Location column.
   - Set MissionStatus to Success and Fail(Failure, Partial Failure, Prelaunch Failure)
   - Analyze data
      - Data of Success and Fail mission numbers (pie graph1)
      - Relationship between Success Rate and Price (pie graph2)
      - Relationship between Success Rate, Price and Year (bar graph3)
      - Relationship between Success Rate and Country (bar graph4)
      - Relationship between Success Rate and Year (line graph5)
      - Relationship between Success Rate, Year and Country (bar graph6)
      
# Issue
- While import and clean dataset, author found that price data in years before 1964 was unavailable. Consequently, analyzing data with price will have fewer data points than other fields.
- Last set in location refers to country, but some locations are in the sea or set as other places (need to google and set value) 
- Plotting multiple graphs causes data relationship confusion
- A lot of information (refer to Graph6) that displays the relationship between success rate, country, and year. As a result, the author employs a GIF file to display the years one by one.

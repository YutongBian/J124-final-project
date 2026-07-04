# **Passenger Traffic at SFO Rebounded After the Pandemic**

## **Introduction**

San Francisco International Airport, also called SFO, is one of the busiest airports in the United States. Millions of people travel through SFO every year for work, vacations, and family visits. This project looks at passenger traffic at SFO from 1999 to 2025\. Thus I wanted to see how travel patterns changed over time. The data show that passenger traffic increased for many years. In 2020, passenger numbers dropped because of the COVID-19 pandemic. Since then, passenger traffic has recovered and continues to grow.

**Dataset Source**

The data came from the San Francisco Open Data Portal that was given from the Bcourses

Dataset link:

[https://data.sfgov.org/Transportation/Air-Traffic-Passenger-Statistics/rkru-6vcg](https://data.sfgov.org/Transportation/Air-Traffic-Passenger-Statistics/rkru-6vcg)

The original source is San Francisco International Airport.

The dataset includes information about:

* passenger counts  
* airlines  
* geographic regions  
* terminals  
* dates

This dataset is trustworthy because it comes from a government source and is maintained by SFO. However, no dataset is perfect. Passenger counts show the number of trips, not the number of unique people. One person can appear many times if they fly often.

**Analysis Process**

I downloaded the dataset as a CSV file and imported it into Google Sheets. Then I used pivot tables to study the data.

I created pivot tables for:

* passenger traffic by geographic region  
* passenger traffic by year

I used the SUM function to add together passenger counts.

Google Sheets Link:

[*https://docs.google.com/spreadsheets/d/1sxVorobhNJQ2vOK9Ny-YY66ellvwZqYs54MhmPIVleU/edit?usp=sharing*](https://docs.google.com/spreadsheets/d/1sxVorobhNJQ2vOK9Ny-YY66ellvwZqYs54MhmPIVleU/edit?usp=sharing) 

After looking at the data, I have found a few interesting patterns. Passenger traffic increased steadily between 1999 and 2019\. However in 2020, passenger numbers dropped sharply because many people stopped traveling during the pandemic. Passenger traffic then increased again from 2021 to 2025\. I also discovered that most passengers travel within the United States. Asia and Europe are the largest international regions connected to SFO.

**Visualization 1**

**Figure 1\. Passenger Traffic Through SFO by Geographic Region**

Source: San Francisco Open Data Portal

This chart shows where passengers are traveling.

The United States has the highest number of passengers.

Asia has the largest number of international passengers.

Europe is also an important region for SFO.

**Visualization 2**

**Figure 2\. Passenger Traffic at SFO by Year (1999–2025)**

Source: San Francisco Open Data Portal

This chart shows how passenger traffic changed over time.

Passenger traffic increased for many years.

In 2020, there was a large drop because of COVID-19.

Passenger numbers increased again after 2020 and are now close to pre-pandemic levels.

**Additional Analysis**

Besides looking at passenger traffic by year and geographic region, I also want to see passenger traffic by terminal. This analysis showed that Terminal 3 handled the largest number of passengers with more than 455 million passengers between 1999 and 2025\. Furthermore, the International Terminal ranked second followed by Terminal 1 and Terminal 2\.

**Figure 3\. Passenger Traffic by Terminal at SFO (1999–2025)**

Source: San Francisco Open Data Portal.

**Methods**

Initially I downloaded these data from the San Francisco Open Data Portal, then I used Google Sheets to clean the data and create pivot tables. I also added an extra column called year for the second graph. Then I grouped passenger counts by year, geographic region, and terminal to find patterns in the data. Moreover, I also used Google Sheets to make the chart and downloaded them as PNG files, and uploaded them to Github.


**Limitations**

This dataset indeed has some limitations. For example, passenger counts cannot show the number of individual travelers because people who fly many times are counted more than once. Moreover, the data also do not explain why travel patterns changed over time, and the dataset can’t show factors such as airline decisions, ticket prices, economic conditions, or personal travel choices. More reporting and additional sources would be needed to better understand these trends.

## 

## **Ethical Considerations**

Some ethical considerations are that passenger data should be used more carefully. High passenger numbers do not mean that one region is more important than the other since travel patterns can be influenced by many factors, including tourism, business travel, immigration, and economic activity. Journalists should avoid making unfair conclusions about certain places or groups of people merely based only on passenger counts.

## 

## **Conclusion**

In conclusion, passenger traffic at SFO grew steadily for many years before the COVID-19 pandemic. Passenger numbers have dropped sharply in 2020, but they recovered in the following years. As of today, SFO continues to play an important role in both domestic and international travel. This project shows how data can help people better understand changes in travel patterns over time. Personally I choose this topic because I am an aviation enthusiast and I want to finish this project with the topics I am interested in. I am glad I have learned all the ways to process and record data in this class and I will definitely carry this knowledge with me beyond.
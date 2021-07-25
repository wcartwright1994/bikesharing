# bikesharing

**Overview of the Statistical Analysis**

The purpose of the analysis is to create a presentation for seed funding from a potential angel investor for a bike-sharing business in Des Moines, Iowa. This presentation will utilize a Tableau Story created relying on publicly available NYC Citibike data for August 2019.

**Results**

Link to dashboard:
https://public.tableau.com/app/profile/william.cartwright/viz/CitibikeChallenge_16271872527870/CitibikeStory?publish=yes

Visualization 1:
  * Shows the total number of rides taken in August 2019
  * Over 2 million rides were taken in August 2019

Visualization 2:
  * Shows the breakdown between short-term users ("customers") and long-term users ("subscribers") for the rides taken in August 2019
  * Over 75% of users in August 2019 had subscriptions

Visualization 3:
  * Provides insight into the length of trips for each session in August 2019
  * Updated to add an additional filter and column to filter on "Number of Days", as following the instructions resulted in an inaccurate visualization that aggregated sessions longer than 1 day into one data point on the graph
  * The most common session was approximately 5-6 hours
  * Due to a large number of outliers, additional data cleansing must be completed to avoid providing inaccurate data to the potential investor

Visualization 4:
  * Provides insight into the trips taken by different gender for each session in August 2019
  * Based on the data provided, an overwhelming majority of the users are male
  * Providing statistical measures analyzing the preferred trip lengths by gender would be helpful to determine the best course for marketing strategies to different genders

Visualization 5:
  * Heatmap showing the most common rental times by time-of-day and weekday
  * The most popular times for sessions are during morning and evening rush hour during the week and on Saturdays

Visualization 6:
  * Heatmap similar to visualization 5, but also incorporating a gender breakdown
  * This visualization is redundant, as we have already shown that the majority of customers are males in Visualization 4
  * This should be updated to use base values for each genders

Visualization 7:
  * Heatmap showing the most common rental weekday by gender and user type
  * As mentioned above, this is redundant, as we have already shown that the majority of customers are males and subscribers in Visualization 4 and Visualization 2, respectively
  * This should be updated to use base values for each gender and usertype pair 

**Summary**

Based on the publicly available data and scope of the assignment, it can be seen that:
 1. The most common session was 5-6 hours
 2. The most popular time for a session is on weekdays during morning and evening rush hour, as well as on Saturdays
 3. The majority of customers are male

Two additional visualizations that could be added include:
 1. Heatmaps including data from additional months to show the variance in sessions during different times of the year
 2. Time series data including data from additional years to show the growth of the business in NYC

Although this data was collected and put into visualizations, it is important to note that this alone should not be shown to the investor. This data should be compared against data from other cities with bike share programs, as well as projections for how this translates into a profitable business in Des Moines, Iowa. 





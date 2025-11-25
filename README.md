# POWER_BI_INTERN_TASK
nullclass internship task for tweeter analysis

Tasks

1. Plot a scatter chart to analyse the relationship between media engagements and media views for tweets that received more than 10 replies. Highlight tweets with an engagement rate above 5% and this graph should work only between 6PM IST to 11 PM IST apart from that time we should not show this graph in dashboard itself and the tweet date should be odd number as well as tweet word count be above 50.

- Extract Word Count - create a new column name as WordCount to count a lenth of tweet(char/word count).
- x axis- media engagements y axis-media views
- apply tweets that received more than 10 replies filter on this visual columns name- replies 
- should engagement rate above 5% add filter on this visual engagement rate>0.05
- create new column for particular time graph show - ShowChart
- create new column name for check tweet date is odd column name -OddDate
- apply some effect and modification


2. Create a clustered bar chart that breaks down the sum of URL clicks, user profile clicks, and hashtag clicks by tweet category (e.g., tweets with media, tweets with links, tweets with hashtags). Only include tweets that have at least one of these interaction types and this graph should work only between 3PM IST to 5 PM IST apart from that time we should not show this graph in dashboard itself and the tweet date should be even number as well as tweet word count be above 40.
  
- create Even Date Dax column to show the graph in even date only
- x axis:sum of URL click ,y axis: user profile clicks hashtag,tweet category.
- graph work only 3pm to 5pm IST for that create a new Dax column In3to5pm and apply it on this visual
- world count is greater than 40

3. Build a chart to identify the top 10 tweets by the sum of retweets and likes. Filter out tweets posted on weekends and show the user profile that posted each tweet and this graph should work only between 3PM IST to 5 PM IST apart from that time we should not show this graph in dashboard itself and the tweet impression should be even number and tweet date should be odd number as well as tweet word count be below 30.
- create a new category to tweeetcategory for check type of tweet is
- graph show only 3pm to  5pm
- apply filter on wordcount is below 30

4. Create a line chart showing the trend of the average engagement rate over each month of the year. Separate the lines for tweets with media content and those without and this graph should work only between 3PM IST to 5 PM IST and 7 AM to 11AM apart from that time we should not show this graph in dashboard itself and the tweet engagement should be even number and tweet date should be odd number as well as tweet character count should be above 20 and need to remove tweet word which has letter 'C'.
-show line chart for particular time
-show engagement rate over month and year
-create a new column to remove a 'c' letter


5. Develop a visualization that compares the number of replies, retweets, and likes for tweets that have received media engagements greater than the median value. Include a filter for tweets posted in between June and August of 2020 and this graph should work only between 3PM IST to 5 PM IST and 7 AM to 11AM apart from that time we should not show this graph in dashboard itself and tweet date should be odd number and media views should be even number as well as tweet character count should be above 20 and need to remove tweet word which has letter 'S'.
-create a new column to remove 'S'
-apply or graph show 3pm to 5pm and 7am to 11 am
- create a new columns to remove 'S'Letter


6. Analyse tweets to show a comparison of the engagement rate for tweets with app opens versus tweets without app opens. Include only tweets posted between 9 AM and 5 PM on weekdays andthis graph should work only between 12PM IST to 6PM IST and 7 AM to 11AM apart from that time we should not show this graph in dashboard itself and the tweet impression should be even number and tweet date should be odd number as well as tweet character count should be above 30 and need to remove tweet word which has letter 'D'.


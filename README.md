# Twitter User Data Analysis
Scraping tweets for a specified twitter user, and performing some analysis on those tweets.
Tweets were scraped via the python library GetOldTweets3 (https://github.com/Mottl/GetOldTweets3).

The notebook provided performs the analysis for twitter user @realDonaldTrump, however you can change this to be any other user. Data is collected from the start of 2016
to present. 4 years of tweets needs to be collected to perform the Anova/Tukey tests.

Scraping the tweets may take some time. In the notebook I am scraping 4 years worth of tweets for @realDonaldTrump, and since the user tweets often, it took around ~15min 
to collect all the data. I have provided a csv which already contains the tweets for @realDonaldTrump, which you can import instead of having to re-scrape all the tweets.

### Prerequisites
You may need to install the following packages to run the notebook.
- numpy
- pandas
- matplotlib
- wordcloud
- statsmodel
- scipy 
- GetOldTweets3

### Steps to Run
To run the data analysis on some user, simply set the username and run. Currently, the notebook is running against @realDonaldTrump.

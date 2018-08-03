# Wrangle_and_Analyze_Data
Wrangling the tweet archive of Twitter user @dog_rates, also known as WeRateDogs and analysing the data after Wrangling.
For the first step, I gathered data from three soucres,

Sources are:
a) The WeRateDogs Twitter archive is provided by twitter_archive_enhanced.csv which is downloaded manually .
b) The next table to be extracted is the Image Prediction table which I downloaded programmatically. This file (image_predictions.tsv) is hosted on Udacity's servers and should be downloaded programmatically using the Requests library.
c) The next piece of data was the most difficult to gather out of the three. Using the tweet IDs in the WeRateDogs Twitter archive, query the Twitter API for each tweet's JSON data using Python's Tweepy library and store each tweet's entire set of JSON data in a file called tweet_json.txt file. The data in this table consists of information like retweets and favourites for that particular tweet. It took me several tries and hours for wait to get finally data

II. Assessing: After gathering all the data I divided the assessing part into two segments: a) Manual Assessment b) Programmatic Assessment.
a) For Manual Assessment, I looked for errors by looking from the tables visually and check for Data Tidiness.
b) For Programmatic Assessment , I looked the .info() function to check for Data Quality . I also assessed individual columns in seek for any data issues.
At the end of this process I came across 9 Data Quality Issues and 3 tidiness Issues.

III. Cleaning:
For the final step of the wrangling act I rectified 9 Data Quality Issues and 3 Tidiness IssuesI initially made copies of the original tables to allow me to work with the copied table and experiment with them which turned out to be extremely useful as I lost the data in the copied data several time due to wrong code or logic.

IV. For the fourth step I used the cleaned data to analyze it and get insightful observations using matplotlib, pandas and numpy.

This project on Data wrangling is comprised of the following three steps:
1. Data Gathering
2. Data Accessing
3. Data Cleaning

1. Data Gathering:
a. twitter_archive_enhanced.csv is a given file. 
b. image_predictions.tsv was downloaded on Udacity's servers by sending requests
c. tweet_json.txt -> Using the tweet IDs in the twitter_archive_enhanced.csv, i queried the Twitter API for each tweet's JSON data using Python's Tweepy library and store each tweet's entire set of JSON data in a file called tweet_json.txt file

2. Data Accessing:
Detected and documented quality and tidiness issues by inspecting programmatically and visually. This can be seen in the wrangle_act.ipynb file.

3. Data Cleaning:
Clean each of the documented quality and tidiness issues. This cleaning is done in the wrangle_act.ipynb file. The resulting data frame is a high quality pandas data frame.

Finally, store the clean data frame as twitter_archive_master.csv. wrangle_act.ipynb will include very basic analysis and visualization (as this project focuses mostly on wrangling). Moreover, wrangle_report.html briefly describes the wrangling efforts, while act_report.html communicates the insights and displays the visualizations produced by the wrangled data.
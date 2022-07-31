# Title:
Dog Rating Tweet Retrieval and Analysis 

## Description
This project completes the gathering, cleaning, analysis and visualization of a data. A master dataset is to be generated from data gathered from different sources. The sources for the gathered data include:
- A file downloaded manually `twitter_archive_enhanced.csv` containing basic information about 5000 archived tweets by the user @dog_rates
- A programmatically downloaded tsv file `image_predictions.tsv` using the requests library containing predictions results from a neural network identifyting the dog images per tweet.
- A txt file `tweet_json.txt` containing more tweet information stored line by line in JSON format. This is obtained by querying the Twitter API using tweepy and the tweet ids for about 5000 archived tweets.

The master dataset `twitter_archive_master.csv` is then created, then analyzed and some insights are generated for visualisations thereafter.

The jupyter notebook code file is named `wrangle_project.ipynb` other reports and visualisations are named similarly.

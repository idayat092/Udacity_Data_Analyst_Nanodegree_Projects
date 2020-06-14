## PROJECT TITLE: Wrangle and Analyze Data

Data Wrangling is the process of gathering data from a variety of sources and in a variety of formats, assessing its quality and tidiness, then cleaning it.

The dataset I will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog.

#### The data gathering is from three sources:
	- File on hand: A CSV file that was provided in the classroom
	- Flat file to be downloaded from Udacity Website
	- Twitter API: Using the tweet IDs in the WeRateDogs Twitter archive (file on hand), I will query the Twitter API for each tweet's JSON data using Python's Tweepy library
	

#### After cleaning, all three files are then merged into a single dataframe and stored as a csv file and into a SQL lite Database

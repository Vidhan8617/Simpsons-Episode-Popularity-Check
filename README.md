# Simpsons-Episode-Popularity-Check
Task: Predict whether a Simpson episode is 'popular' with Machine Learning
Popularity is defined by "IMDB rating" from simpsons_episodes.csv file.
csv files are provided and loaded as source data. The original data are downloaded from https://data.world/data-society/the-simpsons-by-the-data.

##Goal
Construct feature columns for each episode that you think are related to popularity with the given datasets and construct the target column 'popularity', which is a binary class.

##Example feature columns

How many characters are in that episode?
How many lines are spoken by each character in that episode?
etc.
We will guide you through the preprocessing, or you can jump to down load the processed sample data and work on machine learning models.

The sample data will not give you the best result, and it is suggested that you go through the preprocessing and learn how different techniques affect model results. Also, you are more than welcome to create your own features and explore all possibilities!

##Pre-processing
Calculate number of lines spoken by each character in each Episode
Note: Here we also count interjections even there's no words. (i.e. speaking_line=false, spoken_words=Nan etc.)

##Splitting
we further split the dataset on basis of IMDb Ratings

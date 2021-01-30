# Gather, Wrangle and Analyse Data
## By Rahal Mehdi Abdelaziz


## Project Overview 
The goal of this project was to learn how to gather data from an API wrangle and analyse data.
The summary of findings can be fount on the act_report.pdf file


## DataSet

This data was gathered from the WeRateDog page on twitter
We have 3 datasets:
• Twitter-archive-enhanced: a csv file downloaded manually and wrangled as a dataframe named "df_1".
• Image_predictions: a tsv gathered programmatically using the ‘requests’ library from this url : 
https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv 
and wrangled as a dataframe named "df_2".
• Tweet_json : a txt file gathered from tweets JSON data using the twitter API ‘tweepy’, then read line by line to be wrangled as a dataframe named "df_3".


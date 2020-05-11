# Twitter Archive Analysis - A Data Wrangling Project

## Dataset

Two datasets are merged and used in this Udacity project. 'Enhanced twitter archive' dataset contains basic tweet data, such as tweet id, ratings, text of the tweet and so on, of 2000+ tweets. The dataset requires a lot of wrangling effort. To get accurate data, I queried Twitter API using Tweepy library. 

Image predictions dataset provided by Udacity to classify breeds of dogs in pictures.


## Summary of Wrangling Efforts

This datasets are perfect for practicing wrangling as they have a wide variety of quality and tidiness issues. 
- use JSON library to extract data from JSON formatted tweets obtained from Twitter API
- join dataframes
- use `melt()` to rearrange columns and rows
- fix missing values
- convert datatypes
- remove redundant, duplicated, inaccurate values and rows



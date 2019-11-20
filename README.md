# Coursera_Capstone: Prediction of One's Favor to a Place
This project is for the Capstone Project of Applied Data Science in Coursera

## Introduction

### Background
People like traveling nowadays. Some go out for business and others go out for sightseeing. After staying in a place long enough (for example, 1 week), people tend to rate that place based on its neighborhood: I like this place because there are a lot of restaurants; I hate this place because I cannot find a grocery here. If going to a boring place, the tourist would think this is an uninteresting trip. Therefore, it becomes very important to predict whether a person like this place or not. Otherwise, it will only be a waste of time and energy to travel around. But how could we know that? How much does the neighbor affect a person’s favor to a certain place? Do the places he likes have something in common? And is it possible to use this method to predict his favor to another place?

### Problem
It is assumed that the factors that affect a person’s favor to a place is the neighborhood features. This capstone project will use myself as an object to find out the neighborhood features of the places I have stayed. In addition, I will try to predict my like or dislike to a random place I have never been to.

### Interest
The tourist agencies will be extremely interested in clustering tourists’ favor to different places. Also, it is quite valuable for them to recommend the similar sightseeing spots to a tourist once they find out his love or hate to a certain kind of places.

## Data Acquisition and Cleaning

### Data Sources
I will use myself as an object. Therefore, I create a table of places and rating. All the places I have been to are put in the left column and my rating of each place (1-10; the higher, the better) are put in the right column. Below is an example:

| Places  | Rating |
| ------------- | ------------- |
| Baltimore, the United States | 6 |
| Beijing, China | 3 |
| Boston, the United States | 5 |
| Cambridge, the United Kingdom | 8 |
| Chengdu, China | 5 |

This table will be uploaded to the Jupyter Notebook as a data frame. I will use this data frame as the original data to test the influence of neighbors on my rating of places. In reality, more samples of people’s rating of places could be attained, much more than the test one of thirty. The more data for machine learning, the more comprehensive the model will be.

### Data Cleaning
Since the original data is created by me, the data cleaning process will be very simple. However, in reality, special processes will be needed to clean up the data in these two columns, for example, the format of place and rating.

### Feature Selection
Only two features are original features: places and ratings. One’s rating of a place is indispensable in this model. In addition, as the analysis continues, more feature will be attained: latitude and longitude of the place, venues of that place, latitude and longitude of venues and category of venues. 

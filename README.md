# Controversial YouTube Videos

**Collaborators**

Angel, Noah, Dan, Cree

## Main Question

What trending videos was the most liked and most disliked (controversial)? Does location have anything to do with the number of controversial videos?

## Target Data
 
Kaggle CSVs - https://www.kaggle.com/datasnaek/youtube-new#USvideos.csv

Datasets that display Trending Date, Video ID, Views, Likes, Dislikes, Comments etc.

## Describe data exploration and cleanup

Throw out categories with low numbers of videos; Delete any video duplicates; Remove videos where comments & likes are disabled

## Analysis Process (Jupyter Notebook)

Input all data from US (include other countries for comparison if time permits). Defining "controversial": if the likes/dislikes ratio is between 40% to 60%, the video is controversial. We might have to be more liberal with those parameters since there are five times as many likes than dislikes. Controversial Score = (x number of likes / total number of likes&dislikes) 

## Summarize conclusions (numerical summary + visualization)
“Politically charge videos vs Justin Bieber”
Logan Paul, Call of Duty, Childish Gambino = extremely controversial

## Discuss the implications of your findings and what they mean
Find limitations

## Tell a good story
What we think of as controversial may not be what we actually think 
Niche content everyone likes it there [far right, progressives, etc]

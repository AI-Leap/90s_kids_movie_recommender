The link to the medium blog post
https://medium.com/@linnphoopyaepyae/90s-kids-movies-recommender-system-e7257fef541e

# 90s-Kids Movie Recommender System

![90skidsmovies](https://user-images.githubusercontent.com/20230956/125284756-e0451280-e33f-11eb-9a24-aa57eb02e7d1.png)


This project works on Movielens dataset and build the recommender system using Content-based and Collaborative-filtering methods.

## Table of Contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info

You can download the 6 csv files from the link below and paste them in movies_lens folder.
https://drive.google.com/drive/folders/1zITqnpLJp1toe1OnI5fKpU1qpEj3SgTa?usp=sharing

## For a quick look, open the html files for each notebook.

Content-based filtering used 'tag' as the main feature used and we are going to find the most relevant 'tag' and extract the features of the tag content. There are clean tags with relevancy scoring. That makes it easier to get the most relevant tags for the movie.

For collaborative filtering, we are going to use the rating of the movie given by each user to find the similarity between the two users. We just use similarity-based on to calculate how similar the user interests are. The higher the similarity score, the more the user profiles are closed.


## Technologies
The following libraries are used:
* pandas
* numpy
* collections
* nltk
* matplotlib
* seaborn
* TF-IDF

## Setup
```
$ pip install jupyter
$ pip install pandas numpy matplotlib seaborn scikit-learn
```

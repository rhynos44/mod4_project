# Recommender System using MovieLens
> Ryan Sims

## Intro

> Utilizing the ratings from users, build a recommender system that can suggest the top 5 movies to watch.  This model was built on existing user ratings providing suggestions for other users.  The method used was collaborative filtering as it handles the user-user engagement.  The greatest factor in collaborative filtering is how simple it is to implement.  The data frames did not need to be adjusted much to work with surprise.

## EDA
> Inital analysis revealed that most of the ratings given were a 4 out of 5.
> The dataset consists of 610 users, with an additional being created at the end to preveiw recommendations.
> The dataset also contained 9,724 different movie titles.
> Eventhough there are only 610 users, there were over 100,000 ratings amongst them

## Results

> The model was able to recommend 5 movies based on the ratings from the generated new user.  The model also estimated the ratings for all the movies in the dataset.  
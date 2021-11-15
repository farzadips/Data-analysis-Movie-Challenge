# Challenge: Machine Learning on Movies

The goal of this challenge is to build a Machine Learning model to predict the genres of a movie, given its synopsis. Your solution will be evaluated on:
- The performance of your Machine Learning model.
- The quality of your code.

## Challenge 
To succeed, you must implement a Python package called `challenge`, which exposes a REST API according to the following specifications.

### Your API must expose:

1. A training endpoint at `localhost:5000/genres/train`,
   1. To which you can POST a CSV with header: `movie_id,synopsis,genres`, where `genres` is a space-separated list of movie genres.
2. A prediction endpoint at `localhost:5000/genres/predict`,
   1. To which you can POST a CSV with header: `movie_id,synopsis`
   3. Which returns another CSV with header: `movie_id,predicted_genres`, where `predicted_genres` is a space-separated list of the top 5 movie genres (sorted).

### Important notes:
- A dataset is provided in the [datasets](./datasets) directory.
- Feel free to use any library you want.
- [Reach us](mailto:dev@mediascale.eu) when you completed the challenge.

### Gitlab setup

1. [Fork this repo](https://gitlab.com/mediascale-benelux/movies-challenge).
2. In your forked challenge repo:
   1. Go to `Settings > General > Visibility [...]` and set the project visibility to `Private`.
   2. Go to `Settings > Members > Invite Member` and add `mediascale` as a `Reporter`, so we can follow along with your progress.


## Good luck!
-- The Mediascale team

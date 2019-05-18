# boxoffice
Kaggle TMDB Box Office Prediction Competition 2019

Link: https://www.kaggle.com/c/tmdb-box-office-prediction

### Authors

* **Sean Trinh**
* **Hariharan Vijayachandran**

### Team Name

* CS583Team

### Rank

* N/A

## Overview (from Kaggle)

### Description

We're going to make you an offer you can't refuse: a Kaggle competition!

In a world... where movies made an estimated $41.7 billion in 2018, the film industry is more popular than ever. But what movies make the most money at the box office? How much does a director matter? Or the budget? For some movies, it's "You had me at 'Hello.'" For others, the trailer falls short of expectations and you think "What we have here is a failure to communicate."

In this competition, you're presented with metadata on over 7,000 past films from The Movie Database to try and predict their overall worldwide box office revenue. Data points provided include cast, crew, plot keywords, budget, posters, release dates, languages, production companies, and countries. You can collect other publicly available data to use in your model predictions, but in the spirit of this competition, use only data that would have been available before a movie's release.

Join in, "make our day", and then "you've got to ask yourself one question: 'Do I feel lucky?'"

### Evaluation

It is your job to predict the international box office revenue for each movie. For each id in the test set, you must predict the value of the revenue variable. 

Submissions are evaluated on Root-Mean-Squared-Logarithmic-Error (RMSLE) between the predicted value and the actual revenue. Logs are taken to not overweight blockbuster revenue movies.

**Submission File Format**

The file should contain a header and have the following format:

id,revenue

1461,1000000

1462,50000

1463,800000000

etc.

You can download an example submission file (sample_submission.csv) on the Data page.

### Timeline

The competition will conclude May 30, 2019 at 11:59 PM UTC.

### Prizes

At the conclusion of the competition, the top three most popular Kernels--as determined by number of upvotes at the deadline--will receive Kaggle Swag. Only Kernels created/forked after the start of the competition will be eligible for a prize.

Happy modeling and thanks for being great Kernelers of the Kaggle community!

## Data (from Kaggle)

### Description

In this dataset, you are provided with 7398 movies and a variety of metadata obtained from The Movie Database (TMDB). Movies are labeled with id. Data points include cast, crew, plot keywords, budget, posters, release dates, languages, production companies, and countries.

You are predicting the worldwide revenue for 4398 movies in the test file.

Note - many movies are remade over the years, therefore it may seem like multiple instance of a movie may appear in the data, however they are different and should be considered separate movies. In addition, some movies may share a title, but be entirely unrelated.

E.g. The Karate Kid (id: 5266) was released in 1986, while a clearly (or maybe just subjectively) inferior remake (id: 1987) was released in 2010. Also, while the Frozen (id: 5295) released by Disney in 2013 may be the household name, don't forget about the less-popular Frozen (id: 139) released three years earlier about skiers who are stranded on a chairlift...

### Acknowledgements

This dataset has been collected from TMDB. The movie details, credits and keywords have been collected from the TMDB Open API. This competition uses the TMDB API but is not endorsed or certified by TMDB. Their API also provides access to data on many additional movies, actors and actresses, crew members, and TV shows.

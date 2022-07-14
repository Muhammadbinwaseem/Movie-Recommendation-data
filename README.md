# Movie-Recommendation-data:

## File Intro:

THe data set is about movies sale and purchase and credit of the movie. the sales man is to prefreance this data. and to decision about on 
the basis of this data. i download data set on kaggel and then apply algorithems. data set is greater than 25 mb so github not appload 
the file. i attached the kaggel data set link bellow.

## Link:

https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset

## Introduction:

This system help users discover movie. the salemen of company knows which movie user are prefre.an of diffrent algorithem that combine to
predict the prefrence of movies for a users.on the basis of they make suggestion.


## Content Based Filtering And Colabrative Are The Types Of Recommender System:

i have build content based recommender system content based recommendation system work more closely with item attribute rather than user 
data.it is predict the bhaviour of a user.


## Analyze Document With TF:

frequency of any word in document and is given by dividing instances with total instances the another part is idf known as inverse document 
frequency relative count of document containg the term and is given as a log

### this is given a matrix where a column represents a word to overall vocablary.

## overall importance of each word on the document appear be given by TF-IDF

TF-IDF usefull in reducing the importance of word occur frequently our movie description function would in turn,reduce their significance 
in computing the final similarity score.
 
## Cosine Similarity

i used similarity of the cosine to find similarity. and used score reason it is independent magnititude and also relatively very easy or fast to calculate.

## Time To Make A Recommendation

## Steps

1) Retrive index of movies given its title
2) compute a list of similarity scores for the targeted movies for all movies in data set then convert into a list of tuple
3) sort list of tuple based on similarity scores
4) Get top 10 elements of the list
5)output the title to correspond to the indices of top elements 

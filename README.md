# bechdel
Predicting whether movies pass the Bechdel test


#### What is the question you hope to answer?
* Without confirming with a script, can I predict whether a movie will pass the Bechdel test?
* Can I predict if a movie will be a "good movie"? What is the liklihood of a movie passing a certain user rating threshold?
#### What data are you planning to use to answer that question?
* Bechdel test data
* TMDb movie data
* Other sources of information about people involved in movies?
  * I'd like to incorporate outside sources of information about directors and producers, if possible, from lists such as XXX
#### What do you know about the data you're using so far?
* Bechdel test data from bechdeltest.com 
  * community generated Bechdel test results for XXXX movies
  * test results are categorical 0-3 depending on how many parts of the test are passed
  * all movies have IMDB IDs
* TMDb
  * data about released and upcoming movies, as well as information about all the people involved in the movie (actors, producers, etc.)
  * has user ratings
  * also has IMDB IDs for each movie
#### Why did you choose this topic?
These are two things that I find difficult to predict from movie trailers or descriptions alone. Often there are movies with strong female leads, but only one or they only talk to other women about men.  There are also a bunch of movies that pass Bechdel but aren't very good movies.  I'd be great to have a prediction of both pieces of information before deciding to go see a movie.

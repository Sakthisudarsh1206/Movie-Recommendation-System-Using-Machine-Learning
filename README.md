This is Movie Recommendation system project which categorizes data using content-based filtering.
Here modules pandas,numpy,sklearn and nltk are used
First data preprocessing is done to the dataset acquired from TMDB website so that the genres, overview(blurb), cast, crew and title columns are put in list with comma seperated but with no space between each of the words
Then the the columns genres, overview,cast,crew are put in one single column- label 
Following this vectorization is done. Algorithm used was Bag of Words.
Porter Stemmer was utilized to remove the repeating english words and stop words.
Cosine similarity was found between each of the vectors to find similar movies.
Top 5 recommendation is printed.

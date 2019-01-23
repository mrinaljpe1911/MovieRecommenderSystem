# MovieRecommenderSystem
A Movie Recommender System with the serindipity movie DB

I have built a simple movie recommender system using the serindipity dataset.

Initial cleaning of dataset 'movies' was done on R, where another dataset with movie summaries was joined, missing values handled,
and columns formatted

    movies.csv contains movie names, and summary has been added

    tags.csv contains movie tagwords

    tag_genome.csv contains movie tagwords with relevance

    training.csv contains user ratings

Systems built:

Genre based popularity-wise ordered recommender

Content based
      
      Director, cast, genres, tag words similarity recommender
      Keyword (from summary) based similarity recommender
      Hybrid of the above two ordered by populaity recommender

Collabarative filtering 

    Director, cast, genres, tag words and Keyword (from summary) similarity recommender 
    AND 
    tailored to the personal taste of each user



# Book Recommendation
Designing a machine learning model to create a book recommendation system.
The designed recommendation system provides results in the form of titles or types of books that match user preferences.

Two recommendation system techniques are used:
1. **Content-based Filtering**, filtering that uses similarities between items to recommend items that have similarities with what the user likes. For example, if user A watches two funny cat videos, the system can recommend funny animal videos to the user.
2. **Collaborative Filtering**, filtering that uses similarities between queries and items simultaneously to provide recommendations. For example, if user A has similarities with user B, and user B likes funny cat videos, the system can recommend funny cat videos to user A (even though user A has never seen a video similar to a funny cat video).

There are 2 datasets used:
1. book_dataset.csv
2. rating_dataset.csv

Modelling:
1. Content-based Filtering
In Content-based Filtering, a function is created for the same book recommendations according to the results of TF-IDF and cosine similarity that have been created. The results that will be displayed are 10 book titles that are almost the same as the defined book title.
2. Collaborative Filtering
In Collaborative Filtering, a function is created using tf.keras.Model. The results that will be displayed are 10 recommended book titles


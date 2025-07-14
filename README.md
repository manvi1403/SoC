#SoC Midterm
I explored the Pandas library in Python and learned how to modify and edit CSV files using various commands. I also gained an understanding of key concepts such as cosine similarity, cosine distance, TF-IDF vectorizer, and count vectorizer.

Additionally, I learned how to merge, join, and concatenate multiple files, which was especially useful in Week 2 when I needed to combine different datasets containing distinct information about movies with the same ID. This helped in consolidating all relevant details of a particular movie into a single file.

I also learnt about text preprocessing in NLP, tokenization, lowercase conversion, stopwords removal, stemming, lemmetization and text processing with NLTK.

In Weeks 3 and 4, we were provided with code by the mentor, which we had to understand thoroughly.Week3.ipynb and Week4.ipynb contains these codes. We were also given helpful YouTube resources to support our learning and project development. 

Based on the codes from Week 3 and Week 4, we were required to write our own code to filter relevant data (from the file generated in Week 2) that would be used for making movie recommendations.

The filter_data.ipynb notebook is responsible for extracting and processing important textual features from the dataset. The movie_recommen.ipynb notebook then takes these processed features, converts them into vectors using CountVectorizer, and calculates similarity scores between movies using cosine similarity.

A movie name is entered through a widget. If the movie is not found in the dataset, it suggests movies with similar titles. If the movie is found, it generates recommendations based on similarity scores computed from a combined column of overview, genre, and keywords. These recommended movies are then sorted by popularity, and the system displays the top 10 recommendations along with the input movie name.

# Sprint_13: Natural Language Processing

# Module 1: Yelp Coffee Shop Review Analysis
We analyzed a dataset of Yelp coffee shop reviews. Our goal was to extract insights from the reviews about different coffee shops. We began by cleaning and preprocessing the review data, which involved tokenization (breaking down the text into individual words), removing stop words and punctuation, and lemmatization (reducing words to their base or root form). We then visualized the most common words in the reviews, both overall and split by positive and negative reviews.

We also examined the relationship between star ratings and word usage in the reviews. This involved extracting the star ratings from the review data, splitting the reviews into positive (4 and 5-star ratings) and negative (less than 4-star ratings), and comparing the most common words in each group. Our analysis provided interesting insights into what factors contribute to positive and negative experiences at coffee shops, according to Yelp reviews.

# Module 2: Text Data Representation and Similarity Search (Vector Representations)
We focused on representing text data in vector form and utilizing those representations for similarity searching. We started with raw text data, cleaned it by removing HTML tags, tokenized it using the spaCy library, and transformed it into numerical representations using both CountVectorizer and TfidfVectorizer from Scikit-Learn.

We then trained a NearestNeighbors model on our document-term matrix to find similar job descriptions based on a given job query. This allowed us to see how different vector representations of the text data could influence the results of the similarity search. Our work demonstrated the importance of thoughtful text preprocessing and the power of vector representations for exploring and analyzing text data.

# Module 3: (Document Classification)
Coming soon...

# Module 4: (Topic Modeling)
Coming soon...

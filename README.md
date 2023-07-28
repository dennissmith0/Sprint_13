# Sprint_13: Natural Language Processing

# Module 1: Yelp Coffee Shop Review Analysis
We analyzed a dataset of Yelp coffee shop reviews. Our goal was to extract insights from the reviews about different coffee shops. We began by cleaning and preprocessing the review data, which involved tokenization (breaking down the text into individual words), removing stop words and punctuation, and lemmatization (reducing words to their base or root form). We then visualized the most common words in the reviews, both overall and split by positive and negative reviews.

We also examined the relationship between star ratings and word usage in the reviews. This involved extracting the star ratings from the review data, splitting the reviews into positive (4 and 5-star ratings) and negative (less than 4-star ratings), and comparing the most common words in each group. Our analysis provided interesting insights into what factors contribute to positive and negative experiences at coffee shops, according to Yelp reviews.

# Module 2: Text Data Representation and Similarity Search (Vector Representations)
We focused on representing text data in vector form and utilizing those representations for similarity searching. We started with raw text data, cleaned it by removing HTML tags, tokenized it using the spaCy library, and transformed it into numerical representations using both CountVectorizer and TfidfVectorizer from Scikit-Learn.

We then trained a NearestNeighbors model on our document-term matrix to find similar job descriptions based on a given job query. This allowed us to see how different vector representations of the text data could influence the results of the similarity search. Our work demonstrated the importance of thoughtful text preprocessing and the power of vector representations for exploring and analyzing text data.

# Module 3: Document Classification in Whiskey Reviews
Assignment 3 centered on the task of document classification, where our goal was to classify whiskey reviews into different categories based on the text of the reviews. The initial stage involved cleaning the text data to ensure that our models would be learning from clear, consistent information. This included removing unwanted characters and normalizing the text.

Next, we set up our data for machine learning by defining our feature (the review text) and the target variable (the review's rating category). We then employed a series of different machine learning models, including RandomForestClassifier, GradientBoostingClassifier, XGBClassifier, CatBoostClassifier, and LGBMClassifier. These models were integrated into a pipeline with a TF-IDF Vectorizer, which transformed the text data into a numerical format that the models could process.

To optimize our models, we conducted a grid search with cross-validation. This iterative process adjusted the hyperparameters of the pipeline, leading to improved model performance.

We then explored the use of Latent Semantic Analysis (LSA), a technique for dimensionality reduction and topic discovery in text data. Our LSA pipeline incorporated a TF-IDF Vectorizer and TruncatedSVD and was followed by a classifier.

Then, we used the Spacy library to create word embeddings for our data, and then trained a RandomForestClassifier on these embeddings. We used the model's out-of-bag score as an estimate of its performance on unseen data.

Finally, the assignment concluded with research into sentiment analysis and Singular Value Decomposition (SVD). These two important concepts provided further insights into the processing and analysis of text data, and the mathematical foundations that underpin many machine learning techniques.

# Module 4: (Topic Modeling)
Coming soon...

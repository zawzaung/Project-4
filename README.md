# Project-4

1. Yelp text reviews, the review date and the star rating are scraped from Yelp page of Purple Kow Tea Shop.  The code for web scraping can be found in 'scraping_yelp' notebook.

2. The main notebook of project4 is titled 'NLP_yelp_review'.  
    A. The pickled file is loaded in this notebook and EDA is performed. 
    B. The data is cleaned, lemmatized and tokenzied.  
    C. Topic modeling is explored using LSA and NMF with TF-IDF and CountVectorizer.  NMF with TF-IDF is chosen since it produced the most coherent topics.
    D. For each review, the topic with the highest weight is assigned as the dominant topic. Then each review's dominant topic is given a sentiment label according to the star rating.  Star rating of 5-4 is labled positive, 3 Star is labled neutral and Star rating of 1-2 is labeld negative.
    E. Sentiment Analysis on each topic is explored.  
    
3. Topic modeling with LDA is also explored in the notebook (yelp_LDA_topic_modeling), but was not an optimal model for this project. 

4. WordCloud visualization for topic modeling is performed in the notebook (WordCloud).

5. Sentiment analysis using Vader is briefly explored in the notebook(Sentiment_Analysis_vader) for the learning purpose.  The result is not used in this project.
    

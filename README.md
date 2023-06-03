# UGC (User Generated Content) analysis on an e-commerce site using natural language processing and Web-Crawling.
Natural Language Processing based analysis of UGC (User Generated Content) on e-commerce site.
# Introduction: 
Excited to share my latest data science, ML, and Natural Language Processing project built on  Web-Scraping, Data crawling, and analyzing product reviews and ratings! Many machine learning methods, e.g., naïve Bayes, decision tree, decision table, and logistic regression, have been investigated for review text classification in this project. 

# Related Work:
# Data Crawling >> Data Preprocessing >> Sentiment lexicon generation >> Training and Testing data for accuracy#

1. The data crawling step provides a raw form of the latest and genuine data foundation for the next steps. In the web-scraping method, I used Selenium, BeautifulSoup, and Requests libraries of Python in addition to Pandas DataFrames to scrape reviews.
2. Since this UGC(user-generated content) is typically unstructured, data preprocessing is necessary. Typical preprocessing includes useless element (e.g., hashtag, URL, and special symbol) removal, stop word removal, part of speech (POS) tagging, named entity recognition, and fake information filtering. In some special language contexts, e.g., Chinese, some special preprocessing, e.g., word segmentation, may be needed.
3. Data Cleaning involves Null spaces removal, duplicate identification and removal, Tokenization, Stemming and Lemmatizing, and stopwords removal.
4. Performed Exploratory data analysis and made a few plots, review length, count, rating distribution table, and formation of the word cloud.
5. The seed Vader sentiment lexicon is a small set of high-frequency positive sentiment words and negative sentiment words. Here I determined the polarity scores and assigned Positive, Negative, and Neutral sentiments, and determined their compound.
6. Accuracy score testing using a Decision tree, decision table, logistic regression and Naive Bayes methods and formed classification report.

# Used Stack: 
Language: Python 
Libraries: Selenium, Pandas, BS4, Scikit-Learn, Natural Language Toolkit (NLTK)

# Conclusion:
1. This work highlights the importance of considering competition in product performance and sentiment analysis. This consideration may be applicable to performance analysis regarding other types of entities (e.g., individuals and organizations) in other contexts.
2. Customer satisfaction and thoughts are neutral about the product.
3. Competitive advantage analysis.

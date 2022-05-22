# Mining-reddit-posts-on-EVs 
The code in this repository can be used to mine a set of reddit posts through LDA topic modeling and Aspect Based Sentiment Analysis (ABSA):
1. Use the code in “LDA_Mallet_Grouped.ipynb” to get the main themes (LDA topics) discussed in the collected posts.
2. Use the code in “ABSA.ipynb” to get the sentiments for a selected set of aspects related to EVs. 

## Notes:
1. Please note that the list of aspects in step 2 is selected from the topics lists on step1
2. To get reddit posts: you may use the open source tool [subreddit-comments-dl](https://github.com/pistocop/subreddit-comments-dl).

## Main Tools
1. Gensim 3.8 # this is important as Mallet support has been stopped in the later versions from Gensim 
2. Spacy # version when this code was run was 3.2.1; later version didn't produce the exact results (mainly as the produced vocabulary was different).
3. Vader tool in NLTK package 

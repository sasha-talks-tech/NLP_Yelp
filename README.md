# NLP_Yelp
In this project I analyze the yelp restaurant review dataset for the purpose of topic modeling. The data was gathered from the [Yelp Dataset Website](https://www.yelp.com/dataset). Several dataframes are merged together to obtain desired information. The dataset was filtered to contain restaurant data only, and further reduced to only contain Las Vegas data. 
***************************************************
### Pre-processing:
The data was cleaned first. The reviews were lowercased, stopwords and punctuation was removed, and the corpus was then lemmatized, stemmed and tokenized. The corpus was then vectorized in order to obtain document-term matrix.
***************************************************
### Modeling:
Libraries used: NLTK, SpaCy, gensim and scikit-learn. <br>
The document-term matrix obtained in the previous step was used for topic modeling with LSA and LDA. LDA seemed to produce good results. PyLDAvis was used to produce a visualization of topics.
***************************************************
### Results:
##### Prevalent topics discovered: <br>
  * Hotel: Vegas strip, bar, casino
  * Promptness: things taking a long time, both service and food
  * Surf and Turf: steak and lobster dinner, salad, shrimp, bread, dessert
  * Casual dining: pizza, burger, chicken, tacos, sandwich
  * Positive experiences: service, staff friendliness, food quality and sushi.


# Topic-Detection-using-LDA
Latent Dirichlet Allocation: 
LDA is used in machine learning and specifically in NLP applications to discover topics in a collection of documents, and then automatically classify 
any individual document within the collection in terms of how "relevant" it is to each of the discovered topics. A topic is considered to be a set of terms
(i.e., individual words or phrases) that, taken together,suggest a shared theme.

Here in this project I have taken a series of speeches from www.pmindia.gov.in and attempted to detect topics of the speech.

LDA lets us mention the number of topics to be detected from the pool of text. LDA then assigns group of topics which comes together to represent a speech.

In this project we have provided 8 number of speeches. I have attempted to detect topics with 3 modes of pre-processing.
1. Using all the text in the data
2. Using only nouns present in the data
3. Using only nouns and adjectives present in the data.

I have tried the LDA model with 3 to 9 number of topics to be detected. It is found that with only nouns, number of topics as 8 and passes at 100,
we can differentiate the topics accurately.

Reference used: https://github.com/adashofdata/nlp-in-python-tutorial/blob/master/4-Topic-Modeling.ipynb

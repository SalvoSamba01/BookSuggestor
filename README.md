# BookSuggestor
The "BookSuggestor" is a recommendation system that allows the user to obtain recommendations on books to read, based on a set of keywords supplied as input to the system. 
Another objective of the project is to compare the functioning of the system using two different types of text representation: "**Bag of Words**" and "**Word Embeddings**".
Finally, the results obtained from the two variants of the algorithm will be analyzed and compared, using the evaluation metric "**Mean Reciprocal Rank**", in order to see which is better.

This application was realized as my final project for the course of Social Media Management at University of Catania, Academic Year 2022-2023 (Teacher: Antonino Furnari).

# Approach
The problem of finding books whose plot is similar to some keywords is solved using two different kinds of representation for words:

1. ***"Bag of words"***: in the bag-of-words representation, each word is transformed into a vector where each dimension corresponds to a unique word in the vocabulary. The vector is filled with counts or binary values, indicating the presence or absence of words in a given text.
   
2. ***Words Embedding***: Word embeddings are dense vector representations of words that capture semantic relationships. Each word is mapped to a fixed-size vector where the values are learned through training on a large corpus. Words with similar meanings or contexts are closer in this vector space. 

Similarities between keywords inserted by te user and the books plot are measured, in order the best books to suggest.

# Dataset
The functioning of the system is based on the use of a special dataset, which contains various information, such as the title, the plot or the author, regarding a wide variety of books.
This dataset was obtained on [Kaggle](https://www.kaggle.com/datasets)

# Usage
In order to use the application, simply download the Notebook and run it on Jupyter Notebook.

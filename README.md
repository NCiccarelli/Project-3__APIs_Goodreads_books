# Project-3__APIs_Goodreads_books

Kaggle's Goodreads books dataset + APIs

In this Jupyter notebook, we are going to use these datasets/APIs:

    The Goodreads books dataset from Kaggle.
    The Open Library Books API
    The Open Library Covers API

This Jupyter notebook has one main goal. The goal is to show information -i.e., title, author, rating, publisher, book cover- for the 100 books with the highest average rating. To achieve this goal we follow these steps. We merge the data from Kaggle's dataset (CSV file) with data from two APIs. The CSV file comes from Kaggle's Goodreads books dataset, and the APIs that are used in this notebook are the "Open Library Books API" and the "Open Library Covers API". These datasets are merged in order to enrich the Kaggle dataset with information from the two APIs; the APIs are used to retrieve the following information:

    The publisher(s)
    The publication date
    The book cover

The Jupyter notebook comprises the following sections:

    In section 1 we create a dataframe for the Kaggle dataset. Since retrieving data from the APIs is highly time-consuming, we exclusively use the 100 books with the highest rating included in the Kaggle dataset.

    In section 2 we import data from the "Open Library Books API": We import data about the publisher of each book and we import the publication date.

    In section 3 we use the "Open Library Covers API" to retrieve and download the book covers for the 100 books.

    In section 4 we show information for each of the 100 books in this notebook. The information that we add in the notebook are the title, author, rating, publisher, publication date, book cover for each of the 100 books.

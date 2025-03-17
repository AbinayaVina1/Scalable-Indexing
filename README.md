# Scalable Indexing and Search with Whoosh

This project demonstrates a scalable approach to indexing and searching text documents using the Whoosh library. The code includes custom preprocessing, stemming, stopword removal, term frequency calculation, and ensures unique search results.

## Features

- **Preprocessing**: Converts text to lowercase, tokenizes, removes stopwords, and applies a simple stemmer.
- **Custom Stopwords**: Uses a predefined set of stopwords for text cleaning.
- **Term Frequency (TF)**: Calculates and stores term frequency for each document.
- **Indexing**: Efficiently indexes all `.txt` files in a specified directory.
- **Unique Search Results**: Ensures each document appears only once in search results.
- **Query Term Frequency**: Displays the frequency of query terms in search results.

## Requirements

- Python 3.7 or later
- [Whoosh](https://pypi.org/project/Whoosh/)

## Installation

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_directory>

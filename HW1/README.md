# Homework #1

This repository contains several projects demonstrating basic text mining techniques on Persian text using the Hazm, Parsivar, and DadmaTools libraries.

## Overview

### 1. Persian Text Mining with Hazm
This project uses the Hazm library to perform text mining on Persian news articles.

- **Steps:**
  - **Data Acquisition:** Downloads a dataset of Persian news articles from a GitHub repository and extracts it.
  - **Data Reading:** Reads the JSON-formatted news data.
  - **Hazm Processing:**
    - Normalizes the text using Hazm's `Normalizer`.
    - Tokenizes the text into words and sentences.
    - Stems the words using Hazm's `Stemmer`.
  - **Output:** Prints the original text, normalized text, tokenized words, and stemmed words.

- **Functions**
  - normalizer.normalize(text)
  - word_tokenize(text)
  - sent_tokenize(text)
  - stemmer.stem(text)

### 2. Persian Text Mining with Parsivar
This project demonstrates text mining techniques using the Parsivar library.

- **Steps:**
  - **Data Acquisition:** Downloads a Persian news dataset from a GitHub repository.
  - **Data Preprocessing:** Cleans and normalizes the text using Parsivar's Normalizer.
  - **Tokenization:** Splits the text into words and sentences.
  - **Stemming:** Reduces words to their root form using Parsivar's FindStems.
  
- **Functions**
  - parsivar_normalize(text)
  - parsivar_tokenize(text)
  - parsivar_stem(words)
  - parsivar_process_news(news)


### 3. Persian Text Processing with DadmaTools
This project uses the DadmaTools library for processing Persian text.

- **Steps:**
  - **Data Acquisition:** Downloads a Persian news dataset and extracts it.
  - **Processing Techniques:** Applies normalization, tokenization, and stemming using DadmaTools.

- **Functions**
  - dadma_normalize(text)
  - dadma_tokenize(text)
  - dadma_stem(text)
  - dadma_process_news(news)

  
## Requirements
- Python 3.x
- Install the required libraries:
```bash
  pip install hazm parsivar dadmatools unrar
```

## Usage
1. Clone this repository.
2. **Download and extract the dataset**: The code automatically clones the dataset repository and extracts the required files.
3. **Run the code**: Execute the Jupyter Notebook cells to process the news data. The output will show the normalized, tokenized, and stemmed versions of the articles.

## Notes
- Each project processes a single news article for demonstration purposes. You can modify the code to process the entire dataset.
- Refer to the documentation of each library for more details on available functions and their parameters.

### README for Homework #1

# Persian Text Mining with Hazm, Parsivar, and DadmaTools

## Overview
This repository demonstrates basic **text mining** techniques on Persian text using the **Hazm**, **Parsivar**, and **DadmaTools** libraries and covers the following text-mining tasks on Persian news articles using three different libraries: Hazm, Parsivar, and DadmaTools.

## Functionality

### 1. Persian Text Mining with Hazm
- **Data Acquisition**: Downloads a dataset of Persian news articles.
- **Data Preprocessing**:
  - **Normalization**: Normalizes the text using Hazm's `Normalizer`.
  - **Tokenization**: Tokenizes the text into words and sentences.
  - **Stemming**: Stems the words using Hazm's `Stemmer`.
- **Output**: Displays the original text, normalized text, tokenized words, and stemmed words.

### 2. Persian Text Mining with Parsivar
- **Data Acquisition**: Downloads a Persian news dataset.
- **Data Preprocessing**:
  - **Normalization**: Cleans and normalizes the text using Parsivar's `Normalizer`.
  - **Tokenization**: Tokenizes the text into words and sentences.
  - **Stemming**: Stems the words using Parsivar's `FindStems`.
- **Output**: Displays the original text, normalized text, tokenized words, and stemmed words.

### 3. Persian Text Processing with DadmaTools
- **Data Acquisition**: Downloads and extracts a Persian news dataset.
- **Data Preprocessing**:
  - **Normalization**: Normalizes the text using DadmaTools.
  - **Tokenization**: Tokenizes and stems the text using DadmaTools.
- **Output**: Displays the original text, normalized text, tokenized words, and stemmed words.

## Libraries Used
- **Hazm**: For Persian text normalization, tokenization, and stemming.
- **Parsivar**: For text normalization, tokenization, and stemming.
- **DadmaTools**: For Persian text processing.

## Requirements
- **Python 3.x**
- Install the required libraries:
    ```bash
    pip install hazm parsivar dadmatools unrar
    ```

## Usage
1. Clone the repository:
    ```bash
    git clone https://github.com/bitua79/information_retrieval_assignment.git
    ```
2. Download and extract the dataset using the provided code.
3. Run the Jupyter Notebooks to process the news data with each library.

## Notes
- The project processes a single news article for demonstration purposes. You can modify the code to process the entire dataset.
- Each library has additional functionalities you can explore in their documentation.

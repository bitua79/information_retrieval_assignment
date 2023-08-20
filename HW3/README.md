### README for Homework #3

# Information Retrieval Models on Persian text

## Overview
This assignment demonstrates **text indexing** on a dataset of Persian news articles using **Hazm** for preprocessing. The primary goal is to preprocess the dataset, construct a **posting list**, and analyze token frequencies to facilitate further text mining tasks. The input for this assignment is the news articles dataset extracted from Farsnews Agency.

## Functionality
- ### Part 1: Posting List Construction
  In this part, a **posting list** (inverted index) is constructed where each term points to a list of documents it appears in, along with the frequency of the term in each document. The posting list helps in the quick retrieval of documents based on token queries.

  - ### Output:
    A posting list is created as a dictionary where keys represent *tokens* and *values* are lists of tuples with document IDs and token frequencies.

  The posting list is saved as a text file (`output_all.txt`) for further use in text mining tasks.

- ### Part 2: Data Visualization and Statistical Analysis
  This part includes visualizing token frequencies across documents and analyzing various statistical properties of the dataset, such as mean and standard deviation of token frequencies.

  - ### Output:
    Scatter plots and statistical data, such as **mean** and **standard deviation**, are computed for token frequencies across documents. These results are displayed in the Colab notebook.

- ### Example Visualizations:
  - **Token Frequency Scatter Plot**: Visualizes the frequency of tokens across documents.
  - **Document Frequency Scatter Plot**: Shows the distribution of token occurrences across the entire dataset.

## Libraries Used
- **Hazm**: For Persian text normalization, tokenization, and stemming.
- **Matplotlib**: For visualizing token frequencies.
- **NumPy**: For performing statistical calculations.

## Requirements
- **Python 3.x**
- Install the required libraries:
    ```bash
    pip install hazm unrar matplotlib numpy
    ```

## Usage
1. Clone the repository:
    ```bash
    git clone https://github.com/bitua79/information_retrieval_assignment.git
    ```
2. Download and extract the dataset using the provided code.
3. Run the Colab notebook to preprocess the dataset, generate the posting list, and visualize the token frequencies.

## Notes
- This project processes a subset of news articles for demonstration, but the code can be extended to handle the full dataset.
- The final posting list and frequency data are saved as `output_all.txt` for further analysis.





### README for Homework #2

## Text Indexing with Hazm in Persian News Articles

This repository demonstrates text indexing and preprocessing techniques on Persian news articles using the **Hazm** library for Persian NLP.

## Overview

This project covers the following tasks for indexing and analyzing a Persian news dataset.

## Functionality

### 1. Data Extraction
- **Data Acquisition**: Downloads the Persian news dataset from a GitHub repository. The dataset is extracted from `.rar` files containing articles from the Fars News Agency.

### 2. Data Preprocessing with Hazm
- **Normalization**: The text is cleaned and normalized using Hazm's `Normalizer`, removing unnecessary characters like newlines and standardizing the text.
- **Tokenization**: The text is split into words and sentences.
- **Stemming**: Words are reduced to their root forms using Hazm's `Stemmer`.

### 3. Posting List Construction
- A **posting list** is created, storing the tokens' frequency across the corpus and recording which documents contain each token.

### 4. Data Visualization
- Scatter plots visualize token frequencies across documents.
- Various statistical measures such as **mean** and **standard deviation** are computed for token frequencies.

### 5. Statistical Analysis
- An ordered list of token frequencies is generated, allowing insights into the most frequent tokens and how often they appear across the dataset.

### 6. Handling the Full Dataset
- After cleaning inconsistencies such as missing or invalid data, the complete dataset is processed.
- The full posting list is constructed, followed by the same statistical and visualization steps.

### 7. Output
- The final posting list is saved to a text file for further analysis or use in future text mining tasks.

## Libraries Used
- **Hazm**: For Persian text normalization, tokenization, and stemming.
- **Matplotlib**: For data visualization through scatter plots.
- **NumPy**: For numerical analysis and statistical calculations.

## Requirements
- **Python 3.x**
- Install the required libraries:
    ```bash
    pip install hazm unrar matplotlib numpy
    ```

## Usage
1. Clone the repository:
    ```bash
    git clone https://github.com/bitua79/information_retrieval_assignment.git
    ```
2. Download and extract the dataset using the provided code.
3. Run the Colab Notebook to preprocess the text, generate the posting list, and visualize the token frequencies.

## Notes
- The posting list and frequency data are saved as `output_all.txt` for future reference.
- The project uses a subset of the dataset (1000 news articles) for demonstration purposes, but the code can be extended to handle the full dataset.
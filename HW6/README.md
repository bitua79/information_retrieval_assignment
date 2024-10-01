### README for Homework #6

# Information Retrieval System Evaluation

## Overview

This repository implements the **evaluation of information retrieval systems** using various metrics on the **CISI dataset**. The goal is to compare system performance based on the **Precision**, **Recall**, **F-Measure**, **MAP**, and **DCG** evaluation metrics.

## Functionality

### 1. Data Acquisition and Preprocessing

- **Dataset**: Downloads the CISI dataset containing documents, queries, and relevance judgements.
- **Preprocessing**:
  - **Tokenization and Normalization**: Processes the documents by tokenizing and normalizing them.
  - **Posting List Generation**: Constructs a posting list and calculates word frequencies in documents.

### 2. Query Processing and Evaluation

- **Query Application**: Applies the provided queries from the CISI dataset to the processed documents.
- **Evaluation Metrics**:
  - **Precision**: Measures the ratio of correctly retrieved documents to the total retrieved documents.
  - **Recall**: Measures the ratio of correctly retrieved documents to the total relevant documents.
  - **F-Measure**: Harmonic mean of Precision and Recall, with a customizable parameter.
  - **MAP (Mean Average Precision)**: Calculates average precision across multiple queries.
  - **DCG (Discounted Cumulative Gain)**: Evaluates the relevance of documents based on their ranks in the retrieved list.

### 3. Performance Comparison

- **Effect of Preprocessing Steps**: Evaluates the impact of removing stop words and applying different weighting schemes (e.g., TF-IDF vs. word frequency) on the system's performance.

## Libraries Used

- **Numpy**: For numerical operations.
- **Pandas**: For handling datasets and tabular data.
- **Matplotlib**: For visualizing performance metrics.

## Requirements

- **Python 3.x**
- Install the required libraries:
  ```bash
  pip install numpy pandas matplotlib
  ```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/username/IR-evaluation-homework.git
   ```
2. Download the **CISI dataset** from the following links:
   - [CISI Dataset](http://ir.dcs.gla.ac.uk/resources/test_collections/cisi)
   - [Data Description](https://www.pragmalingu.de/docs/guides/data-comparison/)
3. Run the Jupyter Notebook to evaluate the information retrieval system and compute the evaluation metrics.

## Notes

- The system evaluates retrieval performance using only the top 20 documents retrieved for each query.
- You can adjust the parameters for stop word removal and weighting schemes to observe their effects on system performance.

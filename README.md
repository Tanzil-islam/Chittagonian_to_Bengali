
# Chittagonian to Bengali Translation

This project focuses on translating Chittagonian language text into Bengali using natural language processing (NLP) techniques. The dataset used in this project consists of Chittagonian sentences paired with their Bengali translations. This project uses various libraries such as pandas, torch, and sentencepiece to preprocess the data and perform the translation tasks.

## Project Overview

The goal of this project is to build a translation model capable of converting Chittagonian text into Bengali. The project analyzes a dataset that includes a collection of Chittagonian and Bengali sentence pairs, using data preprocessing techniques such as checking for missing values, and analyzing unique values. Additionally, a basic model architecture has been built to handle the translation task.

## Features

- **Chittagonian to Bengali Translation**: A model built to translate text between Chittagonian and Bengali.
- **Data Analysis**: Includes checks for missing values, data types, unique values, and basic statistics for understanding the dataset.
- **Preprocessing**: The dataset is cleaned and filtered for meaningful translation results.
  
## Requirements

- Python 3.x
- Pandas
- PyTorch
- TensorFlow
- SentencePiece
- Google Colab (for mounting Google Drive and dataset storage)

## Dataset

The dataset used in this project consists of Chittagonian text and its Bengali translation. It has two main columns:
- **Chittagonian**: The Chittagonian sentences.
- **Bengali**: The corresponding Bengali translations.

Example:

| Chittagonian      | Bengali       |
|-------------------|---------------|
| আঁর               | আমার          |
| বাড়ি             | বারি          |
| আঁরার             | আমাদের        |
| আঁরো বারিত কনো কিয়া নো আইয়ি | আমাদের বাড়িতে কেউ আসে নাই |

## How to Use

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/chittagonian-to-bengali.git
   cd chittagonian-to-bengali
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Upload the dataset to your Google Drive (if using Google Colab) and ensure the path is correct in the notebook.

4. Run the Jupyter notebook to start analyzing the dataset and building the translation model:
   ```
   jupyter notebook ctg_to_bn.ipynb
   ```

## Dataset Analysis

The dataset consists of 1103 entries, with 941 unique Chittagonian words and 939 unique Bengali words. The top frequent words are displayed for both languages, and missing values are checked to ensure the dataset is complete.



This README file provides an overview of the project, dataset, and instructions for running the notebook. Feel free to modify and extend it as necessary.

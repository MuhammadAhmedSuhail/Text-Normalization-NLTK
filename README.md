# Text-Normalization-NLTK

## Project Description

This project implements text normalization using the Natural Language Toolkit (NLTK) library. Text normalization is the process of converting text into a canonical (standard) form. The project uses various normalization techniques such as stemming, lemmatization, and removing stop words to preprocess text data. The project also implements specific rules to normalize certain types of text such as URLs, dates, and phone numbers.
The langauge of the Text is **Roman-Urdu**.

## Approach
The text normalization process implemented in this project involves the following steps:
- **Tokenization:** The input text is first tokenized into individual words or tokens. This is done using the NLTK word_tokenize function.
- **Lowercasing:** All tokens are converted to lowercase to standardize the text and make it easier to compare.
- **Stemming:** The Porter stemmer algorithm is applied to each token to reduce it to its root form.
- **Lemmatization:** The WordNet lemmatizer is applied to each token to reduce it to its base or dictionary form.
- **Stop word removal:** A list of commonly occurring words are removed from the token list.
- **Rule-based normalization:** The rules provided in the pdf attached with the project is followed.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
You will need to have Python 3.x installed on your machine. You can download the latest version of [Python](https://www.python.org/downloads/) here.
</br>
You will also need to have Anaconda on your machine. You can download the latest version of [Anaconda](https://www.anaconda.com/) here.

### Installing
Clone this repository onto your local machine.
```
git clone https://github.com/MuhammadAhmedSuhail/Text-Normalization-NLTK.git
```
Install the required packages.
```
pip install -r requirements.txt
```
Run `Normalization.ipynb` to normalize the text using NLTK

## Author:
- Muhammad Ahmed Suhail

## Acknowledgments:
- This project was completed as an assignment for **Introduction to Data Science** at FAST - NUCES Islamabad.

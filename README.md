# Book Analysis using NLP

**Tech Stack:** Python, NLTK, Regular Expressions, Jupyter Notebook

## Description
This project performs natural language processing (NLP) tasks on a real-world book (`miracle_in_the_andes.txt`) to extract meaningful insights such as word frequency, keyword occurrences, and sentiment analysis.

## Key Features
- 📚 Counts the number of chapters using both string and regex
- 💬 Finds sentences that mention the word "love"
- 🔢 Identifies most common words in the book
- 🚫 Filters out stopwords using NLTK's `stopwords` corpus
- 😊 Performs sentiment analysis on the entire book and per chapter using `VADER`

## Techniques Used
- Regular expressions for pattern matching
- Word frequency analysis via dictionaries and list comprehensions
- Stopword filtering with NLTK
- Sentiment scoring with `SentimentIntensityAnalyzer`

## How to Run
1. Clone the repository.
2. Install dependencies:
```bash
pip install nltk

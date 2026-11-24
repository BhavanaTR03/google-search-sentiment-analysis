# Google Search Sentiment Analysis

A Python-based sentiment analysis project that extracts text from Google Search results for a user-entered keyword and classifies the text as positive, negative or neutral.

## Project Overview

This project explores how Natural Language Processing (NLP) can be used to identify sentiment in text. It uses Google Search results as the source of text and applies TextBlob to calculate sentiment polarity.

## How It Works

1. The user enters a keyword.
2. The program retrieves Google Search results.
3. BeautifulSoup extracts text from the returned HTML.
4. TextBlob calculates the sentiment polarity of the extracted text.
5. The program classifies each result as:
   - **Positive**
   - **Negative**
   - **Neutral**

## Technologies Used

- Python
- TextBlob
- BeautifulSoup
- Requests
- Natural Language Processing (NLP)

## Repository Structure

```text
google-search-sentiment-analysis/
├── ML1.py
├── image.pdf
└── README.md
```

## Example Output

The `image.pdf` file contains an example of the program's output.

## Limitations

- Uses Google Search result text rather than directly collecting social-media comments.
- Sentiment classification relies on TextBlob polarity.
- No labelled dataset or formal model evaluation was included.
- Search-result extraction may be affected by changes to Google's page structure.

## Project Background

An academic Python project completed in 2023 to explore text processing and basic sentiment analysis.


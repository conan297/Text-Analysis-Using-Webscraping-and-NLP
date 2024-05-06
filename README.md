# Web Content Analysis Tool

This project is a web content analysis tool designed to extract and analyze textual data from web pages. It performs various text processing tasks such as sentiment analysis, readability assessment, and word frequency analysis.

## Introduction

The Web Content Analysis Tool is a Python-based application that retrieves text content from web pages, processes it, and generates insights regarding the text's sentiment, complexity, and other linguistic features. It utilizes techniques from natural language processing (NLP) and text analysis to provide valuable insights into the textual content of web pages.

## Features

- **Web Scraping**: The tool scrapes textual content from web pages using the `requests` and `BeautifulSoup` libraries in Python.
  
- **Text Processing**: It preprocesses the extracted text by removing special characters, punctuation, and stopwords using the `nltk` library.

- **Sentiment Analysis**: The tool calculates sentiment scores based on the presence of positive and negative words in the text. It uses a master dictionary of positive and negative words to determine sentiment polarity.

- **Readability Assessment**: It assesses the readability of the text by calculating metrics such as average sentence length, percentage of complex words, and FOG index.

- **Word Frequency Analysis**: The tool analyzes word frequency and calculates metrics such as average word length and syllables per word.

## Usage

1. **Input Data**: Provide a list of URLs and corresponding URL IDs in an Excel file named `Input.xlsx`.
   
2. **Run the Script**: Execute the Python script `web_content_analysis.py` to scrape web content, process text, and generate analysis results.
   
3. **Output Data**: The analysis results are stored in an Excel file named `Output.xlsx`, containing various metrics for each URL ID.

## Setup

1. **Dependencies**: Install the required Python libraries using `pip install -r requirements.txt`.

2. **Input Data**: Ensure that the input Excel file `Input.xlsx` is correctly formatted with columns for URLs and URL IDs.

3. **Execution**: Run the Python script `web_content_analysis.py` to perform web scraping and text analysis.

## Results

The analysis results provide insights into the sentiment, readability, and linguistic characteristics of the text content extracted from web pages. These insights can be valuable for content analysis, SEO optimization, and linguistic research.

## Conclusion

The Web Content Analysis Tool offers a convenient way to extract, process, and analyze textual content from web pages, enabling users to gain valuable insights and make informed decisions based on the analyzed data.

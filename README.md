# Assignment2_CSIS4260
# CSIS 4260 Assignment 2

## Student Name
Amish Nanda
ID-300408947

## Project Topic
Artificial Intelligence and Education

## Project Description
This project uses web scraping and text analysis to collect content from 50 public webpages and generate a summary and importance score for each page.

## Libraries Used
- requests
- beautifulsoup4
- pandas
- nltk
- textblob
- openpyxl
- lxml

## Why BeautifulSoup Was Chosen
BeautifulSoup was selected because it is beginner-friendly, lightweight, and works well with static public webpages like Wikipedia. It is easier to understand and implement than more advanced tools such as Playwright.

## Text Analysis Methods
1. Extractive summarization using word-frequency scoring
2. Importance scoring using sentiment polarity and topic keyword relevance

## Files Included
- assignment2.ipynb
- articles_output.csv
- articles_output.xlsx
- README.md
- requirements.txt

## How to Run

### 1. Create a virtual environment
```bash
python -m venv venv

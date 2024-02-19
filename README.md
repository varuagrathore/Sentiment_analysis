Sentiment Analysis

This repository contains Python scripts for scraping 100 websites and performing sentiment analysis on the extracted data.

Objective

The objective of this project is to scrape textual data from 100 websites and analyze the sentiment of the extracted content.

Files

- `Data_Extraction.ipynb`: Jupyter Notebook containing code for scraping data from websites.
- `Data_analysis.ipynb`: Jupyter Notebook containing code for sentiment analysis.
- `Input.xlsx`: Input file containing URLs of the websites to be scraped.
- `Stop_words.txt`: File containing stop words for text processing.
- `negative-words.txt`: File containing a list of negative words for sentiment analysis.
- `positive-words.txt`: File containing a list of positive words for sentiment analysis.
- `output.xlsx`: Output file containing the results of sentiment analysis.
- `instruction.rtf`: Instructions for the project.

Code

The code is divided into two parts:

1. Data Extraction:
   - `Data_Extraction.ipynb` contains the code for scraping textual data from 100 websites.
   - The script uses Python libraries such as BeautifulSoup for web scraping.

2. Sentiment Analysis:
   - `Data_analysis.ipynb` contains the code for performing sentiment analysis on the extracted data.
   - The sentiment analysis is done using predefined lists of positive and negative words.
   - The output is saved in `output.xlsx` file.

Usage

1. Clone the repository:

```
git clone https://github.com/varuagrathore/Sentiment_analysis.git
```

2. Install the required libraries:

```
pip install beautifulsoup4 pandas
```

3. Open and run the Jupyter Notebooks `Data_Extraction.ipynb` and `Data_analysis.ipynb` in your local environment.

Results

The sentiment analysis results are stored in the `output.xlsx` file.


//if there is any issue with code so plese let me know 


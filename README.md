# GDP Web Scraping Analysis

## Overview

This project extracts GDP data from a web page using Python web scraping techniques and performs data cleaning and analysis.

The goal of this project is to collect GDP information, transform the raw data into an analysis-ready format, and identify the world's largest economies by GDP.

## Technologies Used

- Python
- Requests
- BeautifulSoup
- Pandas
- Jupyter Notebook

## Project Workflow

1. Send an HTTP request to the target webpage using Requests.
2. Extract HTML content from the response.
3. Parse the HTML structure using BeautifulSoup.
4. Locate and extract GDP table data.
5. Convert extracted data into a Pandas DataFrame.
6. Clean and transform the dataset.
7. Convert GDP values from Million USD to Billion USD.
8. Sort countries by GDP and analyze the top economies.

## Data Processing

The project includes:

- Web scraping
- HTML parsing
- Data extraction
- Data cleaning
- Missing value handling
- Data type conversion
- Data sorting

## Results

The analysis identifies the countries with the highest GDP values.

Top economies include:

- United States
- China
- Japan
- Germany
- India

## Files

- `GDP_Web_Scraping_Analysis.ipynb`  
  Jupyter Notebook containing the complete analysis workflow.

- `GDP_analysis.csv`  
  Cleaned GDP dataset generated from the analysis.

## Conclusion

This project demonstrates a complete data analysis workflow starting from web data extraction and ending with a structured dataset ready for analysis.
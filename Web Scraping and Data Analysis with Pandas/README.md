# Project  Description: Web Scraping and Data Analysis with Pandas

[**Link to collab Notebook on GitHub**](https://github.com/ShomritaSingha/Data-Analyst-Portfolio-Projects/blob/main/Python%20projects/Data_scrapping_%26pandas_project.ipynb)

## Overview

Welcome to my GitHub repository showcasing a data analysis project focusing on web scraping and data manipulation using Python. In this project, I aimed to extract and analyze information about the largest companies in the United States by revenue, utilizing web scraping techniques with BeautifulSoup and data manipulation capabilities of Pandas.

## Code Highlights

## Libraries Used

The following Python libraries were instrumental in the successful execution of this project:

- **BeautifulSoup:** 

- **Requests:** 

- **Pandas:**

- **Matplotlib:**

## Code Highlights

### 1. Web Scraping

The project begins with the essential steps of web scraping:

- **Tool Import:** Importing the necessary tools, namely BeautifulSoup and requests.

- **URL Definition:** Defining the URL for the Wikipedia page listing top U.S. companies by revenue.

- **HTML Retrieval:** Fetching the HTML content of the page using the requests library.

- **HTML Parsing:** Utilizing BeautifulSoup to parse the HTML content.

- **Data Inspection:** Checking the HTML structure to ensure successful data retrieval.

- **Table Extraction:** Locating and extracting the relevant table containing the company data.

### 2. Data Cleaning and Structuring

Once the data is scraped, the focus shifts to cleaning and structuring:

- **Header and Row Extraction:** Extracting table headers and rows from the HTML structure.

- **Pandas DataFrame Creation:** Creating a Pandas DataFrame with columns named after the table headers.

- **Data Population:** Looping through the table rows, cleaning the data, and populating the DataFrame.

### 1. Web Scraping

The project begins with the essential steps of web scraping:

- **Tool Import:** Importing the necessary tools, namely BeautifulSoup and requests.

- **URL Definition:** Defining the URL for the Wikipedia page listing top U.S. companies by revenue.

- **HTML Retrieval:** Fetching the HTML content of the page using the requests library.

- **HTML Parsing:** Utilizing BeautifulSoup to parse the HTML content.

- **Data Inspection:** Checking the HTML structure to ensure successful data retrieval.

- **Table Extraction:** Locating and extracting the relevant table containing the company data.

### 2. Data Cleaning and Structuring

Once the data is scraped, the focus shifts to cleaning and structuring:

- **Header and Row Extraction:** Extracting table headers and rows from the HTML structure.

- **Pandas DataFrame Creation:** Creating a Pandas DataFrame with columns named after the table headers.

- **Data Population:** Looping through the table rows, cleaning the data, and populating the DataFrame.

### 3. Data Export

The cleaned and structured data is then exported to a CSV file named 'usa_top.csv' for external use.

### 4. Data Visualization

The project incorporates data visualization using Matplotlib:

- **Revenue Comparison:** Generating a bar chart to visually compare the revenue of companies in different industries.

 ## **Dashboard**

![Alt text of the image](https://github.com/ShomritaSingha/Data-Analyst-Portfolio-Projects/blob/main/Python%20projects/Industry%20ranking%20Usa%20Top%20Data%20scappring%20project.png)


### 5. Data Quality Check

Conducting a check for any missing values in the DataFrame ensures the reliability of the dataset.

## Key Performance Indicators (KPIs)

1. **Data Extraction and Cleaning:**
   - Successful extraction of relevant data from the Wikipedia page.
   - Effective cleaning and structuring of the data for analysis.

2. **Data Export:**
   - Successful export of the cleaned data to a CSV file.

3. **Data Visualization:**
   - Creation of an informative bar chart illustrating revenue distribution among different industries.

4. **Data Quality Check:**
   - Verification of no missing values in the final DataFrame.

## Conclusions

This project showcases my proficiency in web scraping and data analysis using Python. The resulting 'usa_top.csv' file serves as a valuable dataset for further exploration, and the visualizations provide quick insights into the revenue distribution among top U.S. companies. Feel free to explore the code, adapt it to your needs, and provide any feedback or contributions. I hope you find this project informative and valuable for your data analysis endeavors!



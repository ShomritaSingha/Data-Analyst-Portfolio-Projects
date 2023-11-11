# Project Description: Customer Call List Data Cleaning

## **Project Objective**

This project focuses on the systematic cleaning of a customer call list dataset extracted from an Excel file ('Customer Call List.xlsx') using Python and the Pandas library. The main objective is to enhance data quality, address anomalies, and prepare the dataset for subsequent analysis.

## **Dataset used**
- <a href="https://github.com/ShomritaSingha/Data-Analyst-Portfolio-Projects/blob/main/Python%20projects/Customer%20Call%20List.xlsx">call center data</a>
Please download the .xlsx to veiw the data

# Libraries Used

The data cleaning and structuring process leverages the following Python libraries:

- **Pandas:** A powerful data manipulation library, essential for handling and transforming tabular data.

- **NumPy:** Used for efficient numerical operations, providing the foundation for various data manipulations.

## **Process**

###1. Data Import

The project starts by importing data from the Excel file into a Pandas DataFrame:
**import pandas as pd**
**df = pd.read_excel('Customer Call List.xlsx')**

### 2. Data Cleaning and Structuring

# Data Cleaning and Structuring

## Overview

The data cleaning and structuring phase of this project focuses on refining the integrity and organization of the customer call list dataset. Employing Python and the Pandas library, this phase aims to enhance the dataset's quality, resolve anomalies, and create a structured format conducive to efficient analysis.

This was the Data in the begining :
![Alt text of the image](https://github.com/ShomritaSingha/Data-Analyst-Portfolio-Projects/blob/main/Python%20projects/Scrapped%20from%20call%20center%20csv%20data%20uncleaned.png)


## Key Steps

### a. Duplicate Removal

Duplicate entries within the dataset are identified and systematically removed, ensuring the elimination of redundant information.

### b. Column Selection

Selective removal of unnecessary columns is performed, streamlining the dataset to include only relevant information for subsequent analysis.

### c. Anomaly Handling in 'Last_Name'

The 'Last_Name' column undergoes a meticulous cleaning process to strip away specified anomalies, ensuring uniformity and consistency in the data.

### d. Phone Number Formatting

The formatting of phone numbers is standardized for clarity and ease of interpretation. This involves removing non-alphanumeric characters, converting numbers to strings, and applying a structured format.

**Further structuring of the Data it looks like**

![Alt text of the image](https://github.com/ShomritaSingha/Data-Analyst-Portfolio-Projects/blob/main/Python%20projects/before%20formating%20the%20cells%20and%20handling%20the%20null%20exceptions.png)

### e. Standardizing Values

Values within specific columns, such as 'Paying Customer' and 'Do_Not_Contact,' are standardized to maintain consistency and coherence across the dataset.

### f. Handling 'N/a' and NaN Values

Occurrences of 'N/a' are systematically replaced with an empty string, and any remaining NaN values are filled to mitigate data gaps and ensure a comprehensive dataset.

### g. Row Removal Based on Conditions

Rows flagged for 'Do_Not_Contact' are purposefully excluded to comply with contact preferences. Additionally, rows lacking essential contact information, such as phone numbers, are systematically removed.

### h. Index Reset

The final step involves resetting the index for the dataset, providing a clean and organized structure ready for further exploration and analysis.



## **Final Cleaned Data**

![Alt text of the image](https://github.com/ShomritaSingha/Data-Analyst-Portfolio-Projects/blob/main/Python%20projects/Cleaned%20call%20center%20data.png)



## **Final Conclusion:**

This data cleaning and structuring phase is pivotal in transforming raw data into a refined and organized format. By addressing duplicates, anomalies, and standardizing values, the dataset is primed for meaningful analysis, allowing for insights and applications that leverage a high-quality and well-structured foundation. The adaptable code welcomes customization based on specific project requirements.

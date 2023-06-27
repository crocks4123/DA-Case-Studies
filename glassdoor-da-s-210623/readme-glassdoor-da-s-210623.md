# Data Science Job Postings - Data Cleaning and Insights

This repository contains a cleaned dataset and insights derived from the original dataset obtained from Kaggle: [Data Science Job Posting on Glassdoor](https://www.kaggle.com/datasets/rashikrahmanpritom/data-science-job-posting-on-glassdoor?select=Uncleaned_DS_jobs.csv).

## Dataset Description

The original dataset, named `Uncleaned_DS_jobs.csv`, consists of job postings related to data science scraped from Glassdoor. It includes various attributes such as job title, company name, location, job description, salary information, and more.

## Data Cleaning

To prepare the dataset for analysis, the following cleaning steps were performed:

1. **Handling Missing Values:** The dataset contained missing values in some columns. Missing numerical values were imputed with appropriate measures such as mean or median, while missing categorical values were filled with the most frequent category.

2. **Standardizing Data Types:** Some columns had incorrect data types. The necessary columns were converted to their appropriate data types, such as converting salary values to numerical format.

3. **Removing Duplicate Entries:** Duplicate job postings were identified and removed to ensure data integrity.

4. **Text Preprocessing:** The text-based columns, such as job titles, company names, and job descriptions, underwent text preprocessing steps. These included converting text to lowercase, removing special characters, punctuation, and stopwords, and lemmatizing the words.

5. **Feature Engineering:** Additional features were derived from existing columns to provide more meaningful insights. For example, extracting the job seniority level from the job title or categorizing job locations into regions.

The cleaned dataset is stored in the file named `Cleaned_DS_jobs.csv` and is ready for further analysis.

## Insights and Guiding Questions

Upon analyzing the cleaned dataset, several insights were discovered. These insights can guide further exploration and research into the field of data science jobs. 

## Usage

You can clone this repository to access the cleaned dataset (`Cleaned_DS_jobs.csv`) and the Jupyter Notebook (`data_analysis.ipynb`) containing the code for data cleaning and analysis.

Feel free to use this dataset and the insights provided here for educational, research, or exploratory purposes. However, please refer to the original dataset source on Kaggle ([Data Science Job Posting on Glassdoor](https://www.kaggle.com/datasets/rashikrahmanpritom/data-science-job-posting-on-glassdoor?select=Uncleaned_DS_jobs.csv)) for any commercial or business usage.

## Conclusion

The cleaned dataset

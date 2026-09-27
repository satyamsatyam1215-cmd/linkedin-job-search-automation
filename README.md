# LinkedIn Job Search Automation & Job Market Analysis

A Python-based data analytics project that automates job data collection, cleans and transforms the collected data, and analyzes the Junior Data Analyst job market through Python-based visualization.

## Overview

This project was developed as an end-to-end data workflow covering:

* Job data collection
* Data extraction
* Data cleaning
* Data transformation
* Exploratory data analysis
* Data visualization
* Job market reporting

The project uses configurable search parameters such as job title, location, posting period, and number of jobs.

## Project Workflow

```text
Search Criteria
       |
       v
Job Data Collection
       |
       v
Job Detail Extraction
       |
       v
Data Cleaning
       |
       v
Data Transformation
       |
       v
Exploratory Data Analysis
       |
       v
Data Visualization
       |
       v
Job Market Analysis
       |
       v
Final Report
```

## Key Features

### Job Data Collection

* Search jobs by job title
* Search jobs by location
* Filter recently posted jobs
* Configure the number of jobs to collect
* Extract job descriptions when available
* Collect company information
* Collect job location
* Capture posting information
* Capture applicant information when available
* Remove duplicate job listings

### Data Cleaning and Transformation

* Clean text fields
* Handle missing values
* Remove duplicate records
* Process posting dates and times
* Convert timestamps to IST
* Calculate days since posting
* Prepare structured data for analysis

### Job Market Analysis

* Analyze Junior Data Analyst job listings
* Explore job posting patterns
* Create charts and visualizations
* Generate a PDF-based analysis report

## Technology Stack

| Technology        | Purpose                                  |
| ----------------- | ---------------------------------------- |
| Python            | Data collection, processing and analysis |
| Selenium          | Browser automation                       |
| BeautifulSoup     | HTML parsing and data extraction         |
| Pandas            | Data cleaning and transformation         |
| NumPy             | Data processing                          |
| Matplotlib        | Data visualization                       |
| Seaborn           | Statistical visualization                |
| LXML              | HTML parsing                             |
| WebDriver Manager | Browser driver management                |
| Jupyter Notebook  | Development and analysis                 |

## Project Structure

```text
linkedin-job-search-automation/
|
+-- NoteBook/
|   +-- linkedin_job_scraper.ipynb
|   +-- linkedin_data_cleaning.ipynb
|   +-- Data visulation .ipynb
|
+-- Sample data Clean-Raw/
|   +-- linkedin_jobs_cleaned.csv
|   +-- linkedin_junior_data_analyst_jobs.csv
|
+-- Result/
|   +-- Junior_Data_Analyst_Job_Market_Analysis_charts.pdf
|
+-- README.md
```

## Notebooks

### 1. LinkedIn Job Scraper

File:

`NoteBook/linkedin_job_scraper.ipynb`

This notebook handles the job-search and data-collection process.

Example configuration:

```python
job_title = "junior data analyst"
location = "Mumbai"
posted_within = "r604800"
workplace_type = ""
number_of_jobs = 100
get_job_description = True
```

### 2. Data Cleaning

File:

`NoteBook/linkedin_data_cleaning.ipynb`

This notebook prepares the collected job data for analysis.

The cleaning workflow includes:

* Text cleaning
* Data standardization
* Duplicate removal
* Date and time processing
* Missing-value handling
* Dataset preparation

### 3. Data Visualization

File:

`NoteBook/Data visulation .ipynb`

This notebook uses the cleaned dataset to create visualizations and analyze the Junior Data Analyst job market.

## Dataset

The project contains raw and cleaned job datasets.

Important fields include:

| Column              | Description                          |
| ------------------- | ------------------------------------ |
| `title`             | Job title                            |
| `company`           | Company name                         |
| `location`          | Job location                         |
| `posted_date_ist`   | Posting date in IST                  |
| `posted_time_ist`   | Posting time in IST                  |
| `days_since_posted` | Number of days since posting         |
| `posted_text`       | Original posting information         |
| `applicants`        | Applicant information when available |
| `jd`                | Job description                      |
| `link`              | Job listing URL                      |

## Analysis Report

The repository includes a PDF report containing visual analysis of the Junior Data Analyst job dataset.

Report:

`Result/Junior_Data_Analyst_Job_Market_Analysis_charts.pdf`

You can open the PDF directly from the `Result` folder in the repository.

## Skills Demonstrated

This project demonstrates practical experience with:

* Python
* Selenium
* BeautifulSoup
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Data extraction
* Data cleaning
* Data transformation
* Exploratory Data Analysis
* Data visualization
* Jupyter Notebook
* Analytical reporting

## Future Improvements

* Extract skills from job descriptions
* Classify experience requirements
* Categorize job roles
* Analyze skill demand
* Analyze salary information where publicly available
* Build an interactive Power BI dashboard
* Automate reporting
* Develop job matching based on required skills

## Disclaimer

This project is intended for educational and research purposes. Users should comply with LinkedIn's applicable Terms of Service, access restrictions, and usage policies when using automation tools.

## Author

**Satyam Singh**

Data Analyst | Python | SQL | Power BI | Excel

GitHub: https://github.com/satyamsatyam1215-cmd

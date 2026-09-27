# LinkedIn Job Search Automation & Job Market Analysis

A Python-based data analytics project that automates LinkedIn job data collection, cleans and transforms the collected data, and performs visual analysis of the Junior Data Analyst job market.

The project was developed as an end-to-end workflow covering **data collection, data cleaning, transformation, exploratory analysis, visualization, and reporting**.

---

## Project Overview

This project was built to streamline repetitive job-search data collection and convert job listings into a structured dataset that can be analyzed.

The workflow starts with configurable search criteria such as job title, location, posting period, and number of jobs. The collected records are then cleaned and transformed before being used for job-market analysis and visualization.

## Workflow

```text
Search Criteria
      ↓
LinkedIn Job Listings
      ↓
Job Data Collection
      ↓
Job Detail Extraction
      ↓
Data Cleaning
      ↓
Data Transformation
      ↓
Exploratory Data Analysis
      ↓
Data Visualization
      ↓
Job Market Analysis
      ↓
Final Report
```

---

## Key Features

### Job Data Collection

* Search jobs by job title
* Search jobs by location
* Filter recently posted jobs
* Configure the number of jobs to collect
* Extract job descriptions when available
* Capture company and location information
* Capture posting information
* Capture applicant information when available
* Remove duplicate job listings

### Data Cleaning & Transformation

* Standardize text fields
* Clean and prepare collected records
* Handle missing posting dates
* Convert posting timestamps to IST
* Calculate days since posting
* Sort records by posting date
* Prepare structured datasets for analysis

### Job Market Analysis

* Analyze Junior Data Analyst job listings
* Explore job-posting patterns
* Create visualizations using Python
* Generate a PDF-based analysis report

---

## Technology Stack

| Technology            | Purpose                              |
| --------------------- | ------------------------------------ |
| **Python**            | Core programming and data processing |
| **Selenium**          | Browser automation                   |
| **BeautifulSoup**     | HTML parsing and data extraction     |
| **Pandas**            | Data cleaning and transformation     |
| **NumPy**             | Numerical and data processing        |
| **Matplotlib**        | Data visualization                   |
| **Seaborn**           | Statistical visualization            |
| **LXML**              | HTML parsing                         |
| **WebDriver Manager** | Browser driver management            |
| **Jupyter Notebook**  | Development and analysis             |

---

## Repository Structure

```text
linkedin-job-search-automation/
│
├── NoteBook/
│   ├── linkedin_job_scraper.ipynb
│   ├── linkedin_data_cleaning.ipynb
│   └── Data visulation .ipynb
│
├── Sample data Clean-Raw/
│   ├── linkedin_jobs_cleaned.csv
│   └── linkedin_junior_data_analyst_jobs.csv
│
├── Result/
│   └── Junior_Data_Analyst_Job_Market_Analysis_charts.pdf
│
└── README.md
```

---

## Notebooks

### 1. Job Scraper

**`linkedin_job_scraper.ipynb`**

This notebook handles the job-search and data-collection process.

Search parameters can be customized according to the required analysis.

Example:

```python
job_title = "junior data analyst"
location = "Mumbai"
posted_within = "r604800"
workplace_type = ""
number_of_jobs = 100
get_job_description = True
```

### 2. Data Cleaning

**`linkedin_data_cleaning.ipynb`**

This notebook processes the collected job data and prepares it for analysis.

The workflow includes:

* Text cleaning
* Data standardization
* Duplicate handling
* Date and time processing
* Missing-value handling
* Dataset preparation

### 3. Data Visualization

**`Data visulation .ipynb`**

This notebook uses the prepared dataset to create visualizations and explore patterns within the Junior Data Analyst job market.

---

## Dataset

The processed dataset contains information such as:

| Column              | Description                          |
| ------------------- | ------------------------------------ |
| `title`             | Job title                            |
| `company`           | Company name                         |
| `location`          | Job location                         |
| `posted_date_ist`   | Posting date in IST                  |
| `posted_time_ist`   | Posting time in IST                  |
| `days_since_posted` | Number of days since posting         |
| `posted_text`       | Original posting-time text           |
| `applicants`        | Applicant information when available |
| `jd`                | Job description                      |
| `link`              | Job listing URL                      |

---

## Results

The repository includes a PDF report containing the visual analysis of the Junior Data Analyst job dataset.

### Analysis Report

[View Junior Data Analyst Job Market Analysis](Result/Junior_Data_Analyst_Job_Market_Analysis_charts.pdf)

---

## Skills Demonstrated

This project demonstrates practical experience with:

* Python
* Web automation
* Web data extraction
* Data cleaning
* Data transformation
* Exploratory Data Analysis
* Data visualization
* Pandas
* Selenium
* BeautifulSoup
* Matplotlib
* Seaborn
* Jupyter Notebook
* Analytical reporting

---

## Future Improvements

* Automated skill extraction from job descriptions
* Experience-level classification
* Job-role categorization
* Skill-demand analysis
* Salary analysis where publicly available
* Power BI dashboard integration
* Automated job reporting
* Job matching based on required skills

---

## Disclaimer

This project is intended for educational and research purposes. Users should comply with LinkedIn's applicable Terms of Service, access restrictions, and usage policies when using automation tools.

---

## Author

**Satyam Singh**

**Data Analyst | Python | SQL | Power BI | Excel**

GitHub: [satyamsatyam1215-cmd](https://github.com/satyamsatyam1215-cmd)

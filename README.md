# final-project-qtm350
DATASCI 350 - Final Project: Group 4

## Project Overview

This project analyzes Population dynamics data for selected Asian countries. The projectamid to clean, process, and explore the dataset to identify mortality and fertility patterns and trends across Asian countries.

The workflow includes data cleaning, sql data analysis, data analysis with visualizations and Quarto report.

---

## Repository Structure

* **data/**
  Contains the cleaned dataset used in the analysis.

* **documentation/**
  Includes the codebook and the entity-relationship (ER) diagram describing the dataset.

* **figures/**
  Contains plots and tables generated during the analysis.

* **scripts/**
  Includes Python and SQL scripts used for data cleaning and analysis.


---

## Quarto Report

The final report is provided in both PDF and HTML formats.  The HTML version is rendered to ensure all figures display correctly.

---

## How to Run the Project

### Step 1: Data Cleaning

Run the data cleaning script:

```bash
scripts/data_cleaning.py
```

This script retrieves raw data, cleans and preprocesses it, and saves the cleaned dataset in the local folder.

---

### Step 2: Data Analysis

Run the analysis script:

```bash
scripts/SQL_Script.ipynb
scripts/Making_graphs.ipynb
```

This script performs exploratory data analysis through sql, and generates plots and tables by python.

---

## Outputs

* Cleaned dataset stored in the data folder
* Visualizations stored in the figures folder
* Documentation stored in the documentation folder

---

## Notes

* Missing values are handled during preprocessing
* The dataset focuses on selected Asian countries

## Data Sources

Life Expectancy:  
https://data.worldbank.org/indicator/SP.DYN.LE00.IN  

Under-5 Mortality:  
https://data.worldbank.org/indicator/SH.DYN.MORT  

Adolescent Fertility:  
https://data.worldbank.org/indicator/SP.ADO.TFRT  

## Published Links

GitHub Repository: https://github.com/karMa083-x/final-project-qtm350
Published HTML Report: https://rawcdn.githack.com/karMa083-x/final-project-qtm350/9026eb922f756ff82a2691da38ee467397d4c5b1/Dsci350_Final_Report.html


---


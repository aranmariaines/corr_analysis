
# Corruption Perception Index Differences Analysis

The Corruption Perceptions Index (CPI) is an index published annually by Transparency International which ranks countries by their perceived levels of public sector corruption, as determined by expert assessments and opinion surveys.

I analyzed the index and its composition. [Clik here for full report!](https://nakanotokyo.github.io/corr_analysis/CPI_Perception_Differences.html)

# Repository structure

## Data
Contains raw data download from Transparency International URL

## ETL
Contains R script that loads excel file for each year, normalizes column names, drop unused columns. 
Output: A CSV file with CPI for each country across years and sources

## Analysis_reports
Markdown and HTML files with final reports

## Style
html files for footer and header

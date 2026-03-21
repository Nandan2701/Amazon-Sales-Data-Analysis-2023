# Amazon-Sales-Data-Analysis-2023

## Project Overview

This project is an end-to-end exploratory data analysis of the **Amazon Sales Data 2023** dataset.  
The objective is to understand marketplace behavior using pricing, revenue, sales volume, and customer ratings.

Instead of creating separate repositories, four related analyses are grouped into one project:

1. Category performance using revenue and sales volume  
2. Price architecture across categories  
3. Customer rating analysis  
4. Customer trust and engagement segmentation  

This project focuses on practicing:

- Data cleaning  
- SQL-based analysis  
- Business-oriented interpretation  
- Dashboard-based visualization  

---

## Dataset

**Source:** Amazon Sales Data 2023  
**Size:** ~551,000 products  
**Structure:**

- Product name  
- Main category  
- Sub-category  
- Discount price  
- Actual price  
- Average rating  
- Number of ratings  
- Product link and image URL  

---

## Tools & Technologies

- **Python (Pandas, NumPy)** – data cleaning and preparation  
- **Jupyter Notebook** – exploratory analysis  
- **PostgreSQL** – structured analysis using SQL  
- **Power BI** – visualization and dashboards  

---

## Data Preparation

Main steps:

- Removed currency symbols and text from price columns  
- Converted relevant fields to numeric format  
- Removed duplicate products  
- Renamed columns for consistency and readability  

---

## Analysis Breakdown

### 1. Marketplace Category Segmentation (Revenue vs Volume)

Categories were segmented into four groups:

- High Revenue – High Volume  
- High Revenue – Low Volume  
- Low Revenue – High Volume  
- Low Revenue – Low Volume  

Purpose:

- Identify whether revenue comes from pricing or scale  
- Highlight strong and weak performing categories  

---

### 2. Price Architecture Analysis

Compared:

- Average price  
- Median price  
  Across categories and sub-categories  

Purpose:

- Understand price distribution  
- Detect premium-driven vs mass-market categories  
- Identify skewness caused by outliers  

---

### 3. Customer Rating Analysis

Analyzed:

- Average ratings by sub-category  
- Rating gaps inside main categories  

Purpose:

- Identify stable vs problematic categories  
- Separate quality issues from expectation mismatches  
- Treat ratings as a diagnostic signal rather than only a score  

---

### 4. Customer Trust & Engagement Segmentation

Built a simple trust-engagement framework using:

- Average rating  
- Number of ratings  

Categories were grouped into:

- High Engagement – High Ratings  
- High Engagement – Low Ratings  
- Low Engagement – High Ratings  
- Low Engagement – Low Ratings  

Purpose:

- Identify where to scale  
- Where product quality needs fixing  
- Where visibility is missing  
- Where investment should be avoided  

---

## Output

- SQL queries used for analysis  
- Power BI dashboards for visualization  
- PDF reports for each analysis part  

---

## Folder Structure

data/ → dataset
notebooks/ → Python cleaning & exploration
sql/ → SQL queries
dashboards/ → Power BI files
reports/ → PDF analysis reports
- data/ → dataset  
- notebooks/ → Python cleaning & exploration  
- sql/ → SQL queries  
- dashboards/ → Power BI files  
- reports/ → PDF analysis reports  

---

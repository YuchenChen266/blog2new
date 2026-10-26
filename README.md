# Blog Post 2: Finding Best Value Books with Web Scraping
This repository contains code and output for the web scraping blog post.

## Repository structure
- `blog2revised.Rmd`: Full analysis code and written discussion
- `blog2revised.html`: Rendered webpage for submission
- `/figures`: Saved scatter plot output

## Replication instructions
1. Open `blog2revised.Rmd` in RStudio
2. Install required package: `install.packages("rvest")`, `install.packages("ggplot2")`
3. Knit the document. The code scrapes data from books.toscrape.com, cleans variables, computes the value index, and saves the scatter plot into the figures folder.

## Data source
Data scraped from https://books.toscrape.com/. This website is designed for educational web scraping practice and permits non-commercial scraping for learning purposes.

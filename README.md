# AmbitionBox Web Scraping Tool 🕸️

This Jupyter Notebook scrapes company reviews and salary information from [AmbitionBox](https://www.ambitionbox.com) for analysis and reporting.

## Features

- Extracts review titles, ratings, pros/cons, and summaries
- Collects salary data by job title and experience
- Supports multi-page scraping
- Outputs data into pandas DataFrames

## Libraries Used

- `requests`
- `BeautifulSoup`
- `pandas`

## Output

The output is processed into a csv file with the following data:
- `Company name`
- `Type`
- `Rating`
- `Establishment`
- `Highly rated for`
- `Critically rated for`

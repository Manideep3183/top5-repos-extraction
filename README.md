# GitHub Trending Scraper

This project uses Python’s `requests` and `BeautifulSoup` libraries to scrape the top 5 trending repositories from [GitHub Trending](https://github.com/trending).

## Features

- Extracts top 5 trending repositories
- Gets repository name and GitHub link
- Saves the data to a CSV file: `trending_repos.csv`

## Requirements

- Python 3.x
- `requests`
- `beautifulsoup4`

## How to Run

```bash
pip install requests beautifulsoup4
python scrape_trending.py

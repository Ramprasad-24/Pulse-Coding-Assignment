# Pulse Coding Assignment - SaaS Reviews Scraper

Python script to scrape SaaS product reviews from G2, Capterra, and TrustRadius.  
Accepts company name, date range, and source, outputs reviews in JSON.  

## Usage
```bash ---we need to run this in the bash 
python review_scraper.py --company slack --source g2 --start_date 2024-01-01 --end_date 2024-06-30

## Sample Output
```json ----the output creates a json file to review the output 
[
    {
        "title": "Sample Review",
        "review": "This is a sample review for slack.",
        "date": "2025-12-27",
        "source": "g2",
        "reviewer_name": "John Doe",
        "rating": 5
    }
]

# Book Market Analytics: Books to Scrape
Data Science 500 assignment (Richfield). End-to-end pipeline: scrape (BeautifulSoup) → clean → visualise → linear regression → report.

## Run it
```bash
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook book_market_analytics.ipynb
```
Run all cells. The first run scrapes ~1000 books (about 5–10 minutes) and saves `data/books_raw.csv`; later runs reuse it. The cleaned dataset is saved to `data/books_clean.csv`.

## Files
- `book_market_analytics.ipynb`: full pipeline
- `data/books_clean.csv`: final dataset (submit this)
- `report/`: final PDF report

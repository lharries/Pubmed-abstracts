# Pubmed abstract scraper
Extract a huge number of pubmed abstracts for NLP

## How to use

`python utils/scraper.py` will download a very large number of abstracts into `data/abstracts.txt`.

To increase the number of abstracts increase `NUMBER_OF_FILES_TO_SCRAPE`. `NUMBER_OF_FILES_TO_SCRAPE` has a default of 4 (approximately 14,000 abstracts per file => ~56,000 by default).

## Source

[National Library of Medicine, PubMed](https://www.nlm.nih.gov/databases/download/pubmed_medline.html)

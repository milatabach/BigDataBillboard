# Billboard Lyrics Analysis

This project analyzes Billboard Top 100 songs from 1946 to 2022 to explore trends in artists, pronoun usage ("I", "We", "You"), and sentiment over time. It also compares average song sentiment with U.S. GDP per capita.

## How to Run

1. Make sure the datasets are in the `datasets/` folder:
   - `datasets/billboard_top_100_1946_2022_lyrics.csv`
   - `datasets/gdp_per_capita.csv`

2. Open and run the notebook or Python script in order. It will:
   - Load and analyze the data
   - Count pronoun frequencies
   - Perform sentiment analysis using VADER
   - Plot sentiment and GDP trends over time

## Requirements

- Python 3.x  
- pandas  
- matplotlib  
- nltk  

Install the dependencies with:
```bash
pip install pandas matplotlib nltk

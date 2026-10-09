# Amazon Review Sentiment Analysis

## Overview
This project analyzes Amazon food product reviews to determine customer sentiment and extract insights.

## Dataset
- **Source:** Amazon Fine Food Reviews (Kaggle)
- **Size:** 2,000 reviews
- **Columns:** ProductId, UserId, Score, clean_text, sentiment_label

## Analysis Results
- **77.9%** of reviews are positive
- **14.0%** are neutral
- **9.1%** are negative

## Key Findings
- High star ratings (4-5 stars) perfectly match positive sentiment
- Negative reviews mention: product quality, taste, packaging issues
- Strong correlation between ratings and sentiment

## Recommendation
Focus on improving product quality and packaging to reduce negative reviews.

## Technology Stack
- Python 3
- Pandas (data manipulation)
- Matplotlib (visualization)
- WordCloud (text visualization)

## Files
- `sentiment_analysis.ipynb` - Main analysis notebook
- Charts and insights included

## How to Run
1. Download the notebook from GitHub
2. Open in Google Colab or Jupyter
3. Upload the CSV file (amazon.csv)
4. Run all cells

## Author
[Your Name]

## License
MIT

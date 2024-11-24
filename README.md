# Kindle App Review Analysis

## Overview
This project analyzes user reviews of the Kindle app using sentiment analysis, topic modeling, and natural language processing techniques. The analysis provides insights into user satisfaction, common issues, and areas for improvement.

## Dataset
The analysis uses the Amazon Software Reviews dataset from:
- **Source**: [Amazon Review Data (2018)](https://cseweb.ucsd.edu/~jmcauley/datasets.html#amazon_reviews)
- **Paper**: Justifying recommendations using distantly-labeled reviews and fine-grained aspects
  - *Authors*: Jianmo Ni, Jiacheng Li, Julian McAuley
  - *Conference*: Empirical Methods in Natural Language Processing (EMNLP), 2019
- **Dataset Characteristics**:
  - Category: Software
  - Time period: May 1996 - October 2018
  - Total reviews analyzed: 459,436
  - Unique products: 21,663
  - Format: JSON.GZ

## Key Features
- Sentiment analysis of user reviews
- Topic modeling to identify key discussion themes
- Word frequency analysis and visualization
- Advanced text preprocessing and cleaning
- Interactive visualizations and dashboards

## Technologies Used
- Python 3.11
- Libraries:
  - pandas: Data manipulation and analysis
  - numpy: Numerical computations
  - matplotlib & seaborn: Data visualization
  - textblob: Sentiment analysis
  - nltk: Natural language processing
  - scikit-learn: Machine learning (LDA topic modeling)
  - wordcloud: Word cloud visualization

## Project Structure
```
kindle-reviews/
│
├── data/
│   └── Software.json.gz
│
├── notebooks/
│   └── clean-analysis-notebook.ipynb
│
├── README.md
└── requirements.txt
```

## Key Insights

### Sentiment Analysis
- Overall positive sentiment: 74.1% of reviews
- Neutral sentiment: 17.0% of reviews
- Negative sentiment: 9.0% of reviews
- Average rating: 4.23/5.0

### Topic Distribution
1. Features & Usage (83.0% positive)
2. Installation & Setup (73.3% positive)
3. Reading Experience (69.3% positive)

### Key Terms Analysis
Most mentioned features:
- Page navigation: 3.4% of reviews
- Library management: 2.2%
- Screen interface: 2.2%
- Sync functionality: 1.4%

### User Experience
- Usability terms:
  - "Easy": 8.3% of reviews
  - "Difficult": 0.7%
  - "Simple": 0.7%
- Performance terms:
  - "Fast": 0.8%
  - "Slow": 0.5%

## Key Recommendations
1. Technical Performance
   - Address crash reports
   - Improve speed optimization

2. User Interface
   - Simplify complex features
   - Enhance navigation

3. Feature Enhancement
   - Focus on most requested features
   - Improve sync functionality


## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
Your Name - Aravind Raju

## Acknowledgments
- Dataset provided by [Julian McAuley](https://cseweb.ucsd.edu/~jmcauley/) at UC San Diego
- Original paper: "Justifying recommendations using distantly-labeled reviews and fine-grained aspects" (EMNLP 2019)

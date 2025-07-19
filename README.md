# <u>**🎬 Fandango Movie Ratings Analysis**</u>

A comprehensive data analysis project examining movie rating discrepancies and potential bias in Fandango's rating system compared to other major review platforms.

## 📊 Project Overview

This project analyzes movie ratings from various platforms to investigate potential rating inflation on Fandango, a popular movie ticket purchasing website. The analysis explores rating distributions, correlations between different review sites, and visualizes patterns in movie scoring across platforms.

## 🎯 Objectives

- Analyze rating distributions across different movie review platforms
- Investigate potential bias or inflation in Fandango's rating system
- Compare Fandango ratings with other major review sites (Rotten Tomatoes, Metacritic, IMDB)
- Identify patterns and discrepancies in movie scoring
- Visualize rating correlations and distributions
- Provide insights into the reliability of different rating platforms

## 📁 Dataset Description

**Datasets Used:**
- `all_sites_scores.csv` - Comprehensive movie ratings from multiple platforms
- `fandango_scrape.csv` - Scraped Fandango ratings data



The datasets contain movie ratings from multiple platforms including:
- Fandango (user ratings and displayed ratings)
- Rotten Tomatoes (critics and audience scores)
- Metacritic (critics and user scores)
- IMDB (user ratings)

The data covers popular movies and provides a comprehensive view of how different platforms rate the same films, with the scraped data offering additional insights into Fandango's rating practices.

## 📂 Project Structure

```
fandango-analysis/
│
├── fandango.ipynb           # Main Jupyter notebook with analysis
├── all_sites_scores.csv     # Comprehensive ratings dataset
├── fandango_scrape.csv      # Scraped Fandango ratings data
├── requirements.txt         # Python dependencies
├── README.md               # Project documentation
└── images/                 # Generated visualizations (if saved)
```

## 📈 Visualizations Included

The notebook generates several key visualizations:

- **Rating Distribution Histograms** - Compare rating spreads across platforms
- **Correlation Heatmaps** - Show relationships between different rating systems
- **Scatter Plots** - Visualize rating comparisons between platforms
- **Box Plots** - Display rating distributions and outliers
- **Bar Charts** - Compare average ratings by platform
- **Regression Analysis** - Explore linear relationships between rating systems

---


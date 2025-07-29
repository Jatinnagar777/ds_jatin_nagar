# Trader Behavior vs Market Sentiment Analysis

## 📂 Project Overview
This project analyzes the relationship between trader behavior and market sentiment using Bitcoin market data and Hyperliquid trader data. The analysis explores how trading behavior (profitability, risk, volume, leverage) aligns or diverges from overall market sentiment (fear vs greed).

## 📊 Datasets
1. **Bitcoin Market Sentiment Dataset**
   - Columns: `Date`, `Classification` (Fear / Greed)
   - Source: Fear & Greed Index

2. **Historical Trader Data from Hyperliquid**
   - Columns: `account`, `symbol`, `execution price`, `size`, `side`, `time`, `start position`, `event`, `closedPnL`, `leverage`, etc.

## 🎯 Objective
Analyze how trading behavior (profitability, risk, volume, leverage) aligns or diverges from overall market sentiment (fear vs greed). Identify hidden trends or signals that could influence smarter trading strategies.

## 📁 Project Structure
```
ds_candidate_analysis/
├── notebook_1.ipynb          # Main analysis notebook (Google Colab)
├── notebook_2.ipynb          # Additional analysis notebook (Google Colab)
├── csv_files/                # All CSV and data outputs
├── outputs/                  # Visual outputs, graphs, charts
├── ds_report.pdf            # Final summarized insights
└── README.md                # This file
```

## 🚀 Setup Instructions

### Prerequisites
- Google Colab account
- Python libraries: pandas, numpy, matplotlib, seaborn, plotly
- Access to the provided datasets

### Dataset Links
1. **Historical Trader Data**: https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing
2. **Fear & Greed Index**: https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing

### Getting Started
1. Open `notebook_1.ipynb` in Google Colab
2. Upload the datasets to your Colab environment
3. Run the analysis cells sequentially
4. Check the `outputs/` folder for generated visualizations
5. Review `ds_report.pdf` for final insights

## 📈 Analysis Components
- **Data Preprocessing**: Cleaning and merging datasets
- **Exploratory Data Analysis**: Understanding data distributions and patterns
- **Sentiment Analysis**: Mapping fear/greed classifications to trading periods
- **Behavioral Analysis**: Analyzing trader profitability, risk, and volume patterns
- **Correlation Analysis**: Finding relationships between sentiment and behavior
- **Visualization**: Creating insightful charts and graphs

## 📝 Notes
- All analysis is performed in Google Colab notebooks
- Intermediate results are saved to `csv_files/`
- Visual outputs are saved to `outputs/`
- Final insights are compiled in the PDF report

## 🔗 Google Colab Links
- Main Analysis: [Link to be added after notebook creation]
- Additional Analysis: [Link to be added if needed]

---
*This project follows the required structure for data science candidate submissions.* 
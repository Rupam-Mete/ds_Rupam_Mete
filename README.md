# Trader Behavior vs. Market Sentiment Analysis

## Project Overview
This repository contains a data science analysis exploring the relationship between trader performance (PnL, volume) and the Bitcoin Fear & Greed Index. [cite_start]The goal is to identify how sentiment influences trading behavior and discover potential signals for smarter trading strategies[cite: 38, 39].

## 📂 Standardized Directory Structure
[cite_start]As per the assignment requirements, this project follows the strict directory layout[cite: 5, 8]:

- [cite_start]**`notebook_1.ipynb`**: Primary Google Colab notebook containing all data cleaning, merging, and EDA[cite: 9, 10].
- [cite_start]**`csv_files/`**: Contains the raw datasets used for the analysis[cite: 15].
  - [cite_start]`historical_data.csv`: Historical trader data from Hyperliquid[cite: 35, 41].
  - [cite_start]`fear_greed_index.csv`: Bitcoin Market Sentiment dataset[cite: 33, 43].
- [cite_start]**`outputs/`**: All visual results, charts, and graphs generated during the study[cite: 17, 23].
- [cite_start]**`ds_report.pdf`**: Final summarized insights and behavioral findings[cite: 19, 25].
- [cite_start]**`README.md`**: Project setup instructions and documentation[cite: 20].

## 🛠️ Setup & Usage
1. [cite_start]**Colab Access**: All code is strictly shared as **Google Colab links** with access set to 'Anyone with the link can view'[cite: 10, 27].
2. **Data Processing**: 
   - [cite_start]Column names were standardized (e.g., `Timestamp IST` and `Closed PnL`)[cite: 36].
   - [cite_start]Datasets were merged on a daily date key to align sentiment with trade execution[cite: 31, 38].
3. **Environment**: Analysis was performed using `pandas` for data manipulation and `seaborn`/`matplotlib` for visual insights.

## 📈 Key Objectives
- [cite_start]Analyze the correlation between market sentiment (Fear vs. Greed) and trader profitability (Closed PnL)[cite: 38].
- [cite_start]Identify hidden trends in leverage and trade size during different sentiment phases[cite: 39].
- [cite_start]Deliver data-driven insights to drive smarter Web3 trading strategies[cite: 37].

## 🔗 Links
  - **Google Colab Notebook**:[(https://colab.research.google.com/drive/1vhqj05S96dAs0fMCNv9shhrpy0lMEQ5Z?usp=sharing)]
- **Contact**: saami@bajarangs.com | nagasai@bajarangs.com | chetan@bajarangs.com | CC: sonika@primetrade.ai

Trader Behavior vs. Market Sentiment Analysis
Project Overview

This project examines the relationship between Bitcoin market sentiment, measured using the Fear & Greed Index, and trader performance data from the Hyperliquid platform. The objective is to uncover how overall market mood influences trader profitability and risk-taking behavior, including trade volume and leverage patterns.

Submission Structure

In accordance with the assignment guidelines, the project is organized as follows:

notebook_1.ipynb
Main analysis notebook executed in Google Colab.

csv_files/
Contains raw datasets, including Historical Trader Data and the Bitcoin Fear & Greed Index.

outputs/
Stores generated visualizations illustrating PnL trends and trading volume behavior.

ds_report.pdf
Final report summarizing key insights and strategic recommendations.

README.md
Includes setup instructions and additional project notes.

Setup Instructions

Google Colab:
The analysis is hosted on Google Colab. Ensure the notebook link is set to “Anyone with the link can view.”

Environment Requirements:
The project relies on the following Python libraries:

pandas

matplotlib

seaborn

Data Loading:
The notebook is configured to load all datasets directly from the csv_files/ directory.

Key Insights

Contrarian Profitability:
Higher average PnL was observed during periods classified as Fear, indicating that lower market sentiment may present better trading opportunities.

Volume Trends:
Trading volume frequently peaks during Greed phases, suggesting increased risk-taking and potential over-extension when market sentiment is overly optimistic.
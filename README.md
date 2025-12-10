# 📊 Nifty 500 Web Scraping & Exploratory Data Analysis (EDA)

Automated Financial Data Extraction • Data Cleaning • Market Insights • Visualization
##📝 Project Overview

This project automates the scraping, cleaning, and exploratory analysis of financial data for all Nifty 500 companies from Screener.in.
Perfect for beginners in stock analysis, data enthusiasts, and Python automation learners.

##🎯 Objective

To build an end-to-end data pipeline that:
✔ Scrapes financial metrics of Nifty 500 companies
✔ Cleans, preprocesses, and fixes missing values
✔ Performs exploratory analysis to generate insights
✔ Helps visualize stock market patterns & valuation metrics

##📂 Project Structure

Nifty500-WebScraping-EDA/
│
├── README.md
├── requirements.txt
├── LICENSE
├── .gitignore
│
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
│
├── notebooks/
│   └── Nifty500_WebScraping_and_EDA.ipynb
│
├── src/
│   ├── scraper.py
│   ├── eda.py
│   └── utils.py
│
└── reports/
    └── Fundamental_Analysis_Presentation.pdf

##🛠️ Technologies Used

🐍 Python

🍲 BeautifulSoup4

📦 Requests

📊 Pandas

📈 Matplotlib, Seaborn

📒 Jupyter Notebook

##📊 Key Insights

###📌 Market Cap Distribution

🔵 Large Cap: 190 companies

🟠 Mid Cap: 168 companies

🟢 Small Cap: 142 companies

###📌 P/E Ratio Classification

🟢 0–20: Undervalued

🟡 20–26: Fair Value

🔴 26+: Overvalued

###📌 Strong Correlations

📈 Market Cap ↔ Net Profit (0.85)

📈 Sales ↔ Net Profit (0.84)

###📌 Weak Correlations

ROCE does not correlate strongly with company size or profits

##📈 Visualizations Included

📌 Market Cap distribution bar charts

📌 Profit vs Market Cap scatter analysis

📌 Sales vs Net Profit relationship plots

📌 Profit variation boxplots

📌 Correlation heatmaps

📌 ROCE impact visualizations

##🚀 How to Run the Project
1️⃣ Install dependencies
pip install -r requirements.txt

2️⃣ Run the scraper
python src/scraper.py

3️⃣ Run EDA
python src/eda.py

📘 Data Source

Screener.in (Public financial data for NSE & BSE companies)

📄 License

📜 This project is licensed under the MIT License.

##👨‍💻 Author
Kotireddy Narendra Reddy
📍 Bengaluru, India
🔗 LinkedIn: https://www.linkedin.com/in/kotireddy-narendra-reddy-5105301a6

# FinancialDashboard-S-P500
AI-powered financial dashboard analyzing S&amp;P500 companies with Python, Pandas, data visualization, and LLaMA 2 for actionable insights.
# Interactive Financial Summary Dashboard (S&P 500)

This project is a full-stack, browser-based financial dashboard that analyzes and visualizes the performance of selected S&P 500 companies. It combines Python-based data engineering, AI-generated summaries via Hugging Face, and a custom-built HTML/CSS/JavaScript frontend, delivering interactive insights and risk classifications.

## Features

- Company-level financial summaries with risk classification (Safe, At Risk, High Risk)
- Interactive charts showing revenue, net income, and EBIT trends
- AI-generated summaries using Hugging Face models and prompt engineering
- Responsive UI built with custom CSS and modular JavaScript
- Python pipeline for data cleaning, feature engineering, and selection
- Top 5 safest and riskiest companies ranked by profitability metrics

## Screenshots

### Dashboard Overview
![Dashboard Overview](assets/screenshots/dashboard-overview.png)

### Company Summary Card
![Company Summary](assets/screenshots/company-summary.png)

### Financial Trend Chart
![Financial Trends](assets/screenshots/financial-trends.png)

## Tech Stack

| Layer        | Tools Used                          |
|--------------|-------------------------------------|
| Data Prep    | Python, Pandas, NumPy               |
| Feature Eng. | Prompt engineering, Scikit-learn    |
| AI/NLP       | Hugging Face Transformers           |
| Frontend     | HTML5, CSS3, JavaScript             |
| Visualization| Chart.js or D3.js                   |
| Deployment   | GitHub Pages, Google Colab          |

## Sample Companies Analyzed

- Apple (Safe)
- Tesla (High Risk)
- eBay (Safe)
- Norwegian Cruise Line Holdings (High Risk)
- Intercontinental Exchange (Safe)
- Carnival Corporation (High Risk)
…and more

## Data Pipeline

The backend pipeline was built in Google Colab using Python and Hugging Face to:
- Clean and preprocess raw financial data
- Engineer features like profitability ratios and risk scores
- Select key indicators for visualization
- Generate AI-powered summaries using pretrained NLP models
- Output structured JSON for front-end rendering

View the Colab notebook:  
[Google Colab: Financial Data Pipeline](https://colab.research.google.com/drive/1BWaBV8jebIOFoeO13RsQxWj2OUUWFAnr#scrollTo=6509fb34)
#Repository Structure#


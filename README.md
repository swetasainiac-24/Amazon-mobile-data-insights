# Amazon-mobile-data-insights
A complete data pipeline for Amazon mobile listings. Includes a custom web scraper using BeautifulSoup, automated data cleaning, and detailed EDA to uncover pricing trends and brand insights.

# Amazon Mobile Market Analysis (Data Analytics Project)

A hands-on data analytics project that demonstrates the process of gathering raw web data and converting it into meaningful visual insights. This project analyzes the smartphone market trends on Amazon India.

##  Project Workflow
1. **Web Scraping:** Extracting product names, prices, and ratings from Amazon using `BeautifulSoup`.
2. **Data Wrangling:** Cleaning the scraped data, converting currency strings to numerical values, and handling missing records.
3. **Exploratory Data Analysis (EDA):** Using `Matplotlib` and `Seaborn` to identify patterns such as price distribution and top-rated brands.

##  Tools Used
* **Python** (Core Logic)
* **Pandas** (Data Manipulation)
* **BeautifulSoup4** (Web Scraping)
* **Matplotlib & Seaborn** (Data Visualization)

##  File Description
* `Task 1.ipynb`: Web scraping script for Amazon product listings.
* `Task2 EDA+ Task 3.ipynb`: Data cleaning and analytical visualizations.

##  Key Findings
- Analysis of price segments (Budget vs. Premium).
- Average customer rating across different brands.
- Distribution of mobile phone listings based on discounts and offers.

##  Setup
```bash
pip install pandas beautifulsoup4 requests matplotlib seaborn

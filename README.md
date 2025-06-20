# 🌍 A Web-Scraped Overview of Global Market Cap Distribution by Country

This project uses **web scraping** to collect data from https://companiesmarketcap.com/page/1/#google_vignette and analyzes the **global distribution of market capitalization** across countries. A key focus is the comparison of **USA vs Rest of the World** using visualizations.

## 📌 Project Highlights

- ✅ Scraped data for ~6200 publicly listed companies across 60+ pages.
- ✅ Extracted key attributes: Company, Ticker, Market Cap, Price, Daily Change, and Country.
- ✅ Converted string-based market caps (e.g., "$1.3T", "$650B") into numeric values.
- ✅ Aggregated country-wise statistics.
- ✅ Visualized:
  - Top 10 countries by number of companies
  - Top 10 countries by total market capitalization
  - Market Cap Comparison: **USA vs Rest of the World**

## 📊 Technologies Used

- `Python 3`
- `BeautifulSoup` for web scraping
- `Requests` for HTTP calls
- `Pandas` for data cleaning and analysis
- `Matplotlib` for data visualization
- `Google colab` for development

## 📈 Sample Visualizations

- Bar chart: Top 10 countries by total market capitalization
- Pie chart: USA vs Rest of the World (market share)
- Country-level insights from scraped HTML table data


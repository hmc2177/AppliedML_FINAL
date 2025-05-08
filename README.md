# AppliedML_FINAL
This projects aims to reverse engineer Morgan Stanley Capital Management's (MSCI) ESG risk rating scores, to see if they can be inferred solely from publicly available information on the public companies. This involves the use of ESG word frequencies in annual reports, earnings call transcripts and news reports involving the company, as well as its fundamental financial data as would be found on platforms such as Bloomberg and Yahoo Finance. I performed exploratory data analysis using k-means clustering as well as experimenting with a regularized regression model and a random forest model. 

Data Sources:
MSCI ESG ratings dataset: Sourced from Columbia library in the database MSCI ESG Direct https://clio.columbia.edu/databases/10498319
10K and 20F filings: Sourced (via scraping) from the US Securities and Exchange Commission database https://www.sec.gov/Archives/edgar/data/
Stock tickers list: Nasdaq Trader symbol directory ftp://ftp.nasdaqtrader.com/SymbolDirectory/
Financial data: Alpha Vantage Fundamental Data - Company Overview via API key https://www.alphavantage.co/documentation/
Earnings call transcript: Alpha Vantage Alpha Intelligence - Earnings Call Transcript https://www.alphavantage.co/documentation/
News reports: Alpha Vantage Alpha Intelligence - News & Sentiments https://www.alphavantage.co/documentation/

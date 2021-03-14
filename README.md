# Sentiment Analysis
Project Implementation


Phase 1 – Parse & Extract data
1.Parse data of chosen tickers from Finviz
2.Extract Financial News from Finviz
3.Process the data:
	a.Store News in dictionary.
	b.Disintegrate dictionary into relevant items – Ticker, Date, Time, Title.
	c.Store the disintegrated dictionary items into list.
	d.Convert list to dataframe.


Phase 2 – Calculate Sentiment Score
4.Calculate compound scores
5.Process data further:
	a.Create new dataframe which composes of Ticker, Date & Mean compound scores.
	b.Unstack dataframe, transpose it, & use cross-sectional to create a cleaner dataframe.
6.Visualize the sentiment score.


Phase 3 – Download historical data
7.Download Historical Data using yfinance.
8.Calculate Daily Returns.


Phase 4 - Data Analysis 
9.Compare Daily Returns to Sentiment Score to check if they are related.
10. Use correlation matrix & heatmap to analyze & visualize data respectively

		Function			Libraries Used
		HTML Requests		Urllib
		Parsing Data		BeautifulSoup
		Compound Scores		NLTK
		Historical data download	Yfinance
		Visualize Data		Matplotlib

 

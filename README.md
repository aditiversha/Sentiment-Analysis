# Sentiment Analysis
Project Implementation

### Objective - To find correlation between financial news of the given stock & it's price change using Sentiment Analysis

#### Phase 1 – Parse & Extract data
1. Parse data of chosen tickers from Finviz using BeautifulSoup
2. Extract Financial News from Finviz
3. Process the data using Pandas:
	<ol>a. Store News in dictionary.</ol>
	<ol>b. Disintegrate dictionary into relevant items – Ticker, Date, Time, Title.</ol>
	<ol>c. Store the disintegrated dictionary items into list.</ol>
	<ol>d. Convert list to dataframe.</ol>


#### Phase 2 – Calculate Sentiment Score
4. Calculate compound scores (function - Sentiment Analyzer, Library - NLTK)
5. Process data further using Groupby and XS:
	<ol>a. Create new dataframe which composes of Ticker, Date & Mean compound scores.</ol>
	<ol>b. Unstack dataframe, transpose it, & use cross-sectional to create a cleaner dataframe.</ol>
6. Visualize the sentiment score.


#### Phase 3 – Download historical data
7. Download Historical Data using yfinance.
8. Calculate Daily Returns.


#### Phase 4 - Data Analysis 
9. Compare Daily Returns to Sentiment Score to check if they are related.
10. Use correlation matrix & heatmap to analyze & visualize data respectively

		Function			Libraries Used
		HTML Requests		Urllib
		Parsing Data		BeautifulSoup
		Compound Scores		NLTK
		Historical download	Yfinance
		Visualize Data		Matplotlib

### Inference - Most of the stock prices are not much affected by the release of specific news. Exception being Tesla. The daily change in prices of Tesla has shown perfect correlation to the news.

### Output Images
 
 #### Compound Scores Bar Chart
 ![download (2)](https://user-images.githubusercontent.com/78731243/119055330-7b77d680-b9e6-11eb-9d8e-f5c28cbb1563.png)

#### Correlation Scores (Compound vs Daily Returns)
![Capture](https://user-images.githubusercontent.com/78731243/119055560-e5907b80-b9e6-11eb-83ea-38d782479ccf.PNG)


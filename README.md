# Trade-and-Ahead
Unsupervised Learning
The stock market has consistently proven to be a good place to invest in and save for the future. There are a lot of compelling reasons to invest in stocks. It can help in fighting inflation, create wealth, and also provides some tax benefits. Good steady returns on investments over a long period of time can also grow a lot more than seems possible. Also, thanks to the power of compound interest, the earlier one starts investing, the larger the corpus one can have for retirement. Overall, investing in stocks can help meet life's financial aspirations.

It is important to maintain a diversified portfolio when investing in stocks in order to maximise earnings under any market condition. Having a diversified portfolio tends to yield higher returns and face lower risk by tempering potential losses when the market is down. It is often easy to get lost in a sea of financial metrics to analyze while determining the worth of a stock, and doing the same for a multitude of stocks to identify the right picks for an individual can be a tedious task. By doing a cluster analysis, one can identify stocks that exhibit similar characteristics and ones which exhibit minimum correlation. This will help investors better analyze stocks across different market segments and help protect against risks that could make the portfolio vulnerable to losses.

Objective
Trade&Ahead is a financial consultancy firm who provide their customers with personalized investment strategies. They have hired you as a Data Scientist and provided you with data comprising stock price and some financial indicators for a few companies listed under the New York Stock Exchange. They have assigned you the tasks of analyzing the data, grouping the stocks based on the attributes provided, and sharing insights about the characteristics of each group.

Data Dictionary
Ticker Symbol: An abbreviation used to uniquely identify publicly traded shares of a particular stock on a particular stock market
Company: Name of the company
GICS Sector: The specific economic sector assigned to a company by the Global Industry Classification Standard (GICS) that best defines its business operations
GICS Sub Industry: The specific sub-industry group assigned to a company by the Global Industry Classification Standard (GICS) that best defines its business operations
Current Price: Current stock price in dollars
Price Change: Percentage change in the stock price in 13 weeks
Volatility: Standard deviation of the stock price over the past 13 weeks
ROE: A measure of financial performance calculated by dividing net income by shareholders' equity (shareholders' equity is equal to a company's assets minus its debt)
Cash Ratio: The ratio of a company's total reserves of cash and cash equivalents to its total current liabilities
Net Cash Flow: The difference between a company's cash inflows and outflows (in dollars)
Net Income: Revenues minus expenses, interest, and taxes (in dollars)
Earnings Per Share: Company's net profit divided by the number of common shares it has outstanding (in dollars)
Estimated Shares Outstanding: Company's stock currently held by all its shareholders
P/E Ratio: Ratio of the company's current stock price to the earnings per share
P/B Ratio: Ratio of the company's stock price per share by its book value per share (book value of a company is the net difference between that company's total assets and total liabilities)

Business Problem Overview
The task at hand is to analyze the data, group the stocks based on the attributes provided, and share insights about the characteristics of each group.

Tools used
•	Python: scipy.spatial.distance, sklearn.model_selection, sklearn.metrics, yellowbrick.cluster, scipy.cluster.hiearchy
•	Numpy library for computation
•	Sklearn: sklearn.cluster, sklearn.compose, sklearn.preprocessing
•	Seaborn library for informative statistical graphs
•	Matplotib for interactive visualizations

Project Coverage
To perform a cluster analysis, to identify stocks that exhibit similar characteristics and ones which exhibit minimum correlation. This will help investors better analyze stocks across different market segments and help protect against risks that could make the portfolio vulnerable to losses.

Tasks Performed
•	Exploratory data analysis
•	Univarate analysis: boxplot, labeled barplot
•	Bivarate analysis: Heat map, outlier check
•	Scaling data, K-means clustering, K with the elbow method
•	Silhouette score, silhouette visualizer, cluster profiles
•	Hierachical clustering, linkakge with Euclidean distance
•	Dendograms using single linkage, complete linkage, average linkage, centroid linkage, ward linkage and weighted linkage
•	Cluster Profiling

Business Insights
•	Cluster 2 companies are the ones which have a low price and have had a great previous quarter. They are less riskier investments and are traded in large volumes. The low P/E ratio might also indicate that these stocks are undervalued, but we will have to dig deeper to conclude the same with confidence.
•	Cluster 3 company stocks are moderately priced and are less volatile. They had a good previous quarter and their stocks are traded in moderate volumes. The moderate earnings per share also indicate that these stocks will yield good returns.
•	Trade&Ahead  should  look  into  more  financial  (fundamental  and  technical)  indicators  to  make better predictions of stock price movements and assessment of company valuation
•	Trade&Ahead  should also conduct cluster analysis separately for each of the economic sectors as it will help them to provide better investment recommendations to their clients.




















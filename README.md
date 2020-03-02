# Web-Services
In support of parts A and, B, use a file called env_vars.env, with the keys needed to access the data. Use the dotenv and os packages to load and access properties defined in this file
Part A – Accessing a web service via Python types - Quandl
A.1 Using the Quandl web site (www.quandl.com), identify a set of time series of that you are
interested in, which are available for several countries (or currencies) for several years. The
data should be for a consistent measure, e.g., all GDP or another measure of interest.
A.2 Access the data using the appropriate Quandl identifiers and the quandl.get() function.
A.3 Consolidate the data into a pandas DataFrame.
A.4 Visualize the data as a multi-line time series plot.
Part B – Accessing a web service via REST (requests) calls – Alpha Vantage
B.1 For two stocks of interest, access their intraday data using Alpha Vantage and the requests
package. Use 5 minute intervals.
B.2 Consolidate the data into a pandas DataFrame.
B.3 Visualize the data in one chart containing two separate lines (one line for each stock). Use
two Y axes (a left and right Y axis), where the left axis corresponds to one stock, and the right Y
axis corresponds to the other stock, so that the chart is not compressed for one of the series.
B.4 Calculate the correlation of the 5min returns of the two price series.

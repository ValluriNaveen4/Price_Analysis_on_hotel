PROBLEM STATEMENT: Finding right place for comfortable stay within the budget
OBJECTIVE: Price Analysis on OYO Hotels based on Cities, Reviews and Star ratings
TOOLS(LIBRARIES) USED: Web Scrapping, Requests, BeautifulSoup, Pandas, Numpy, RegularExpression, Matplotlib, Seaborn
DATA FRAME CREATION:
Chosen to extract data of four different cities from OYO website.
Getting URL from website through the process requests.get() ,Checking the Status Code and setting the Status code.
Beautifying the data by using BeautifulSoup libraries.
Loading HTML of the website using inspect.
DATA CLEANING: 
Handling the missing values.
Filling the missing values with the Mean Values for the Numerical Data.
Filling the missing values with the mode Values for Categorical Data.
Replace missing values.
Converting the Values to ‘int’ and ‘Float’.
Dropping the null values
VISUALIZATION: Performed Univariate Analysis, Bivariate Analysis, Multi-variate Analysis
CONCLUSION:
OYO Hotel prices are highest in Bangalore city.
Hotels in Noida city are cheaper when compared, but display maximum “Fair” reviews by the customers.
OYO Hotels offer almost same proportions of discounts across different cities.
Original price (Price before discount) is linearly varying with Price (Discounted price). However, few deviations are visible due to varying discounts. 
Hotel prices are totally independent of star ratings.
Overall, OYO reviews and ratings prove the firm’s ability to satisfy the customers.









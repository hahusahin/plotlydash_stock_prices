# STOCK PRICES DASHBOARD CREATED BY PLOTLY DASH

![Stock Price](https://github.com/hhsmobileapps/plotlydash_stock_prices/blob/master/snapshot.jpg)

### Goal
The goal of this study is to create an interactive web dashboard app of some well-known companies' stock prices using the Plotly Dash.

### Data Description
The data is dynamic, i.e. is fetched from web by using the pandas-datareader library when you run the code.
There is also a static data of the company names to be used in the dropdown menu.

### Dashboard Usage
* When you run the script, it automatically runs the local server and opens the dashboard in your default browser.
* From the dropdown menu on the left, select single or multiple company name(s),
* From the date picker select the time range you want,
* After clicking Submit button, the stock prices of the selected companies will be displayed in the graph within the selected time period.
* You can play around with the dropdown menu, start-date and end-date, then get the desired results.
* Here is the web-link : https://plotly-dash-stockprice-app.herokuapp.com/

### Files
* company_list.csv - Company names
* Plotly_Dash_Stock_Prices.ipynb - Project Notebook

### Libraries Used
* pandas,pandas_datareader
* plotly
* dash, dash_core_components, dash_html_components
* datetime

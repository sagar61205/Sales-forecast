# Sales-margin forecasting

## Business problem statement:

1. Determine whether there are detectable trends in Sales-Margin values at a supplier or overall(all suppliers) level over a 10-year period.

2. Build forecast models to predict Sales-margin percentages for the year 2022-2023.

3. Understand seasonality, trend and variability of Sales-margin for each individual supplier over a 10-year period to understand their 
behaviour pattern, in order to make better buisness decisions regarding inventory managemnet and competitive inteliigence.

## Forecasts:
![overall ](https://github.com/sagar61205/Buy-margin-forecast/assets/5305547/f1ff8ef7-3f5c-4f87-b732-02a2b19f8b00)

![newplot (1)](https://github.com/sagar61205/Buy-margin-forecast/assets/5305547/1a4481f4-9c66-46b9-a11f-67fdad064bd8)

![newplot (2)](https://github.com/sagar61205/Buy-margin-forecast/assets/5305547/e7ebfc50-1724-4fad-8f05-e2d12eaa157d)

![newplot (3)](https://github.com/sagar61205/Buy-margin-forecast/assets/5305547/aa6339a8-20b4-4f69-8741-e5de399fbaff)


# Features:
1.	Month Year - Shows the month and year for sales, wholesale and aquisition cost, and buy-margin for multiple parent pharmaceutical suppliers.
2.	Parent supplier number - Shows the corresponding parent suplier supplier number associated with each supplier
3.	Buy-margin raw dollar - Shows the original buy-margin amount prior to grouping with wholesale and aquisition cost and sales for each supplier
4.	WAC: Shows the total wholesale and aquisition cost of all drugs/medicines for each supplier
5.	Sales: Shows the total amount of sales of all drugs/medicines by each supplier
 
These are the major factors affecting the sales-margin value. Additonally, all the values are grouped with sales and parent suppliers number for 
a complete analysis of sales-margin value trend, seasonality, variability for parent supplier based on total sales.

## We helped the client by:

<ul>
<li>Identifying trends and seasonality in the overall supplier data in comparison with the top 3 suppliers</li>
<li>Forecast models produced for the top 3 suppliers as well as an overall model for all suppliers</li>
<li>Analyzed long-term trends, behaviors, variability, distributions and transformations of top 3 individual suppliers along with the overall model and 
their impact on the future forecast</li>
<li>Analyzed behaviour patterns of each supplier, in order to make better business decisions regarding inventory managemnet and competitive inteliigence.</li>
</ul>

## Creating meaningful impact:
<ul>
<li>Created a forecasting model by minimizing the error rate from a 10%-15% range to a range of 4%-6% as per the domain and business requirement.</li>
<li>Performance mterics used: MAE and RMSE for the top 3 suppliers and the overall model.</li>
<li>Created a report with crucial insights and takeaways for top suppliers in terms of trends, seasonality, variability and forecast accuracy for critical future business decisions.</li>
</ul>

This is a POC(Proof of concept) kind-of project. The data used here comes up with no guarantee from the organization. So, please don't use it for making forecasting decsions. However, this project presents the idea that how we can use Machine learning time-series forecasting into practice and how much impact we can generate from the same.

## MOTIVATION 💪
<ul>
<li>Client required sales-margin values, studied and forecasted for each supplier mainly the top 3 suppliers to make future buisness decisions in terms of inventory management. </li>
<li>This was to be done based on the seasonality, trends and behaviour patterns of each of these suppliers in terms of sales values. </li>
<li>Having a huge number of suppliers and each top supplier accounting for $5 million, there was no streamlined way and a forecasting model which could help make future descision making. </li>
<li>We not only seggregated the data from millions of records but classifed it, restructured it, and created the forecast model based on the 10-year data using ARIMA and SARIMAX.</li>
<li>fbprophet library and LSTM architecture were also used. However, best results were obtained by using ARIMA.</li>
</ul>

## Built with 🛠️
<p align="left"> <a href="https://www.arduino.cc/" target="_blank"> <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="arduino" width="40" height="40"/> </a> <a href="https://www.gnu.org/software/bash/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40"/> </a> <a href="https://getbootstrap.com" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a><a href="https://flask.palletsprojects.com/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/pocoo_flask/pocoo_flask-icon.svg" alt="flask" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://heroku.com" target="_blank"> <img src="https://www.vectorlogo.zone/logos/heroku/heroku-icon.svg" alt="heroku" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a><a href="https://postman.com" target="_blank"> <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40"/> </a><a href="https://scikit-learn.org/" target="_blank"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a></p>       


## FORECASTS AND INSIGHTS 🚀 

### Top supplier 1:
![newplot (1)](https://github.com/sagar61205/Buy-margin-forecast/assets/5305547/1a4481f4-9c66-46b9-a11f-67fdad064bd8)
 
#### Insights:
<ul>
<li>Seasonality is present in the top 1 individual supplier.</li>
<li>Sales-margin % is stable across time but long-term trends vary.</li>
<li>Shows no long-term trend in monthly sales-margin either.</li>
</ul>  

  
#### Interactive plot:

#### [Click here to explore the interactive plot for Top supplier 1](https://htmlpreview.github.io/?https://raw.githubusercontent.com/sagar61205/Sales-margin-forecast/main/Top%20supplier%201.html)
 

### Top supplier 2:
![newplot (2)](https://github.com/sagar61205/Buy-margin-forecast/assets/5305547/e7ebfc50-1724-4fad-8f05-e2d12eaa157d)
 
#### Insights:
<ul>
<li>Seasonality is present in the top 2 individual supplier.</li>
<li>Sales-margin(%) is stable across time but long-term trends vary.</li>
<li>Sales-margin has declined somewhat over time, but appears to possibly be bouncing back.</li>
</ul>  


#### Interactive plot:

#### [Click here to explore the interactive plot for Top supplier 2](https://htmlpreview.github.io/?https://raw.githubusercontent.com/sagar61205/Sales-margin-forecast/main/Top%20supplier%202.html)


 
### Top supplier 3:
![newplot (3)](https://github.com/sagar61205/Buy-margin-forecast/assets/5305547/aa6339a8-20b4-4f69-8741-e5de399fbaff)

#### Insights:
<ul>
<li>Seasonality is present in the top 3 individual supplier.</li>
<li>Sales-margin(%) is stable across time but again, long-term trends vary.</li>
<li>Sales-margin(%) has also changed over time, and appears to have become more variable month to month in the past couple years.</li>
</ul>   

#### Interactive plot:

#### [Click here to explore the interactive plot for Top supplier 3](https://htmlpreview.github.io/?https://raw.githubusercontent.com/sagar61205/Sales-margin-forecast/main/Top%20supplier%203.html)


 
### Overall model(all suppliers):
![overall ](https://github.com/sagar61205/Buy-margin-forecast/assets/5305547/f1ff8ef7-3f5c-4f87-b732-02a2b19f8b00)
 
#### Insights:
<ul>
<li>Seasonality is present in the overall model.</li>
<li>Sales-margin(%) is stable across time.</li>
</ul>   
 
#### Interactive plot:

#### [Click here to explore the interactive plot for the Overall Model.html](https://htmlpreview.github.io/?https://raw.githubusercontent.com/sagar61205/Sales-margin-forecast/main/overall%20model.html)



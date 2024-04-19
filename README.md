# ShopSmart Data Analysis
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
 
The objective of this notebook is to conduct a comprehensive analysis of the data The objective of this notebook is to conduct a comprehensive analysis of the data gathered from the ShopSmart website. The aim is to uncover valuable insights into how customers interact with the site, their buying behaviors, and their product preferences.

### In this notebook, I am going to try to answer a few questions:

#### A. Visit Frequency
1. Determine the frequency of the customer's visits to the website based on the available data.
2. Identify any patterns or trends in the frequency of the customer's visits.

#### B. Location Analysis
1. Ascertain the customer's location using the provided data.
2. Analyze how the customer's location might influence their purchasing behavior.

#### C. Overall Purchase Behavior
1. Draw insights about the customer's overall behavior on the website using the provided data.
2. Discuss how these insights could inform marketing strategies or personalized recommendations for this customer.


### Data Sources:
The data for this project will be sourced from ShopSmart Inc.'s website and will include various attributes such as customer IDs, device IDs, transaction details, product information, and timestamps of customer interactions.

### GitHub Project Repository :
* [ShopSmart Data Analysis](https://github.com/SaliuA/ShopSmart_Customer_analysis)

This project also serves as an assessment for the Data Science course at AltSchool.
* [Alt school Data science](https://altschoolafrica.com/)

### Summary :
The exploratory data analysis of the ShopSMart data revealed the following actionable insights:

* **Uniform Engagement Distribution:**<br>
Initially, customer engagement with the website was evenly distributed.
However, there was a significant surge in site activities starting on the 29th.
Investigate the cause of this sudden increase and consider amplifying the actions that led to it.

* **Top-Performing Product:**<br>
The Canon EOS R5 Camera emerged as the top performer, leading in customer interactions, unit sales, and revenue generation. This product drew an impressive 39,715 interactions and amassed a staggering $8,923,978 in revenue. In contrast, the Nintendo Switch, despite being the least sold item, still managed to earn a commendable $567,281. The Coca-Cola 12-pack, even though it sold 2124 units, generated the lowest revenue at $12,722.76. The store should capitalize on the popularity of the Canon EOS R5 camera to boost revenue, while also ramping up marketing efforts for the Nintendo Switch and Coca-Cola 12-pack.

* **Average Interaction Duration:**<br>
On average, customers spent 4.0 days interacting with the site.
Use this insight to optimize user experience and encourage longer engagement.

* **Order Success Rate Optimization:**<br>
Currently, successful orders account for only 33.3% of all orders on the site.
Efforts should be made to increase this percentage and improve order success rates.

* **Revenue and Loss Insights**:<br>
The store revenue during the dataset period was $22,760,347.
However, $44,682,020 in potential revenue was lost due to failed and canceled orders.
Focus on minimizing failed/canceled orders to maximizing revenue.

* **Spending Distribution**:<br>
The average amount spent by customers is $2,133.
While most customers spend below $2,500, there are outliers with significantly larger spending.
Consider strategies to attract more high-spending customers.

* **Revenue from Countries**:<br>
The average revenue from countries is $93,664.
Singapore emerges as the standout revenue contributor, generating an impressive $252,275.
Conversely, Slovenia trails behind, contributing a mere $180.
Focus on underperforming markets with high interaction levels (e.g., Argentina) to boost revenue.

* **Valued Customer Identification**:<br>
Customer bb7fd0af stands out as the most valued, spending $44,417 on the site.
Nurture relationships with high-value customers.

### Built With

```
pandas
seaborn
matplotlib
geopandas
```

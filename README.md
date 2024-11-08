# Ice Cream Sales Chart Visualization
Silly’s Ice Cream Shop is considering three different business strategies for next summer:

1. <b>Invest in a better weather tracking app</b> to predict good weather days
2. <b>Close the shop</b> one or two days a week to make staffing easier and more cost-effective
3. <b>Add more flavors</b> to the menu to keep customers interested

The shop has one month of data from last summer. The shop’s owner is curious about which days in August had the best sales numbers and has compiled a dataset that includes sales data and other factors that may have contributed to daily totals, including the temperature, humidity, and day of the week. Additionally, the top-selling flavor of the day is listed for each day, and the sales count error is listed for each day.

# Preparation Data
The first step was to load all data from the [icecream_data.csv](https://6e2ce8dd71d04e4190664e68d10b88b0.cc-propeller.cloud/edit/icecream_data.csv).

# Data Visualizations
This bar chart examines sales numbers for each day of the month. With a horizontal AB line at the owner’s benchmark for a successful sales day ($640), it's easier to see successful days of sales. An error bar was also added using the sales_error column.<br>
![August sales](https://github.com/tiaralgrier/ChartVisualization/blob/main/ice_cream_sales-bar_graph_august.png?raw=true)<br><br>

At a quick glance, a pattern became apparent, so I went a step deeper and visualized the data by day of the week. First, I had to group the sales data by day of the week and return the average sales data for each day to make one average bar for each day of the week. In this bar graph, it's easier to see that Mondays, Tuesdays, and Wednesdays were consistently their weaker days of sales. It is my recommendation that Silly's consider closing on Mondays and Tuesdays (also Wednesdays if they're considering a 3rd day closed).<br>
![Daily sales](https://github.com/tiaralgrier/ChartVisualization/blob/main/ice_cream_sales-bar_graph_day.png?raw=true)<br><br>

Now I can visualize the top-selling flavors. Of their 16 flavors of ice cream, however, I want to examine their top 3 flavors, which were Moosetracks, Coffee, and Mint Chip.<br>
![Pie chart of flavors](https://github.com/user-attachments/assets/2eb292b4-2484-438b-bbca-2264bc3058a1)<br><br>

The owner was curious about the impact of weather on sales. Using the dataset, I made two scatterplots in subplots to compare the effect of temperature on ice cream sales, and the effect of humidity on ice cream sales. Viewing these scatterplots side-by-side shows that when humidity and temperatures reach beyond 70% and 70°, customers are less likely to come into the shop. This may indicate that the shop owner may benefit from considering humidity and temperature into their hours or operation.<br>
![Scatterplot](https://github.com/tiaralgrier/ChartVisualization/blob/main/ice_cream_sales-scatterplot.png?raw=true)<br><br>

Finally, I added a vertical AB line at the owner’s benchmark for a successful day of sales. This shows that most of Silly’s August sales were above the benchmark.<br>
![Bar graph](https://github.com/tiaralgrier/ChartVisualization/blob/main/ice_cream_sales-bar_chart.png?raw=true)

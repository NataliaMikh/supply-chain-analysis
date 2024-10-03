# Supply Chain Analysis and Profit Prediction
### **Statistical Summary of Sales Data**
This dataset provides a comprehensive statistical overview of various attributes related to order processing and sales performance:
1. **Date Ranges:**
- ProcuredDate: Varies from December 31, 2017, to September 26, 2020.
- OrderDate: Ranges from May 31, 2018, to December 30, 2020.
- ShipDate: Spans from June 2, 2018, to January 24, 2021.
- DeliveryDate: Extends from June 7, 2018, to February 2, 2021.
2. **Sales Metrics:**
- SalesTeamID and CustomerID: Display a broad range of identifiers, with maximum values at 28 and 50, respectively, showing varied involvement across teams and customers.
- StoreID and ProductID: Vary significantly, with maxima of 367 and 47, pointing to a wide product range and numerous store locations involved.
3. **Order Details:**
- Order Quantity: Generally low (median at 5), with a maximum of 8, suggesting limits on order sizes or commonly purchased quantities.
- Discount Applied: Ranges from 0.05 to 0.4 with a median of 0.08, indicating typical discounting practices.
- Unit Cost and Unit Price: Show significant variability with maximums reaching $5498.56 and $6566.00 respectively, which highlights the diverse range of products and their pricing strategies.
- Delivery Time: Averages around 21 days, with a range from 3 to 38 days, which could indicate logistical challenges or efficiencies depending on the context.

### **Transactions distribution recorded under each sales channel:**
In-Store (3298) and Online (2425) channels dominate in popularity, significantly outpacing Distributor (1375) and Wholesale (893) channels. This disparity suggests a focused customer preference towards direct retail experiences, either physically in-store or via digital platforms, highlighting potential areas for targeted business development and resource allocation.
![Supply Chain Analysis Visualization](https://github.com/NataliaMikh/supply-chain-analysis/blob/main/viz/1.png?raw=true)

### **Profit Distribution for Different Sales Channels**
The pie chart shows that In-Store sales generate the largest share of profit (41.2%), followed by Online (29.4%). The visual analysis emphasizes the dominance of In-Store and Online channels in profitability, which suggests these areas are pivotal to the business's revenue strategy. Strategic investments in these channels could further enhance profitability and market position.
![Supply Chain Analysis Visualization](https://github.com/NataliaMikh/supply-chain-analysis/blob/main/viz/2.png?raw=true)

### **Average Delivery Time for Different Sales Channels**
The pie chart shows an even distribution of delivery times across these channels, each contributing around 24% to 25%. The bar chart reveals that all channels have a uniform average delivery time, consistently around 19 days. This uniformity suggests that delivery operations are standardized across all sales channels, which may indicate efficient logistical management.
![Supply Chain Analysis Visualization](https://github.com/NataliaMikh/supply-chain-analysis/blob/main/viz/3.png?raw=true)

### **Order Fulfillment Analysis by Warehouse and Sales Channel:**
The visuals illustrate the distribution of order fulfillment across various warehouses and the impact of different sales channels on each warehouse's operations. The first bar chart shows that WARE-NMK1003 processes the highest number of orders, followed by WARE-PUJ1005, indicating significant operational capacity at these locations. The second stacked bar chart breaks down the order counts from each warehouse by sales channel, revealing that while some warehouses, like WARE-UHY1004 and WARE-NMK1003, predominantly serve Online and In-Store channels, others like WARE-PUJ1005 have a more balanced distribution across all channels, including Distributor and Wholesale. This differentiation may suggest varying strategic focuses or market demands met by each warehouse.
![Supply Chain Analysis](https://github.com/NataliaMikh/supply-chain-analysis/blob/main/viz/4.png?raw=true)


### **Comparative Analysis of Profit Contribution by Warehouse:**
- The pie chart details the percentage contribution of each warehouse to total profits, with WARE-NMK1003 leading significantly at 31.7%, followed by WARE-PUJ1005 and WARE-UHY1004.
- The bar chart complements this by quantifying these profits, highlighting that WARE-NMK1003 not only leads in percentage but also in actual profit value, achieving the highest among the warehouses. This analysis indicates a varying efficiency and profitability among warehouses, which could guide strategic decisions regarding resource allocation, operational improvements, and potentially expanding capacities at higher-performing locations.
![Supply Chain Analysis Visualization](https://github.com/NataliaMikh/supply-chain-analysis/blob/main/viz/5.png?raw=true)

### **Total Profit by WarehouseCode and Sales Channel:**
This visualization illustrates the total profit generated by each warehouse segmented by different sales channels.
- Warehouse WARE-NMK1003 stands out significantly, showing the highest overall profit, predominantly driven by the Distributor channel. This indicates a strong performance in this channel specifically for WARE-NMK1003.
- Other warehouses like WARE-PUJ1005 and WARE-UHY1004 also perform well across multiple channels, particularly In-Store and Online, suggesting a diversified revenue stream.
- In contrast, WARE-MKL1006 and WARE-NBV1002 exhibit lower profit figures across all channels, which might highlight areas for operational review or strategic improvement. The data points to potential strengths and weaknesses in the sales and distribution strategy across different channels and warehouses.
![Supply Chain Analysis Visualization](https://github.com/NataliaMikh/supply-chain-analysis/blob/main/viz/6.png?raw=true)

### **Trend Analysis of Monthly Profits from May 2018 to December 2020:**
This line graph displays the fluctuation in monthly profits over a span from May 2018 to December 2020. The graph highlights a steep initial increase, peaking in July 2018, followed by significant variability, with notable peaks occurring roughly annually around July. The trend shows seasonal patterns with some dips and recoveries, suggesting impacts from external business cycles or seasonal sales activities. Overall, the graph indicates a relatively stable profit generation with periodic fluctuations that could inform future strategic planning and budgeting cycles.
![Supply Chain Analysis Visualization](https://github.com/NataliaMikh/supply-chain-analysis/blob/main/viz/7.png?raw=true)

### **Impact of Delivery Time on Profit Generation:**
The line graph illustrates how the delivery time impacts profit generation, highlighting a clear trend where shorter delivery times correlate with higher profits. The profit peaks when delivery time is around 20 days and then sharply declines as delivery time increases beyond this point. This suggests that efficiency in delivery processes is crucial for maximizing profit, and delays or extended delivery times could significantly reduce profitability. This analysis underscores the importance of optimizing logistics and delivery strategies to sustain or enhance profit margins.
![Supply Chain Analysis Visualization](https://github.com/NataliaMikh/supply-chain-analysis/blob/main/viz/8.png?raw=true)

### **Comparative Profit Analysis Across Sales Teams:**
The visualization reveals that the top-performing teams, like team 26, consistently generate higher profits compared to others. Teams are shown with a gradual decline in profit as we move from the left to the right of the chart, illustrating a significant variation in efficiency and effectiveness across teams. This sorted view allows for easy identification of standout teams and those that may require targeted improvements or further analysis to understand the discrepancies in performance.
![Supply Chain Analysis Visualization](https://github.com/NataliaMikh/supply-chain-analysis/blob/main/viz/9.png?raw=true)

### **Profit Distribution Across Products**
This bar chart presents the total profit generated by each product, sorted in descending order. Product 23 emerges as the highest profit generator, while the graph shows a gradual decrease in profit across subsequent products, with product 44 yielding the least. This visual distribution indicates the varying financial success of each product, which could be critical for strategic decisions regarding inventory management, marketing focus, and product development. Identifying top performers and underperformers enables the company to allocate resources more efficiently and potentially adjust product lines to maximize overall profitability.
![Supply Chain Analysis Visualization](https://github.com/NataliaMikh/supply-chain-analysis/blob/main/viz/10.png?raw=true)

### **Analysis of Delivery Time Versus Profit with Order Quantity as a Factor**
The scatter plot illustrates the relationship between delivery time and profit, with the size of each point representing the order quantity. The distribution of data points suggests that while there are variations in profit at different delivery times, the overall trend, indicated by the flat red trendline, shows no significant correlation between delivery time and profit. Notably, most transactions, regardless of delivery time, cluster around lower profit margins. This analysis implies that while delivery efficiency does not directly impact profit levels, the size of the order (as visualized by the size of the dots) varies significantly, which might affect profitability on a per-order basis. Businesses could leverage this insight to optimize delivery processes or adjust order management strategies to enhance profitability
![Supply Chain Analysis Visualization](https://github.com/NataliaMikh/supply-chain-analysis/blob/main/viz/11.png?raw=true)

### **Predictive Modeling: LGBMRegressor:**
- **Objective:**
The model is designed to predict the 'Profit' based on various cleaned and encoded features from the dataset, aiming to understand the contributing factors to profitability and optimize resource allocation accordingly.
- **Results:**
R2 Score: This metric is used to measure the proportion of variance in the dependent variable that is predictable from the independent variables. The specific R2 score would tell us how well the unseen data is being predicted by the model.
Residual Plot: The plot provided is instrumental in identifying the variance of residuals against the predicted values. A tightly clustered group around the zero line suggests that the model has a decent fit for the data, although there are some outliers, indicating instances where the model’s predictions deviate significantly from actual values.
![Supply Chain Analysis Visualization](https://github.com/NataliaMikh/supply-chain-analysis/blob/main/viz/12.png?raw=true)


**Model's training and evaluation Summary:**
This model's training and subsequent evaluation reveal how effectively it can predict profit based on company data. The R2 score and residual plot are crucial for understanding model performance and reliability, guiding further refinements to enhance predictive accuracy. The described steps not only demonstrate the model's capabilities but also set the stage for potential operational improvements based on predictive insights.
![Supply Chain Analysis Visualization](https://github.com/NataliaMikh/supply-chain-analysis/blob/main/viz/13.png?raw=true)

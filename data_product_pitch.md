Manufacturing Margin and Cost Calculator (Pitch Deck)
========================================================
author: Wei Hsien Yeh 
date: March 27, 2016

Overview
========================================================

This application helps manufacturers calculate the actual profit of production by considering losses due to unplanned downtimes, speed loss, and products with unacceptable quality.

- App could be found at: https://whyeh.shinyapps.io/data_product/
- Code files could be found at: https://github.com/whyeh/Coursera-Data-Product-Project

Inputs
========================================================

- Labour Hourly Rate: Wage of operators
- Hourly Indirect Burden: Operation cost in each operating hour
- Product Price to Customer: (for this inquiry)
- Material Cost: (for this inquiry)
- Direct Burden per Part: Product cost other than material
- # of Operators Assigned: Operators worked on this inquiry
- Theoretical Output CT (in sec): Frequency of production
- Total Duration (in minutes): Duration of job for this inquiry
- # of Product Produced: Pieces/Units produced for this inquiry
- Planned Downtime (in minutes): e.g. lunch, break, meeting
- Unplanned Downtime (in minutes): e.g. machine breakdown 
- # of NG Outputs: Pieces/Units discarded due to poor quality 

Outputs
========================================================

Waterfall Chart:  
Reads from left to right -- first bar of the chart shows the revenue of the job as calculated by the number of pieces made and their unit cost.  Then, the cost of production and other losses are subtracted from Revnue to obtain Net Profit.

Table:  
In this table, negative values indicate money lost whereas positive values indicate money gained (e.g. for Difference from Expected Profit, negative value means that the actual profit is less than expected).  

Example Result
========================================================
Here are information you could get from this app!  


```
            Result   Values Percent.of.Revenue
1          Revenue  4412.64             100.00
2    Expected Cost -3743.92              84.85
3  Expected Profit   710.48              16.10
4 Additional Costs  -388.58               8.81
5   Actual Profits   280.14               6.35
```

From this app, you could clearly see what is the actual profit from a manufacturing job.  You will be able to gain insights to additional costs so you could focus on improvement plans to maximize your profit.  You will not need to include crazy overhead in your budget ever again!

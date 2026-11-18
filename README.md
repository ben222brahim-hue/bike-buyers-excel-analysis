Bike Buyers – Excel Data Analysis

An Excel project analyzing customer data to understand who buys bikes and why, using data cleaning, formulas, pivot tables, and a dashboard.

🎯 Goal

Find which customer characteristics are linked to buying a bike, so a business could target the right customers.

📊 Dataset

1,000 customer records including marital status, gender, income, children, education, occupation, home ownership, number of cars, commute distance, region, age, and whether they purchased a bike.

🛠️ What I did
Data cleaning: standardized categorical values (e.g. abbreviations like M/F converted to full text)
Calculated fields: used IF formulas to segment customers into age brackets
Pivot tables: summarized customer demographics and purchase behavior across multiple dimensions (income, age, region)
Dashboard: built charts to visualize key trends in the data
📈 Results

Overall, 48.1% of the 1,000 customers bought a bike. Purchase rate by segment:

Segment	Group	Purchase rate	Customers
Region	Pacific	58.9%	192
Region	Europe	49.3%	300
Region	North America	43.3%	508
Cars owned	0 cars	61.1%	247
Cars owned	2+ cars	35.6% – 38.8%	486
Commute distance	2–5 miles	58.6%	162
Commute distance	more than 10 miles	29.7%	111
Marital status	Single	54.1%	462
Marital status	Married	42.9%	538
Education	Bachelors	55.2%	306
Education	Partial High School	26.3%	76
Key insights
Customers with fewer cars buy more bikes. Those with 0 or 1 car buy at 57–61%, versus about 36–39% for those with 2 or more cars.
Long commutes lower the purchase rate. Customers commuting more than 10 miles buy at 29.7%, versus 54.6% for those within 1 mile.
Pacific is the strongest region (58.9%), and North America the weakest (43.3%) despite having the most customers.
Singles buy more than married customers (54.1% vs 42.9%).
Income is only weakly linked to buying. Buyers earn on average about $58,000 versus $55,000 for non-buyers, so income alone doesn't explain the decision.
Gender and home ownership make almost no difference (each within 2 points).
Possible business use

Marketing could focus on single customers with few cars in the Pacific region, and on shorter commute distances, rather than targeting by income.

Limits

This is a sample of 1,000 customers and the analysis only shows correlations, not causes. Some groups are small (for example, 76 customers in Partial High School), so those rates are less reliable.

Dashboard

🧰 Tools

Microsoft Excel — formulas (IF), pivot tables, charts/dashboard

📁 Files
Excel_Project_Dataset.xlsx — the full workbook (raw data, cleaned data, pivot tables, dashboard)
dashboard.png — screenshot of the dashboard
📚 What I learned

This was my first end-to-end data project: importing raw data, cleaning it, transforming it with formulas, summarizing it with pivot tables, and visualizing it on a dashboard.

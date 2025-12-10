Coffee Sales Dataset
Coffee Sales Transaction Dataset

https://www.kaggle.com/datasets/navjotkaushal/coffee-sales-dataset

About Dataset
This dataset contains coffee shop transaction records, including details about sales, payment type, time of purchase, and customer preferences.
It is specifically curated for data visualization, dashboard building, and business analytics projects in tools like Power BI, Tableau, and Python visualization libraries (Matplotlib, Seaborn, Plotly).

With attributes covering time of day, weekdays, months, coffee types, and revenue, this dataset provides a strong foundation for analyzing customer behavior, sales patterns, and business performance trends.

Dataset Structure-

File format: CSV
Columns (features):

hour_of_day → Hour of purchase (0–23)

cash_type → Mode of payment (cash / card)

money → Transaction amount (in local currency)

coffee_name → Type of coffee purchased (e.g., Latte, Americano, Hot Chocolate)

Time_of_Day → Categorized time of purchase (Morning, Afternoon, Night)

Weekday → Day of the week (e.g., Mon, Tue, …)

Month_name → Month of purchase (e.g., Jan, Feb, Mar)

Weekdaysort → Numeric representation for weekday ordering (1 = Mon, 7 = Sun)

Monthsort → Numeric representation for month ordering (1 = Jan, 12 = Dec)

Date → Date of transaction (YYYY-MM-DD)

Time → Exact time of transaction (HH:MM:SS)

Potential Data Visualizations-

This dataset is well-suited for interactive dashboards and visual reports, such as:

📊 Sales by Coffee Type (e.g., top-selling drinks)

⏰ Sales by Hour of Day (peak business hours)

🌅 Sales by Time of Day (Morning vs Afternoon vs Night trends)

📅 Sales by Weekday & Month (seasonal & weekly demand patterns)

💳 Payment Method Breakdown (cash vs card usage)

📈 Revenue Trends Over Time (daily/monthly growth analysis)

Use Cases-

* Power BI / Tableau dashboards
* Python data visualization (Matplotlib, Seaborn, Plotly)
* Data storytelling projects
* Business intelligence & decision-making simulations
* Training projects for beginners in data visualization & analytics


no 4 ada fungsi untuk membuat chart
no 5 ada error di :
fig = px.sunburst(df, path=['Time_of_Day', 'coffee_name'], values='money',
                 title='Revenue Hierarchy: Time of Day > Coffe',
                 color='Time_of_Day')
fig.update_layout(margin=dict(l=20,r=20,t=60,b=20))
fig.show()
====================

download contoh kode baru sampai "Prepared Coffee Sales Data for SQL Analysis"


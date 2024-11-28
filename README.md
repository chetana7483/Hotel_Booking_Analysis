Hotel Booking Analysis
Overview
This project analyzes hotel booking data to identify trends, cancellations, and other key insights using Python. The data includes various features such as booking cancellations, average daily rates, and hotel types.

Features
Data Exploration:

View dataset rows (head, tail).
Check dataset shape, column names, and info.
Detect and handle missing values.
Data Cleaning:

Remove unnecessary columns (company, agent).
Drop rows with missing values.
Replace numeric cancellation values (0/1) with labels (not canceled, canceled).
Visualizations:

Bar charts for cancellation counts.
Trends in average daily rates (ADR) by hotel type and month.
Pie charts for top countries with cancellations.
Monthly cancellation trends for City and Resort Hotels.
How to Use
Requirements:

Python 3.x
Libraries: pandas, matplotlib, seaborn
Run the Script:

Load your hotel_bookings.csv file.
Execute the script to view insights and visualizations.
Key Insights
Cancellation Analysis:

Proportion of canceled vs. not canceled bookings.
Top 10 countries with the most cancellations.
Hotel Type Analysis:

Comparison of City and Resort Hotels in terms of ADR and cancellation rates.
Seasonal Trends:

Monthly ADR trends.
Cancellations by month for each hotel type.
Sample Visualizations
Reservation Status: A bar chart showing the count of canceled vs. not canceled bookings for each hotel type.
Average Daily Rate (ADR): Line charts and bar charts comparing ADR trends across months and hotel types.
Top Countries with Cancellations: A pie chart displaying the top 10 countries.

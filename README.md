Music Store Database Analysis Project

Overview
This project involves analyzing a music store database to derive insights and answer various business-related questions. 
The database contains tables related to employees, customers, invoices, tracks, genres, and artists.

All the SQL queries provided for the music store database analysis project:

Senior Most Employee by Job Title:
Identifies the employee with the highest job title level.
Orders employees by their job title levels in descending order and selects the top one.

Countries with Most Invoices:
Lists the top 10 countries with the highest number of invoices.
Groups invoices by billing country, counts the number of invoices for each country, and orders the results in descending order of invoice count.

Top 3 Values of Total Invoice:
Retrieves the top 3 total invoice values.
Orders invoices by total amount in descending order and selects the top 3.

City with the Best Customers:
Determines the city with the highest sum of invoice totals.
Groups invoices by billing city, calculates the total invoice amount for each city, and selects the city with the highest total.

Best Customer:
Determines the customer who has spent the most money.
Joins customer and invoice tables, calculates the total amount spent by each customer, and selects the customer with the highest total spending.

Rock Music Listeners:
Retrieves the email, first name, last name, and genre of all Rock music listeners.
Joins multiple tables (customer, invoice, invoice_line, track, genre) to filter customers who have purchased Rock music.

Top Rock Bands:
Lists the top 10 rock bands based on the total number of rock songs they have written.
Joins track, album, artist, and genre tables to identify rock songs and group them by artist.

Longest Tracks:
Retrieves all track names and lengths longer than the average song length.
Compares track lengths to the average track length using a subquery and selects tracks with longer durations.

Customer Spending on Artists:
Calculates how much each customer has spent on the best-selling artist.
Uses a common table expression (CTE) to identify the best-selling artist, then calculates the amount spent by each customer on that artist.

Most Popular Genre by Country:
Determines the most popular music genre for each country based on the highest amount of purchases.
Groups invoice lines by country and genre, counts the number of purchases for each combination, and selects the most popular genre for each country.

Top Spending Customers by Country:
Finds the customer that has spent the most on music for each country.
Groups invoices by customer and country, calculates the total spending for each customer in each country, and selects the top spender for each country.

Conclusion:
These SQL queries cover a wide range of analyses, including identifying top performers, understanding customer behavior, 
and determining popular music genres. 
They provide valuable insights into the music store database.
Analyzing the music store database provides valuable insights that can inform business decisions, marketing strategies, 
and customer engagement initiatives. 

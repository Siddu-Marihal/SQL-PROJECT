
# Overview
This project is focused on analyzing data from a music store to gain insights into various aspects such as customer spending, employee roles, music genres, and artist performance. The goal of this analysis is to explore different SQL queries and techniques to extract meaningful information from the store's database, focusing on customers, artists, sales, and geographical trends.

# Tools Used
- SQL (Structured Query Language): For querying and manipulating the database.
- PostgreSQL (depending on your environment): The database management systems used to run the SQL queries.
- Database Schema: A relational database containing information about customers, invoices, employees, tracks, genres, and artists.

# Questions Answered
## Question Set 1 - Easy

1. Who is the senior most employee based on job title?
2. Which countries have the most invoices?
3. What are the top 3 values of total invoice?
4. Which city has the best customers? Write a query that returns the city with the highest sum of invoice totals.
5. Who is the best customer? Identify the customer who has spent the most money.

## Question Set 2 - Moderate

1. Rock Music Listeners: Return the email, first name, last name, and genre of all rock music listeners. List them alphabetically by email.
2. Top Rock Artists: Identify the top 10 rock artists who have written the most songs.
3. Longer-than-Average Songs: Return all track names with a song length longer than the average, ordered by song length (longest first).

## Question Set 3 - Advanced

1. Amount Spent by Customers on Artists: Return the customer name, artist name, and total amount spent on the artist.
2. Most Popular Music Genre per Country: Identify the most popular music genre in each country based on purchases.
3. Top Customer per Country: Return the top customer for each country based on spending.

# Challenges Faced

- Handling Large Datasets: Querying large datasets with multiple joins and groupings required optimization techniques like indexing and careful query design.
- Complex Joins and Subqueries: Some questions required nested queries and joining multiple tables, which was challenging but provided a deeper understanding of SQL.
- Data Integrity: Ensuring that the data used for analysis was clean and free of inconsistencies was an essential part of the process.
- Performance Optimization: Some queries took longer to execute, which led me to focus on optimizing the performance by using appropriate indexes and restructuring queries.

# Conclusions

This project helped me refine my SQL skills, particularly in the areas of data aggregation, complex joins, subqueries, and performance optimization. It also provided valuable insights into the music industry, highlighting trends in customer behavior, music preferences, and the economic impact of certain artists and genres. Through this analysis, I gained a deeper understanding of how to derive actionable insights from relational databases.
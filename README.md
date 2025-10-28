Films Revenue Analysis Using SQL and Tableau
Overview

This project explores film rental performance using data from the Sakila Database, focusing on key metrics such as category revenue, rental frequency, and regional trends. The analysis combines data warehousing with SQL and visual analytics with Tableau to identify insights into business performance, customer demand, and content profitability.

The study provides a structured data mart, generates analytical queries, and visualizes business outcomes through interactive Tableau dashboards.

Schema and Data Integration

The Sakila database was used as the foundation to design a film-focused data warehouse.
Multiple relational tables were integrated into a consolidated summary table named film_summary, enabling cross-sectional analysis across categories, rentals, and geographies.

Schema Diagram

Joined Tables

The warehouse integrates data from:

film, category, rental, payment, inventory, and customer

Additional links with actor, city, and country tables
This integration supports full traceability of film performance from inventory to revenue.

SQL Analysis

A series of analytical SQL queries were developed to address core business questions, including:

Which film categories generate the highest revenue?

What are the top-performing films by total revenue and rentals?

Which actors appear in the most profitable films?

Which countries and cities contribute the most to revenue?

How do rental trends vary over time and across genres?

What revenue differences exist between low, medium, and high-budget films?

These insights were exported as clean datasets and visualized through Tableau.

Visual Insights
Top 5 Revenue-Generating Categories

High-performing categories such as Sports, Sci-Fi, and Animation led revenue generation, reflecting audience demand for dynamic and visually rich content.

Top 10 Revenue-Generating Films

Analysis highlighted consistent outperformance by a select group of films across multiple regions, showing strong brand and cast influence on earnings.

Top Actors by Film Revenue

Certain actors showed a significant impact on sales, appearing repeatedly in high-grossing titles, emphasizing the link between casting strategy and commercial success.

Top 10 Countries by Revenue

Revenue concentration was highest in India, China, and the United States, indicating markets with the greatest rental activity and customer engagement.

Most Rented Films by Category

The rental analysis revealed diverse consumer preferences, with family and comedy titles consistently achieving higher rental frequency.

Highest-Grossing Film per Category

Across all genres, select titles consistently achieved both high revenue and strong rental volumes, confirming balanced demand across pricing tiers.

Top Rental Cities

Urban areas demonstrated higher engagement rates, aligning with digital infrastructure and local content demand.

Revenue by Budget Category

High-budget films performed better globally, validating the return potential on premium content investments.

Geographic Revenue Distribution

Revenue distribution visualization identified global rental hubs, reflecting the broad reach and cross-cultural consumption of entertainment content.

Monthly Rental Trends by Category

Rental activity peaked mid-year, indicating seasonal engagement patterns likely influenced by holidays and regional trends.

Rental Performance by Genre

The analysis demonstrated that Sports, Family, and Action films achieved the highest rental frequencies, showing balanced cross-category demand.

Top 5 Most Rented Films

Films such as Rocketeer Mother and Bucket Brotherhood dominated rentals, reinforcing strong audience appeal and accessibility.

Tableau Dashboard


The final dashboard integrates all visual elements to support exploratory analysis and business presentation.
View Tableau Dashboard (Public Link)

Key Insights

High-budget productions dominate total revenue, yet mid-budget films remain competitive in volume.

Global rental demand is concentrated in high-population markets with digital accessibility.

Certain actors and film genres consistently outperform others, suggesting targeted investment opportunities.

Temporal trends reveal opportunities for promotional campaigns during rental peaks.

The integration of data warehousing and visualization demonstrates effective end-to-end analytics capability.

Project Files
Folder	Description
data/	Cleaned datasets used for visualization
sql/	SQL scripts for schema, joins, and analytical queries
tableau/	Tableau workbook (.twb)
images/	Visual outputs and dashboards
reports/	Final report and supporting documentation
Conclusion

This project demonstrates the practical application of data warehousing, SQL analysis, and Tableau visualization in transforming raw transactional data into actionable business insights. The findings support data-driven decision-making in content acquisition, pricing strategies, and global market targeting.

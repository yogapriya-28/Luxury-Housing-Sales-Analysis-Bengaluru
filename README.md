# Luxury-Housing-Sales-Analysis-Bengaluru
Build a complete real estate analytics solution using Python for advanced data cleaning, loaded the refined dataset into a SQL database, and used Power BI to directly connect to SQL and build a dashboard.  It replicates a real-world enterprise-level data pipeline, handling 100,000+ property records and generating actionable business insights for developers, investors, and real estate analysts.

Workflow
------------
 Step 1: Python – Data Cleaning & Feature Engineering
 -------------------------------------------------------

Load raw CSV with property transactions.

Clean inconsistent formats (e.g., Ticket_Price_Cr).

Handle null values (Amenity_Score, Booking_Status, etc.).

Normalize text fields (Builder, Micro_Market).

Derive additional columns:

Price_per_Sqft

Quarter_Number

Booking_count

Output: Cleaned CSV/DataFrame ready for database insertion.



 Step 2: SQL – Load Clean Data into RDBMS
 -------------------------------------------------------------------

Create appropriate table schema (property_transactions).

Insert cleaned data into MySQL using Python (SQLAlchemy).



 Step 3: Power BI – Interactive Dashboard
 ----------------------------------------------

Connect Power BI to SQL database.

Build relationships 

Create interactive dashboards with:

Filters: Builder, Quarter, Micro_Market

Map visuals & geospatial insights

Card visuals for top five performance

Insights from Buyer_Comments




Outcome
-----------------

Cleaned & structured dataset ready for analytics.

Interactive Power BI dashboards for real-time insights.

Actionable business intelligence enabling data-driven decisions in the real estate sector.

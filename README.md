# Luxury-Housing-Sales-Analysis-Bengaluru
This project demonstrates an end-to-end real estate analytics solution for Bengaluru’s luxury housing market using Python, SQL, and Power BI. It replicates a real-world enterprise-level data pipeline, handling 100,000+ property records and generating actionable business insights for developers, investors, and real estate analysts.

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

Build relationships and DAX calculations.

Create interactive dashboards with:

Filters: Builder, Quarter, Micro_Market

Map visuals & geospatial insights

KPIs for Booking Conversion

Insights from Buyer_Comments


Future Scope
---------------------

Predictive Analytics: Forecast housing prices & demand trends.

Sentiment Analysis: Analyze buyer comments using NLP.

Geospatial Insights: Advanced location-based investment analysis.

Automated Dashboards: Real-time data integration via APIs.

Recommendation Systems: Personalized property suggestions.

Scalability: Expand to pan-India luxury housing markets.



Outcome
-----------------

Cleaned & structured dataset ready for analytics.

Interactive Power BI dashboards for real-time insights.

Actionable business intelligence enabling data-driven decisions in the real estate sector.

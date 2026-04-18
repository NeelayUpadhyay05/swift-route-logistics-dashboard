# Swift Route Logistics Dashboard

## Project Overview

This Power BI project provides a comprehensive, end-to-end analysis of **Swift Route Logistics** ,
a real-time logistics company. The dashboard suite is designed to monitor and optimize the
movement of goods by tracking key performance indicators (KPIs) across hubs, drivers, and
vehicles.
The project transforms over 28,000 rows of raw transactional data into actionable insights,
helping stakeholders identify bottlenecks, manage hub capacity, and improve delivery timelines.

## Key Features

● Four-Page Interactive Suite: Includes Executive Overview, Hub Analysis, Driver Profiling,
and Vehicle Fleet tracking.

● Dynamic Reporting: Uses DAX-driven titles and summaries that update automatically
based on user filters (e.g., specific month or driver selection).

● Advanced Visualizations: Custom-built star ratings for drivers using DAX and heatmaps
for hub processing daily trends.

● Time-Intelligence: Real-time Month-on-Month (MoM) growth tracking for all major KPIs
(Total Orders, OTD, CSAT, Delivery Time).

## Tech Stack

● Power BI Desktop: Core platform for visualization and reporting.

● Power Query: Used for data cleaning, transformation, and schema normalization.

● DAX (Data Analysis Expressions): Utilized for complex measures, time-intelligence, and
dynamic visual logic.

● Data Modeling: Star Schema architecture consisting of one Fact table (Orders) and four
Dimension tables (Drivers, Hubs, Vehicles, and Date).

## Dashboard Breakdowns

### 1. Executive Overview

Focuses on core business health through four primary KPIs:

● **Total Orders:** Monitoring volume and MoM growth.

● **On-Time Delivery (OTD) Rate:** Tracking the percentage of packages delivered within the
estimated window.

● **Customer Satisfaction (CSAT):** Analyzing ratings to measure service quality.

● Average Delivery Time: Measuring the speed of the logistics network in hours.

### 2. Hub Analysis

Provides deep-dives into the central distribution nodes:

● **Capacity vs. Actuals:** Identifies which hubs are underutilized or operating over capacity.

● **Daily Processing Trends:** A heatmap analyzing processing times from Monday to Sunday
to identify peak congestion days.

### 3. Driver Profile

A granular view of human resource performance:

● **Individual Metrics:** Tracking tenure, total deliveries made, and average ratings.

● **Performance Visualization:** A dynamic star-rating system that updates based on the
selected driver’s recent scores.

### 4. Vehicle Overview

Monitoring the reliability of the fleet:

● **Age vs. Breakdown:** A scatter plot identifying the correlation between vehicle age and
maintenance frequency.

● **Fleet Status:** Monitoring "Active" vs. "Under Maintenance" vehicles to ensure operational
readiness.

## Repository Contents

● Swift Route Logistics Dashboard.pbix: The primary Power BI project file.

● Project Document.docx: Detailed project report including problem statements and tech
stack.

● Data/: Folder containing the raw CSV datasets used for the analysis.

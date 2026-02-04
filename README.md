# DataAnalysis-with-pyspark
The deliverable is a PySpark notebook that loads and processes a large NYC taxi dataset using distributed computing. It includes data cleaning, feature engineering, scalable aggregations, and business insights derived from big data processing.
#  NYC Taxi Trip Data Analysis (2018)

##  Project Overview

This project analyzes large-scale NYC taxi trip data from 2018 using
scalable data processing techniques. The goal is to clean, transform,
and analyze millions of trip records efficiently and extract meaningful
insights related to demand patterns, revenue trends, tipping behavior,
and location-based activity.

The analysis demonstrates the use of **big data concepts with PySpark**
to handle high-volume datasets that are not suitable for traditional
single-machine processing.

------------------------------------------------------------------------

##  Tools & Technologies

-   **Big Data Processing:** PySpark
-   **Querying & Analysis:** SQL, Python
-   **Data Cleaning & Transformation:** PySpark DataFrame APIs
-   **Environment:** Google colab

------------------------------------------------------------------------

##  Dataset Description

The dataset consists of NYC taxi trip records and zone-level geographic
data: - Taxi trip transaction data (pickup/drop-off time, fare, tips,
payment type) - Taxi zone lookup data (zone name, borough) - Large
dataset size suitable for distributed processing

------------------------------------------------------------------------

##  Data Cleaning & Preprocessing

The following data cleaning steps were performed at scale: - Removed
duplicate trip records - Handled missing and null values - Corrected
data types for numeric and timestamp columns - Filtered invalid records
such as negative fares or distances - Standardized categorical values
for consistency

------------------------------------------------------------------------

##  Key Analysis & Insights

###  Trips by Hour of Day

-   Lowest demand observed between **2 AM -- 5 AM**
-   Peak demand occurs during **afternoon and evening hours (2 PM -- 6
    PM)**
-   Trip volume strongly aligns with daily commute patterns

------------------------------------------------------------------------

###  Average Fare by Hour

-   Higher average fares during **early morning** and **late afternoon**
-   Indicates longer trips and traffic congestion during peak hours

------------------------------------------------------------------------

###  Peak Days of the Week

-   **Friday and Saturday** have the highest trip volumes
-   **Sunday** shows the lowest activity

------------------------------------------------------------------------

###  Top Pickup & Drop-off Locations

-   **LaGuardia Airport** is the most frequent pickup location
-   Other hotspots include **JFK Airport, Times Square, and Midtown
    Manhattan**
-   Manhattan dominates both pickups and drop-offs

------------------------------------------------------------------------

###  Revenue by Payment Type

-   **Credit card payments** generate the highest average total fare
-   Digital payments are associated with higher-value trips

------------------------------------------------------------------------

###  Tip Behavior Analysis

-   Higher tip percentages during **early morning** and **evening
    commute hours**
-   Tip behavior varies significantly by time of day

------------------------------------------------------------------------

###  Zone-Level Insights

-   Airport zones and major business districts generate the highest
    demand
-   Taxi activity is highly concentrated in Manhattan

------------------------------------------------------------------------

##  Business Takeaways

-   Taxi demand follows strong **time-based and location-based
    patterns**
-   Airports and peak commute hours are key revenue drivers
-   Distributed data processing enables efficient large-scale analytics

------------------------------------------------------------------------

##  Future Enhancements

-   Add advanced PySpark optimizations
-   Automate end-to-end data pipelines
-   Integrate machine learning for demand forecasting
-   Deploy dashboards for real-time analytics

------------------------------------------------------------------------

##  Author

**Chethan Gowda**

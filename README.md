[README.md](https://github.com/user-attachments/files/34588764/README.md)
# Riding Analysis -- Riding App Data Analytics

An interactive **Power BI** project that analyzes riding-app booking,
ride, vehicle, revenue, cancellation, and customer-rating data. The
dashboard is designed to turn booking-level data into operational KPIs
and business insights.

## Project Overview

The report explores how rides perform across the year, which vehicle
categories contribute to ride distance, how customers pay, and where
cancellations occur. It also provides views of customer retention,
service quality, peak-hour activity, and ratings.

**Analysis period shown in the dashboard:** 1 January 2024 -- 30
December 2024.

## Key Dashboard Metrics

  Metric                           Reported value
  ------------------------------ ----------------
  Total bookings                         148.767K
  Completed rides                         92.551K
  Cancelled bookings                      37.427K
  Cancellation rate                        25.00%
  Total ride distance                   2,418.05K
  Average ride distance                     26.00
  Customer retention rate                  30.24%
  Premium peak-hours indicator             72.53%
  Service Quality Score                     77.05

*Values are transcribed from the dashboard screenshots. K denotes
thousands. The dashboard's displayed figures and definitions should be
treated as the source of truth.*

## Dashboard Sections

The report contains navigation for the following views:

1.  **Homepage / Booking Overview**
    -   Booking-status distribution.
    -   Monthly booking trend.
    -   Date-range filtering.
2.  **360° View**
    -   A broader view of ride activity and booking performance.
3.  **Vehicle Type Analysis**
    -   Completed, incomplete, and total rides by vehicle category.
    -   Total and average ride distance by vehicle category.
    -   Comparison across Auto, Go Mini, Go Sedan, Bike, Premier Sedan,
        eBike, and Uber XL.
4.  **Revenue Analysis**
    -   Booking value by payment method.
    -   Ride-distance and revenue trends by month.
    -   Revenue distribution across customer/revenue tiers.
    -   Day-part and distance-category comparisons.
5.  **Cancellation Analysis**
    -   Cancelled rides by customer cancellation reason.
    -   Cancelled rides by driver cancellation reason.
    -   Cancellation KPIs.
6.  **Review Analysis**
    -   Driver ratings and customer ratings by vehicle category.
    -   Comparison of rating totals across vehicle types.
7.  **Summary**
    -   Service-quality and customer-retention indicators.
    -   Weekly and monthly booking patterns.
    -   Peak-hour, day-part, and revenue-per-kilometre analysis.

## Selected Findings from the Dashboard

-   Auto has the highest displayed total ride distance among the vehicle
    categories, at **601.79K**.
-   Go Mini records **482.09K** in total ride distance, followed by Go
    Sedan at **433.20K**.
-   UPI is the largest payment method by displayed booking value,
    followed by Cash.
-   The dashboard reports a **25.00%** cancellation rate and separates
    customer-side and driver-side cancellation reasons.
-   The displayed average ride distance is **26.00**.

These are descriptive observations from the dashboard; they do not
establish the causes of booking or cancellation patterns.

## Tools

-   **Microsoft Power BI** -- interactive report and data visualization.

## How to Explore the Report

1.  Open the Power BI report.
2.  Use the navigation buttons to move between dashboard sections.
3.  Apply the date-range slicer to focus on a selected period.
4.  Compare KPIs, vehicle categories, payment methods, monthly trends,
    cancellations, and ratings.
5.  Select chart elements where supported to explore cross-filtered
    results.

The filenames above are suggested organization only. Include the PBIX,
dataset, and screenshots only if you have permission to share them.

## Notes

-   The dataset source and exact data dictionary were not provided with
    the dashboard screenshots, so this README does not make claims about
    the original data source or individual column definitions.
-   KPI names and values are reproduced as displayed. Confirm their
    underlying DAX definitions and units before using them in formal
    business reporting.
-   Do not publish confidential, personal, or licensed dataset
    information in a public repository.

## Author

**Harsh Bhagat**

-   GitHub: [CyberGuyHarsh](https://github.com/CyberGuyHarsh)

# Hotel Booking Analysis

## Project Overview

This project analyzes hotel booking data to understand booking trends, cancellation behaviour, customer patterns, and hotel performance using Tableau.

The analysis focuses on comparing City Hotels and Resort Hotels, identifying factors associated with cancellations, understanding booking channel performance, and presenting business insights through interactive dashboards.

## Objective

The main objectives of this project are:

* Analyze overall hotel booking performance
* Compare booking and cancellation patterns across City Hotels and Resort Hotels
* Understand the relationship between lead time and cancellations
* Analyze booking patterns across market segments and distribution channels
* Study average daily rate (ADR) and length of stay
* Build interactive dashboards to support data-driven business decisions

## Dataset

The dataset contains 119,390 hotel booking records covering City Hotels and Resort Hotels.

The dataset includes information such as:

* Hotel type and booking details
* Arrival dates and lead time
* Length of stay and number of guests
* Cancellation status
* Deposit type
* Market segment and distribution channel
* Customer type
* Average daily rate (ADR)

The data was prepared in Excel before being analysed in Tableau.

## Tools Used

* Tableau
* Microsoft Excel
* GitHub

## Analysis Performed

* Total bookings analysis
* Cancellation rate analysis
* Monthly booking trend analysis
* Hotel type comparison
* Average ADR analysis
* Average stay duration analysis
* Cancellation rate by lead time
* Cancellation rate by deposit type
* Booking volume by market segment
* Cancellation rate by market segment
* Cancellation rate by customer type
* Booking volume and cancellation analysis by distribution channel
* Booking analysis by stay duration

## Key Performance Indicators

* **Total Bookings:** 119,390
* **Cancellation Rate:** 37.04%
* **Average ADR:** €103.53
* **Average Stay Duration:** 3.43 nights

The average ADR was calculated using positive ADR values only.

## Dashboards Created

### Hotel Booking Overview

This dashboard provides an overview of hotel booking performance, including:

* Key performance indicators
* Monthly booking trends
* Bookings by market segment and hotel type
* Bookings by distribution channel
* Bookings by stay duration
* Average ADR by hotel type
* Average stay duration by hotel type

### Cancellation Intelligence

This dashboard focuses on cancellation behaviour across different booking characteristics, including:

* Cancellation rate by hotel type
* Cancellation rate by lead time
* Cancellation rate by deposit type
* Cancellation rate by market segment
* Cancellation rate by customer type
* Cancellation rate by distribution channel

Both dashboards include a hotel-type filter to compare City Hotels and Resort Hotels.

## Key Findings

* The overall cancellation rate was 37.04%.
* City Hotels recorded a cancellation rate of 41.7%, compared with 27.8% for Resort Hotels.
* Bookings made 90 or more days before arrival had a cancellation rate of 50.65%.
* Bookings made 0–7 days before arrival had a cancellation rate of 9.63%.
* Online Travel Agents generated the highest booking volume, with 56,477 bookings.
* The average stay was 4.32 nights at Resort Hotels and 2.98 nights at City Hotels.
* The Non Refund deposit category showed a cancellation rate of 99.4%, which requires further validation against the underlying records.

## Business Recommendations

* Monitor bookings made well in advance to understand cancellation patterns.
* Analyse City Hotels and Resort Hotels separately due to differences in cancellation rates and stay duration.
* Validate deposit-type records before making changes to cancellation policies.
* Evaluate booking channels using booking volume, cancellation rates, and revenue wherever available.
* Use interactive dashboards for regular monitoring of booking performance.

## Repository Contents

* `Hotel_Booking_Analysis.twb` — Tableau workbook containing the dashboards and visualisations
* `data/hotel_booking_data` — Hotel booking dataset used for analysis
* `Hotel_Booking_Analysis_Project_Report.docx` — Project findings and recommendations report
* `Screenshots/` — Dashboard screenshots, if included
* `README.md` — Project documentation

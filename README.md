# rain-or-ride-excel-analysis
Excel dashboard analysing Seoul bike rentals by hour, month, season and rainfall, using 8,760 real records, basic formulas and charts.
# Rain or Ride? 

## Bike Rental Analysis Using Excel

## About This Project

This project studies bike rentals in Seoul, South Korea. I used Excel to understand how rentals change by hour, month, season and rainfall.

## Dataset

* **Source:** [UCI Machine Learning Repository](https://doi.org/10.24432/C5F62R)
* **Total rows:** 8,760
* **Time period:** December 2017 to November 2018
* Each row contains one hour of bike rental and weather information.

## Questions Explored

* Which hour has the most bike rentals on average?
* Which month has the highest total rentals?
* Which season has the highest average demand?
* How do rentals differ during rainy and non-rainy hours?

## Data Cleaning

* Formatted dates and numbers.
* Checked for missing values and duplicate records. None were found.
* Kept all records, but left out hours when the service was closed from demand calculations.

## Excel Skills Used

* SUM, SUMIFS, COUNTIFS and AVERAGEIFS
* INDEX and MATCH
* Sorting and filtering
* Conditional formatting
* Charts and dashboard creation

## Main Findings

* Total bike rentals were **6,172,314**.
* **6 PM** was the busiest hour on average.
* **June 2018** had the highest monthly rentals.
* **Summer** had the highest average rentals per operating hour.
* Rainy hours had fewer rentals on average than non-rainy hours.

Rental counts show the number of trips, not the number of different people. Rainfall was linked to lower rentals, but other factors could also explain the difference.

## Project Files

* **Excel workbook:** dashboard, formulas and data
* **CSV files:** original and prepared datasets
* **PDF report:** simple explanation of the project
* **Dashboard image:** preview of the dashboard



This project uses historical data from Seoul, so the findings may not apply to other cities or current rental patterns.

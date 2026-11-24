# IRCTC Business Insights - Power BI Dashboard

This is my Power BI project on IRCTC train booking data. I built a dashboard that shows bookings, revenue, users, trains operated and occupancy, and how each of them changed compared to the previous month.

## Why I made this project

IRCTC has a lot of booking data, but it is hard to understand just by looking at the raw table. I wanted to turn this data into a simple dashboard where anyone can quickly see:

- How many bookings and how much revenue we got
- Whether bookings, revenue and users went up or down compared to last month
- Which routes get the most bookings
- Which booking type and booking channel give more revenue
- How things change by month, day, travel class and train type

I made this project to practice Power BI, DAX and dashboard design for my Data Analyst journey.

## Dataset

Kaggle dataset: https://www.kaggle.com/datasets/anushka29/irctc-dataset

In my data model I used the main data table (`irctc_data`) and a separate `Date table` for month and day names.

## Tools I used

- Power BI Desktop
- Power Query (to load and clean the data)
- DAX (to write measures)
- Data modelling (connected the data table with the date table)

## What is in the dashboard

The report has 2 pages.

**Page 1 - main dashboard**
- Cards for Total Bookings, Total Revenue, Total Users, Trains Operated and Average Occupancy
- Month over month growth % for each card (vs previous month)
- Line charts to see the monthly trend of each measure
- Bar chart for top routes by bookings
- Donut charts for revenue by Booking Type and by Booking Channel
- A text box that updates by itself and tells which month had the highest bookings
- A filter panel (Month, Day, Travel Class, Train Type) with "Filters" and "Close panel" buttons, which uses bookmarks to open and close

**Page 2**
- Slicers (Month, Day, Travel Class, Train Type) used for the filter panel

## DAX measures I created

- Total Bookings
- Total Revenue
- Total Users
- Trains Operated
- Average Occupancy
- Previous month bookings
- Month over month growth % for bookings, revenue, users, trains operated and occupancy

## What I learned

- How to make measures in DAX, especially previous month and growth % calculations
- How to connect a date table to the data table
- How to use bookmarks and buttons to make a filter panel that opens and closes
- How to make a dashboard look clean and easy to read

## Screenshots

(add your screenshots here)

![Dashboard](images/dashboard.png)

## How to open this project

1. Download this repository
2. Open `IRCTC_Power_Bi_Project.pbix` in Power BI Desktop
3. If it asks to refresh the data, download the dataset from the Kaggle link above

## Files

- `IRCTC_Power_Bi_Project.pbix` - the Power BI file
- `images/` - dashboard screenshots
- `README.md` - this file

## About me

Balaga Manohar Babu
B.Tech CSE (2022-2026), Hyderabad
Skills: Python, MySQL, Advanced Excel, Power BI

LinkedIn: (add your link)


# Hotel Summer Booking Dashboard

![Screenshot 2023-01-26 at 12 14 25 PM](https://user-images.githubusercontent.com/82135370/214903645-9e5a3de4-7ccd-41c7-83d7-300f8035339f.png)

As a Business Analyst, Ben Johnson(Hotel Manager) has asked me to develop a detailed dashboard. For that he has shared the hotel dataset containing Resort and City hotel data from 2015 - 2017.

# Goal

To get insights about resort hotel during the summer period(July - August) of 2016. The focus should be on the Cancellation Level, Average daily rate and Revenue Made compared to Revenue Lost on a monthly basis.

# Data Attributes:

Booking ID, Hotel, Booking Date, Arrival Date, Lead Time, Nights, Guests, Distribution Channel, Customer Type, Country, Deposit Type, Avg Daily Rate, Status, Status Update, Cancelled (0/1), Revenue, Revenue Loss

# Data Preperation and Data Transformation:

To prepare the data for analysis, performed data cleaning in Power Query and use DAX expressions to create new columns. It aslo included:
  - Removed unwanted columns which were empty
  - Changed datatype to perform aggregate functions
  - use DAX expressions to create new columns
  - Created new columns using conditional Formatting

# Analysis Results:

- The Resorts in 2016 had an increse in revenue in the summer months of July and August, but at the same time the company lost $987k due to cancellations
in the same month
- Another good news is that the Average daily rate was found to be higher in the months of summer with the lowest percentage of cancellation
- The highest cancellation of Resorts in 2016 was on January, March and November
- To get better insights regarding Cancellation, on further analysis it was found that Higher cancellations were most occuring during 30 days after booking on Mondays and Saturdays in July and August
- On the contrary it was found that the Average daily rate is higher during the period of July and August

# Key Recommendations:

- One method to reduce cancellations are by over booking during July and August
- There is a need to focus more on the bookings during the lead time of 0-30 days in July and August
- Reducing the average daily rate in 0-30 days of July and August might reduce cancellations

Link to dashboard:https://www.novypro.com/project/data-visualization-using-powerbi

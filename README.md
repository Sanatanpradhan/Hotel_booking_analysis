Hotel Booking Data Analysis

Introduction:
This project involves exploring a dataset containing information about hotel bookings, consisting of 119,390 entries with 32 attributes. The aim is to understand booking patterns and customer behavior through Exploratory Data Analysis (EDA).

Objective:
Our main goal is to uncover insights into booking trends, cancellations, and customer preferences. By analyzing the data, we aim to understand factors influencing cancellations, identify peak booking periods, and improve guest satisfaction.

Data Preprocessing:

Duplicate Removal: After loading the dataset, 31,994 duplicate entries were identified and subsequently removed to ensure the integrity of the analysis.
Handling Missing Values: The 'company' column, with 93% missing values, was deemed irrelevant for analysis and therefore excluded. Additionally, columns with only 7% data were considered too insignificant to provide meaningful insights and were consequently disregarded.
Data Formatting: The 'reservation_status_date' column was converted from string format to datetime format to facilitate temporal analysis.
New Feature Creation: A new column named 'arrival date' was created to aid in further analysis of booking patterns and trends.

Key Insights:

1-Booking Trends: There's been a noticeable increase in cancellations over the years.

2-Monthly Bookings: Bookings peaked in July and August, with a gradual decline thereafter.

3-Cancellation Patterns: August shows peak cancellations, suggesting a seasonal trend.

4-Lead Time and Cancellations: Longer lead times tend to correlate with higher cancellation rates.

5-Repeat vs. New Customers: Repeat customers have lower cancellation rates compared to new ones.

6-Room Preferences: Most guests prefer and receive room type "A."

7-Room Assignments vs. Cancellations: Discrepancies in room allocation have minimal impact on cancellations.

8-Guest Origins: Majority of guests are from Portugal, Great Britain, and France.

9-Deposit Types: Guests who didn't make any deposit had higher cancellation rates.

10-ADR Variation: Certain factors like room type "H" and the GDS channel contribute to higher Average Daily Revenue (ADR).

11-Special Requests and ADR: Fulfilling special requests tends to increase ADR.

12-Customer Types and Cancellations: Transient customers have higher cancellation rates compared to group types.

13-Repeat Customer Ratio: Percentage of repeat customers is increasing annually.

14-Guest Demographics and Length of Stay: More adults tend to lead to longer stays.


Business Objective:
Based on these insights, the hotel aims to implement strategies to reduce cancellations, enhance guest satisfaction, and optimize revenue generation. This includes improving booking accuracy, catering to guest preferences, and fostering loyalty among repeat customers.


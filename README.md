# MIST_4610-Project-2
Group name: 61608 Group 3

Team Members

Cavanaugh, Rory
Chadha, Jasmine
McNally, Owen
Mulnix, Hayden
Nguyen, Timmy
Our Dataset

We obtained out data from the State of Washington Open Data site.

Columns:

VIN (PK)(INT)
Country (VARCHAR)
City (VARCHAR)
State (VARCHAR)
Postal Code (INT)
Model Year (INT)
Make (VARCHAR)
Model (VARCHAR)
Electric Vehicle Type (VARCHAR)
Clean Alternative Fuel Vehicle (CAFV) Eligibility (VARCHAR)
Electric Range (INT)
Base MSRP (INT)
Legislative Distric (INT)
DOL Vehicle ID (INT)
Vehicle Location (INT)
Electric Utility (VARCHAR)
2020 Census Tract (INT)
Rows:

A single EVregistration in the state of Washington

Question 1

Question:

Compare the average electric range and the maximum electric range of the top five brands in each category.

Manipulations:

For question one, we had to filter the make to display only the top five. We did this by creating a bar chart, identifying the top five makes, and then adding a filter to show only those makes. We repeated this process for our second bar chart.

Analysis and Results:

Suppose you are an employee for a company in Seattle, Washington. However, you live 45 minutes outside the city and have to commute through high-traffic suburban areas twice a day, five days a week. Your gas vehicle is becoming too expensive, so you decide to switch to an EV. Before making the switch, you want to ensure the one you buy will suit your lifestyle and needs.

Our data model can help with this decision by showing which car brands offer the greatest average electric range and maximum electric range. Based on our model's results, one could conclude that if they are looking for a car that is reliable across all models, they would likely choose one of the brands in the top five for average electric range. On the other hand, if the consumer wants a car that can go the farthest on a single charge, they might choose one of the brands ranked highest in maximum electric range. image
https://private-user-images.githubusercontent.com/202871375/439471802-891b767e-6a0b-48eb-bb0e-822a890d1a94.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDYxMzgyMDcsIm5iZiI6MTc0NjEzNzkwNywicGF0aCI6Ii8yMDI4NzEzNzUvNDM5NDcxODAyLTg5MWI3NjdlLTZhMGItNDhlYi1iYjBlLTgyMmE4OTBkMWE5NC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNTAxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDUwMVQyMjE4MjdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1lNTc0ODgwZWE3N2ExMDFjOTg3MDQ2OTYzYmU5MDg2OWU2NDBmNGMxOGIwNTFlODYwNjQ0ODQzMTk5MTY1ODMzJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.fBBAosx1m3AlJLLcm0h1p6AIrL1xxmochM0CTBA5OUE ![image](https://github.com/user-attachments/assets/e65275eb-79eb-49a0-b060-1b94eee30171)

Question 2

Question:

Which county in Washington utilizes the most electric vehicles?

Manipulations:

For question two, we had to apply a filter to make Tableau only show data for the state of Washington. We also had to match ambiguous counties to only those within Washington. This was necessary; otherwise, we would have seen counties from all over the U.S., which would be incorrect because our dataset only contains instances from Washington. These steps ensured our data correctly displayed all counties in Washington.

Analysis and Results:

Unlike question one, question two helps provide companies with insight into EV adoption across Washington state. Suppose you are working for Tesla and want to expand into more areas of Washington. It would be helpful for your team to understand the scale of EV registration across all counties. Our model supports this by showing the total number of registered EVs per county. According to our model, King County, which includes Seattle, has the highest number of EVs. A Tesla advisor may recommend advertising in nearby counties with similar levels of EV adoption.

image
Tableau Packaged Workbook

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

Question 2

Question:

Which county in Washington utilizes the most electric vehicles?

Manipulations:

For question two, we had to apply a filter to make Tableau only show data for the state of Washington. We also had to match ambiguous counties to only those within Washington. This was necessary; otherwise, we would have seen counties from all over the U.S., which would be incorrect because our dataset only contains instances from Washington. These steps ensured our data correctly displayed all counties in Washington.

Analysis and Results:

Unlike question one, question two helps provide companies with insight into EV adoption across Washington state. Suppose you are working for Tesla and want to expand into more areas of Washington. It would be helpful for your team to understand the scale of EV registration across all counties. Our model supports this by showing the total number of registered EVs per county. According to our model, King County, which includes Seattle, has the highest number of EVs. A Tesla advisor may recommend advertising in nearby counties with similar levels of EV adoption.

image
Tableau Packaged Workbook

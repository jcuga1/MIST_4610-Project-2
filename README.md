# MIST_4610-Project-2
Group name: 
61608 Group 3

## Team Members
1. Cavanaugh, Rory
2. Chadha, Jasmine
3. McNally, Owen
4. Mulnix, Hayden
5. Nguyen, Timmy




## Our Dataset
We obtained out data from the State of Washington Open Data site. 

### Columns: 
1. VIN (PK)(INT)
2. Country (VARCHAR)
3. City (VARCHAR)
4. State (VARCHAR)
5. Postal Code (INT)
6. Model Year (INT)
7. Make (VARCHAR)
8. Model (VARCHAR)
9. Electric Vehicle Type (VARCHAR)
10. Clean Alternative Fuel Vehicle (CAFV) Eligibility (VARCHAR)
11. Electric Range (INT)
12. Base MSRP (INT)
13. Legislative Distric (INT)
14. DOL Vehicle ID (INT)
15. Vehicle Location (INT)
16. Electric Utility (VARCHAR)
17. 2020 Census Tract (INT)

### Rows:

A single EVregistration in the state of Washington



## Question 1

#### Question:
Compare the average electric range and the maximum electric range of the top five brands in each category.

#### Manipulations:
For question one, we had to filter the make to display only the top five. We did this by creating a bar chart, identifying the top five makes, and then adding a filter to show only those makes. We repeated this process for our second bar chart.

#### Analysis and Results:
Suppose you are an employee for a company in Seattle, Washington. However, you live 45 minutes outside the city and have to commute through high-traffic suburban areas twice a day, five days a week. Your gas vehicle is becoming too expensive, so you decide to switch to an EV. Before making the switch, you want to ensure the one you buy will suit your lifestyle and needs.

Our data model can help with this decision by showing which car brands offer the greatest average electric range and maximum electric range. Based on our model's results, one could conclude that if they are looking for a car that is reliable across all models, they would likely choose one of the brands in the top five for average electric range. On the other hand, if the consumer wants a car that can go the farthest on a single charge, they might choose one of the brands ranked highest in maximum electric range.
<img width="605" alt="image" src="https://github.com/user-attachments/assets/891b767e-6a0b-48eb-bb0e-822a890d1a94" />

## Question 2

#### Question:
Which county in Washington utilizes the most electric vehicles?

#### Manipulations:
For question two, we had to apply a filter to make Tableau only show data for the state of Washington. We also had to match ambiguous counties to only those within Washington. This was necessary; otherwise, we would have seen counties from all over the U.S., which would be incorrect because our dataset only contains instances from Washington. These steps ensured our data correctly displayed all counties in Washington.

#### Analysis and Results:
Unlike question one, question two helps provide companies with insight into EV adoption across Washington state. Suppose you are working for Tesla and want to expand into more areas of Washington. It would be helpful for your team to understand the scale of EV registration across all counties. Our model supports this by showing the total number of registered EVs per county. According to our model, King County, which includes Seattle, has the highest number of EVs. A Tesla advisor may recommend advertising in nearby counties with similar levels of EV adoption.

<img width="565" alt="image" src="https://github.com/user-attachments/assets/f1480561-151a-4d17-9cd3-8721d3ba27f4" />


## Tableau Packaged Workbook

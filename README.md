 Real Estate Market Trends – 
 Objective :-Simple Meaning
Create a dashboard that helps investors understand:
Property prices
Rental income (returns)
Market demand & supply
Location-based hotspots

 1. Data Required (Sample Columns)
You can use real estate datasets from Kaggle or sample Excel data.
Property Table
Property ID
City / Location
Property Type (Apartment, Villa, etc.)
Price
Rent
Area (sq ft)
Date
Market Data
City
Demand Index
Supply Index
Interest Rate
Inflation Rate
  2. Key KPIs (Cards)
Add Card visuals for:
Average Property Price
Average Rent
Rental Yield (%)
Total Properties
Average Price per Sq Ft
Rental Yield Formula
Copy code
DAX
Rental Yield (%) = 
DIVIDE(SUM(Properties[Rent]) * 12, SUM(Properties[Price])) * 100
 3. Visuals to Include
Property Prices Analysis:-
Line Chart
Axis: Date
Values: Average Price
Legend: City
Bar Chart
Axis: City
Values: Average Price
Rental Yield Analysis:-
Clustered Column Chart
Axis: City
Values: Rental Yield (%)
Table
City | Avg Price | Avg Rent | Rental Yield
3.Demand & Supply Trends:-
Line Chart
Axis: Date
Values: Demand Index, Supply Index
Stacked Bar Chart
Axis: City
Values: Demand vs Supply
4.Geographic Visualization:-
Map / Filled Map
Location: City
Size: Average Price
Color: Rental Yield
*This helps identify investment hotspots
 4. Filters / Slicers:-
Add slicers for:
City
Property Type
Date
Price Range
5. Insights Section:-
Add a summary like:
  Cities with high rental yield and rising demand indicate strong investment potential. Locations with increasing prices and limited supply show future growth opportunities.”
 6. Final Deliverable
Interactive Power BI Dashboard
    1. Clean layout
2. Easy filters
3. Investor-friendly insights# code-apha-task3

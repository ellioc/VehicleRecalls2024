# 2024VehicleCarsAndRecalls

Project Goal and Objective
I am reporting data for 2024 vehicles comparing two datasets one with cars sales information reports like cars.com, choosing make model, color, etc. The other is a dataset of recalls from years 2020- 2024. I will first clean this data and then later join them together using SQL and Tableau to help.The goal is to discover which 2024 car brands are more reliable vs the ones that are not.

Project Plan
Clean, normalize, and join data using SQL based on make, model, and year. Exploratory analysis will be conducted using Python to uncover patterns in pricing, brand, and recall frequency. A custom reliability score will be developed to rank vehicles, and insights will be visualized through Tableau dashboards. This approach effectively combines real-world market data with safety records, offering a practical and data-driven way to guide consumer decision-making.

Data Dictionary

name: The full name of the vehicle, including make, model, and trim.
summary: A brief description of the vehicle issues.
make: The manufacturer of the vehicle (e.g., Ford, Toyota, BMW).
model: The model name of the vehicle.
year: The year the vehicle was manufactured.
price: The price of the vehicle in USD.
cylinders: The number of cylinders in the vehicle's engine.
fuel: The type of fuel used by the vehicle (e.g., Gasoline, Diesel, Electric).
body: The body style of the vehicle (e.g., SUV, Sedan, Pickup Truck).
exterior_color: The exterior color of the vehicle.
drivetrain: The drivetrain of the vehicle (e.g., All-wheel Drive, Front-wheel Drive).
NHTSA ID: National Highway Traffic Safety Administration ID to look up vehicle recall

Data Summary
The vehicles for sale dataset comprises approximately 50,000 records collected from online auto marketplaces such as Cars.com. The data includes listings of vehicles primarily from the year 2024, with around 60% of the listings featuring 2024 models. Another 25% are from 2023, while the remaining 15% are from earlier years. There are over 40 unique vehicle makes represented in the dataset, with the most common being Toyota, Ford, Chevrolet, Honda, and Nissan. In terms of vehicle types, sedans, SUVs, and pickup trucks dominate the listings, reflecting current consumer preferences.

The average price of a vehicle listed in this dataset is approximately $28,400, with mileage averaging around 31,000 miles. Popular exterior colors include white, black, gray, and silver. Most vehicles are equipped with automatic transmissions (about 92%), while manual and other types (like CVT) make up the remaining 8%. Each listing provides detailed attributes including the vehicle's make, model, color, body type, drivetrain, seller location, and dealer name, along with the date it was listed.

The vehicle recalls dataset, spanning the years 2020 to 2024, includes around 12,000 records and details safety recalls issued by manufacturers and federal agencies like the National Highway Traffic Safety Administration (NHTSA). The most frequently recalled makes are Ford, Chevrolet, Toyota, and Honda. Recalls tend to address critical safety concerns, with the most common issues involving airbags, brake systems, electrical systems, and fuel systems.

Airbag-related recalls alone account for roughly 25% of the entries, followed by brake systems (18%), powertrain issues (15%), and electrical systems (13%). On average, recalls are issued 10 to 16 months after the vehicle’s manufacture date. Each recall record provides detailed information including the affected component, a summary of the issue, potential safety consequences, and the remedy offered by the manufacturer.

Together, these datasets offer a comprehensive view of the 2024 vehicle market and related safety issues. This provides a strong foundation for analytical comparisons between vehicle sale trends and recall patterns, which will later be visualized using SQL queries and Tableau dashboards.


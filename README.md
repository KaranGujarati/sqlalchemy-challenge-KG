# Hawaii Climate Analysis

This repository includes an analysis of climate patterns in a popular vacation spot, Honolulu, Hawaii.

## PART 1 - Climate Analysis and Exploration

Using Python and SQLAlchemy to do a climate analysis and data exploration of the climate database with the aide of the Pandas, and Matplotlib libraries. 

#### Precipitation Analysis
Created a bar graph of the precipitation by date using the DataFrame plot method.

#### Weather Station Analysis
Calculated the total number of stations, then listed the stations and observation counts in descending order to plot the last 12 months of temperature observation data (tobs).

#### Temperature Analysis
Created a temperature histogram for the most active station, and error bar for MAX, MIN and AVG temperature for last 12 months. Then created an area plot for daily normal temp. of historical data.

## PART 2 - Climate App
Design a Flask API based on the queries that you have just developed, using FLASK.
Routes include:
  - Home page, containing a list of all routes that are available.
  - /api/v1.0/precipitation, containing a dictionary using date as the key and prcp as the value.
  - /api/v1.0/stations, containing a JSON list of stations from the dataset.
  - /api/v1.0/tobs, containing a JSON list of Temperature Observations (tobs) for the previous year.
  - /api/v1.0/<start> and /api/v1.0/<start>/<end>, returning a JSON list of the minimum temperature, the average temperature, and the max temperature for a given start or start-end range.


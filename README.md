# Project Description
Analyse climate in Honolulu, Hawaii to plan for a holiday. Utilise SQLAlchemy ORM queries, Pandas, and Matplotlib to conduct a basic climate analysis and designed a Flask App to showcase database query results. This app ('Hawaii Weather Data API') enables of query of the weather data between a period span of 1 Jan 2010 to 23 Aug 2017.

## How to navigate the Hawaii Weather Data API

### Run this app on terminal with 'flask run' and access the local url provided.

Welcome page (/): Provides a list of all available routes and the respective queries served.

Daily Precipitation Totals for the Last 12 Months (/api/v1.0/precipitation)

List of Weather Stations (/api/v1.0/stations)

Temperature Observations for Most Active Station over Last 12 Months (/api/v1.0/tobs)

Min, Average & Max Temperatures from Start Date (/api/v1.0/<start>)

Min, Average & Max Temperatures for Date Range: (/api/v1.0/<start>/<end>)

NOTE: Please enter all 'start' and 'end' dates in yyyy-mm-dd format.

  
## Packages/Dependencies Used

matplotlin.pyplot

numpy

scipy.stats

pandas

datatime

sqlalchemy


## Contents of 'SurfsUp' Folder

'Resources' folder (contains starter csv files and sqlite database)

climate_analysis.ipnyb (Jupyter notebook containing analysis and data exploration)

Precipitation Analysis_Hawaii.png (Bar Chart of Rainfall Amount in Hawaii between 23 Aug 2016 to 23 Aug 2017)

Aug2016-2017_USC00519281.png (Histogram of Temperature Observation Data for most active weather station)

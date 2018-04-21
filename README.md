<h1><b>Surf's Up! Assignment</h1></b>

<h2> Step 1 - Data Engineering </h2>

<p>In Step 1 I utilized jupyter notebooks and pandas to read in 2 CSV files ('hawaii_measurements.csv' and hawaii_stations.csv') as data frames, cleaned up the files and saved them with the prefix 'clean_'. </p>

<h2> Step 2 - Database Engineering </h2>

<p> In Step 2 I utilized jupyter notebooks and pandas to read in the cleaned CSVs. I created a database 'hawaii.sqlite', defined ORM classes and created tables in the database. </p>

<h2> Step 3 - Climate Analysis and Exploration </h2>

<p> Step 3 was carried out in a jupyter notebook 'climate_analysis.ipynb'. For the this project I chose a time frame of August 1-7 for analysis in this assignment. I then utilized SQLAlchemy automap_base() to reflect tables into classes and saved these as references as 'Station' and 'Measurement'. </p>

<h2> Step 3a Precipitation Analysis </h2>

<p> For this step, I was to design a query to retrieve the last 12 months of precipitation data, select only the date and prcp values, Load the query results into a Pandas DataFrame, set the index to the date column, and plot the results using the DataFrame plot method.  </p>

<h2> Step 3b Station Analysis </h2>

<p> For this step I was to design a query to calculate the total number of stations, design a query to calculate the most active stations(in descending order) and state which is the most active.</p>

<p> Next, I was to design a query to retrieve the last 12 months of temperature observation data (tobs), filter by the station with the highest number of observations, and plot the results as a histogram with bins=12. </p>

<h2> Step 3c Temperature Analysis </h2>

<p> Write function 'calc_temps' that accepts a start date and end date in the format %Y-%m-%d and return the minimum, average, and maximum temperatures for that range of dates. </p>

<p> Use 'calc_temps' function to calculate the min, avg, and max temperatures for the trip using the matching dates from the previous year' </p>

<p>Plot the min, avg, and max temperature from your previous query as a bar chart. </p>

<h2> Step 4 - Climate App </h2>

<p>  Design a Flask API based on queries developed</p>

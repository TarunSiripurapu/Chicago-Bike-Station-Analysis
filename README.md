bdata.txt has one record for each bike station (669 stations) but the the complete data set has 176 million records.

The data is stored as name value pairs as shown below:
{
	"id": "515",
	"timestamp": "2020-11-16T11:55:55.000",
	"station_name": "Paulina St & Howard St",
	"total_docks": "19",
	"docks_in_service": "19",
	"available_docks": "9",
	"available_bikes": "10",
	"percent_full": "53",
	"status": "In Service",
	"latitude": "42.019159",
	"longitude": "-87.673573",
	"location": {
		"type": "Point",
		"coordinates": [-87.673573, 42.019159]
	},
	"record": "51520201116115555"
}

Specific bike station id's are selected from the above file to perform further analysis.


Steps performed are:
1. Using object oriented programming techniques to create a BikeStation object with a constructor and multiple methods.
2. Run a data modeling processes to extract the necessary bike station utilization information from the JSON data and group the data by station.
3. Run  an analysis to calculate some basic statistics about the data.
4. Create at least three different types of visualizations of the bike station data you have retrieved and processed and save some plots. 

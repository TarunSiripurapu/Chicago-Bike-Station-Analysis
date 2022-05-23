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


Execution 1:
The BikeStationCode python file contains the code about utilizing object oriented programming concepts to create a bikestation object that has a constructor and
multiple methods.

Some of the steps involved:
1. Create a basic class that can hold all relevant Bike data for an individual bike station 
2. Appropriately creating a constructor to set all data values.
3. Use the @property decorator to make the Status in BikeStation class private.
4. Use the @???.setter method to validate the private property in some way before setting its value.
5. Creating one or more regular class methods to CALCULATE other relevant bike station values (percentage full, docks in service, etc) from the data attributes 
   you are storing as a part of the class.
6. Override the __str__ method to print a string representation of a BikeStation that looks like the String below
   Paulina St & Howard St had 10 bikes on 2020-11-16 11:55 
   
   
Your output should look something like this:

Paulina St & Howard St had 10 bikes on 2020-11-16 11:55
Clark St & Jarvis Ave had 1 bikes on 2020-11-16 11:55
Greenview Ave & Jarvis Ave had 3 bikes on 2020-11-16 11:55
Bosworth Ave & Howard St had 1 bikes on 2020-11-16 11:55
Eastlake Ter & Rogers Ave had 2 bikes on 2020-11-16 11:55
Stations: [515, 517, 520, 522, 523] Bikes Available 17 Docks Available 58

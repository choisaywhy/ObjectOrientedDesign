``` java
bool InsertFlightList(){
Print Insert FlightList data to create
Input the FlightList(flname, flstar, fldes, fldepart, flarrival) in screen
Connect FlightList DB 
// Check FlightList data
if (inserted flname, flstar,fldepart already exists)
	Print FlightList already registered
	return false
// inserted csn does not exist
Connect FlightList DB 
if (Insert FlightList(flname, flstar, fldes, fldepart, flarrival) in to FlightList DB)
	Print Successfully Registered
	return true
else // Could not insert data
	Print Cannot insert data
	return false
}
```


<!--stackedit_data:
eyJoaXN0b3J5IjpbMTgxMDg5ODcwNl19
-->
``` java
bool UpdateFlightList(){
Print Insert flsn to update
Input the FlightList(flsn) in screen
Connect FlightList DB 
// Check FlightList data
if (inserted flsn does not exist)
	Print Inserted flsn does not exist
	return false
// Inserted flsn exists
Connect FlightList DB 
// Show original datas and request to insert datas to change
Print Original datas and Request Insert datas to update
Input FlightList(flsn,flname, flstar, fldes, fldepart, flarrival) in screen
Connect FlightList DB 
if (Update FlightList(flsn,flname, flstar, fldes, fldepart, flarrival) in Flight DB)
	Print Successfully Updated
	return true
else // Could not update data
	Print Cannot update data
	return false
}
```



<!--stackedit_data:
eyJoaXN0b3J5IjpbMTA3MTIzNzEzNF19
-->
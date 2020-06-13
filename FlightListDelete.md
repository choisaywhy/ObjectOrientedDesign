``` java
bool DeleteFlightList(){
Print Insert flsn to delete
Input the FlightList(flsn) in screen
Connect FlightList DB 
// Check FlightList data
if (inserted flsn does not exist)
	Print Inserted flsn does not exist
	return false
// Inserted flsn exists
Connect FlightList DB 
if (Delete FlightList(flsn) in FlightList DB)
	Print Successfully Deleted
	return true
else // Could not delete data
	Print Cannot delete data
	return false
}
```

<!--stackedit_data:
eyJoaXN0b3J5IjpbOTA2Nzk5MTczXX0=
-->
``` java
bool DeleteFlightBook(){
Input the Customer(csn, cpassword) in screen
Connect Customer DB 
// Check Customer data
if (inserted csn does not exist)
	Print inserted data does not exist
	return false
else // inserted csn exists
	if (inserted cpassword is incorrect)
	Print inserted data is wrong
	return false

// Request to insert FlightBook to delete
Print Insert FlightBook SignalNumber to delete
Input FlightBook(flsn) in screen
Connect FlightBook DB 
// Check FlightBook data
if (Inserted FlightBook data does not exist)
	Print Inserted FlightBook data does not exist
	return false
// Inserted FlightBook data exists
Connect FlightBook DB
if (Delete FlightBook(fbsn, csn, fsn, fseat) in to FlightBook DB)
	Print Successfully delete
	return true
else // Could not delete data
	Print Cannot delete data
	return false
}
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTI0MzgwODg1MV19
-->
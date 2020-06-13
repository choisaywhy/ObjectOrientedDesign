``` java
bool SearchFlightBook(){
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

// Request to insert FlightBook to Search
Print Insert FlightBook SignalNumber to delete
Input FlightBook(flsn) in screen
Connect FlightBook DB 
// Check FlightBook data
if (Inserted FlightBook data does not exist)
	Print Inserted FlightBook data does not exist
	return false
// Inserted FlightBook data exists
Connect FlightBook DB
Print FlightBook(fbsn, csn, fsn, fseat, fbdate)
return true
}
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEyNTk0MjkyNzVdfQ==
-->
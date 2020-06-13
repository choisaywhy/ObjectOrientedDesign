``` java
bool UpdateFlightBook(){
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

// Request to insert FlightBook to update
Print Insert FlightBook SignalNumber to update
Input FlightBook(flsn) in screen
Connect FlightBook DB 
// Check FlightBook data
if (Inserted FlightBook data does not exist)
	Print Inserted FlightBook data does not exist
	return false
// Inserted FlightBook data exists
// Show original datas and request to insert datas to change
Print Original datas and Request Insert datas to update
Input FlightBook(flstar, fldes, fldepart, flarrival) in screen
Connect FlightList DB 
// Check FlightList data
if (Inserted FlightBook data does not exist)
	Print Inserted FlightBook data does not exist
	return false
// Inserted FlightBook data exists
Connect Flight DB 
// Check Flight data
Print bookable seats
Input seat to sit in screen
Connect FlightBook DB
if (Update FlightBook(fbsn, csn, fsn, fseat) in to FlightBook DB)
	Print Successfully updated
	return true
else // Could not update data
	Print Cannot update data
	return false
}
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTYyMzUyNjMyOV19
-->
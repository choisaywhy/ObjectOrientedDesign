``` java
bool InsertFlightBook(){
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
Print Insert Flight datas to book
Input FlightBook(flstar, fldes, fldepart) in screen
Connect FlightList DB 
// Check FlightList data
if (Suitable FlightList does not exist)
	Print Flight does not exist
	return false
// Requested Flight exists
Connect Flight DB 
// Check Flight data
Print bookable seats
Input seat to sit in screen
Connect FlightBook DB
if (Insert FlightBook(csn, fsn, fseat) in to FlightBook DB)
	Print Successfully booked
	return true
else // Could not insert data
	Print Cannot insert data
	return false
}
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTcyODU1Mzg1NiwtMTExNDMzNTg5N119
-->
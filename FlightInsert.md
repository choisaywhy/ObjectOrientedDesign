``` java
bool InsertFlight(){
Print Insert Flight data to create
Input the Flight(flsn, csn, fseat) in screen
Connect Flight DB 
// Check Flight data
if (inserted csn already exists)
	Print csn already registered
	return false
// inserted csn does not exist
Connect Flight DB 
if (Insert Flight(flsn, csn, fseat) in to Flight DB)
	Print Successfully Registered
	return true
else // Could not insert data
	Print Cannot insert data
	return false
}
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE3MjU1MzUxNTVdfQ==
-->
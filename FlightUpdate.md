``` java
bool UpdateFlight(){
Print Insert fsn to update
Input the Flight(fsn) in screen
Connect Flight DB 
// Check Flight data
if (inserted fsn does not exist)
	Print Inserted fsn does not exist
	return false
// Inserted fsn exists
Connect Flight DB 
// Show original datas and request to insert datas to change
Print Original datas and Request Insert datas to update
Input Flight(flsn, csn, fseat) in screen
Connect Flight DB 
if (Update Flight(flsn, csn, fseat) in Flight DB)
	Print Successfully Updated
	return true
else // Could not update data
	Print Cannot update data
	return false
}
```


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIxNDQzMDg4MThdfQ==
-->
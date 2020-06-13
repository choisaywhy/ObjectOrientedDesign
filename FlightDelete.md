``` java
bool DeleteFlight(){
Print Insert fsn to delete
Input the Flight(fsn) in screen
Connect Flight DB 
// Check Flight data
if (inserted fsn does not exist)
	Print Inserted fsn does not exist
	return false
// Inserted fsn exists
Connect Flight DB 
if (Delete Flight(fsn) in Flight DB)
	Print Successfully Deleted
	return true
else // Could not delete data
	Print Cannot delete data
	return false
}
```

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0NTcwMzUyOTVdfQ==
-->
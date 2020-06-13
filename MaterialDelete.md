``` java
bool DeleteMaterial(){
Print Insert msn to delete
Input the Material(msn) in screen
Connect Material DB 
// Check Material data
if (inserted msn does not exist)
	Print Inserted msn does not exist
	return false
// Inserted msn exists
Connect Material DB 
if (Delete Material(msn) in Material DB)
	Print Successfully Deleted
	return true
else // Could not delete data
	Print Cannot delete data
	return false
}
```

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTQ0NjExMzkxMl19
-->
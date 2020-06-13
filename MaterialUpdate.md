``` java
bool UpdateMaterial(){
Print Insert msn to update
Input the Material(msn) in screen
Connect Material DB 
// Check Material data
if (inserted msn does not exist)
	Print Inserted msn does not exist
	return false
// Inserted msn exists
Connect Material DB 
// Show original datas and request to insert datas to change
Print Original datas and Request Insert datas to update
Input Material(msn, mlsn in screen
Connect Material DB 
if (Update Material(msn, mlsn) in Material DB)
	Print Successfully Updated
	return true
else // Could not update data
	Print Cannot update data
	return false
}
```


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTExMzM5OTk1ODVdfQ==
-->
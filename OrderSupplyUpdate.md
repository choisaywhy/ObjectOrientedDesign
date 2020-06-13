``` java
bool UpdateOrderSupply(){
Input the Employee(esn, epassword) in screen
Connect Employee DB 
// Check Employee data
if (inserted esn does not exist)
	Print inserted data does not exist
	return false
else // inserted esn exists
	if (inserted epassword is incorrect)
	Print inserted data is wrong
	return false
// Request to insert Supply datas to update
Print Insert Supply datas to update
Input OrderSupply(ossn) in screen
Connect OrderSupply DB 
// Check OrderSupply data
if (Inserted OrderSupply data does not exist)
	Print Inserted OrderSupply data does not exist
	return false
// Inserted OrderSupply data exists
// Show original datas and request to insert datas to change
Print Original datas and Request Insert datas to update
Input OrderSupply(mlsn, ssn, osnum, osprice, odate, sdate) in screen
Connect OrderSupply DB
if (Update OrderSupply(mlsn, ssn, osnum, osprice, odate) in to OrderSupply DB)
	Print Successfully updated
	return true
else // Could not update data
	Print Cannot update data
	return false
}
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE2NTM0NDA3MzVdfQ==
-->
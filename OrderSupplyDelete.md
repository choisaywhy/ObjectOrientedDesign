``` java
bool DeleteOrderSupply(){
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
// Request to insert Supply datas to delete
Print Insert Supply datas to delete
Input OrderSupply(ossn) in screen
Connect OrderSupply DB 
// Check OrderSupply data
if (Inserted OrderSupply data does not exist)
	Print Inserted OrderSupply data does not exist
	return false
// Inserted OrderSupply data exists
Connect OrderSupply DB
if (Delete OrderSupply(ossn) in OrderSupply DB)
	Print Successfully deleted
	return true
else // Could not delete data
	Print Cannot delete data
	return false
}
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTU2OTEwODg2OV19
-->
``` java
bool SearchOrderSupply(){
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
// Request to insert Supply datas to search
Print Insert Supply datas to delete
Input OrderSupply(ossn) in screen
Connect OrderSupply DB 
// Check OrderSupply data
if (Inserted OrderSupply data does not exist)
	Print Inserted OrderSupply data does not exist
	return false
// Inserted OrderSupply data exists
Connect OrderSupply DB
Print OrderSupply(mlsn, ssn, osnum, osprice, odate)
return true
}
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTY2MDA1NTI3MV19
-->
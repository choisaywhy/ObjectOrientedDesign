``` java
bool InsertOrderSupply(){
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
Print Insert Supply datas to order
Input OrderSupply(mlname, sname, osnum, osprice, odate) in screen
Connect Supplier DB 
// Check Supplier data
if (Inserted Supplier:sname does not exist)
	Print Supplier does not exist
	InsertSupplier()
// Requested Supplier exists
Connect MaterialList DB 
// Check MaterialList data
if (Inserted MaterialList:mlname does not exist)
	Print MaterialList does not exist
	InsertMaterialList()
// Requested MaterialList exists

Connect OrderSupply DB
if (Insert OrderSupply(mlsn, ssn, osnum, osprice, odate) in to OrderSupply DB)
	Print Successfully ordered
	return true
else // Could not insert data
	Print Cannot insert data
	return false
}
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTk1ODk4NTQxM119
-->
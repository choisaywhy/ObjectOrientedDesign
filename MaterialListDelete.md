``` java
bool DeleteMaterialList(){
Print Insert mlsn to delete
Input the MaterialList(mlsn) in screen
Connect MaterialList DB 
// Check MaterialList data
if (inserted mlsn does not exist)
	Print Inserted mlsn does not exist
	return false
// Inserted mlsn exists
Connect MaterialList DB 
if (Delete MaterialList(mlsn) in MaterialList DB)
	Print Successfully Deleted
	return true
else // Could not delete data
	Print Cannot delete data
	return false
}
```

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTM4OTU5MjU4MF19
-->
``` java
bool UpdateMaterialList(){
Print Insert mlsn to update
Input the MaterialList(mlsn) in screen
Connect MaterialList DB 
// Check MaterialList data
if (inserted mlsn does not exist)
	Print Inserted mlsn does not exist
	return false
// Inserted mlsn exists
Connect MaterialList DB 
// Show original datas and request to insert datas to change
Print Original datas and Request Insert datas to update
Input MaterialList(mlsn,mlname, mlcategory, ssn) in screen
Connect MaterialList DB 
if (Update MaterialList(mlsn,mlname, mlcategory, ssn) in Material DB)
	Print Successfully Updated
	return true
else // Could not update data
	Print Cannot update data
	return false
}
```



<!--stackedit_data:
eyJoaXN0b3J5IjpbLTUxNTU2NDk1Nl19
-->
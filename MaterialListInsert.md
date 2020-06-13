``` java
bool InsertMaterialList(){
Print Insert MaterialList data to create
Input the MaterialList(mlname, mlcategory, ssn) in screen
Connect MaterialList DB 
// Check MaterialList data
if (inserted mlname already exists)
	Print MaterialList already registered
	return false
// inserted mlname does not exist
Connect MaterialList DB 
if (Insert MaterialList(mlname, mlcategory, ssn) in to MaterialList DB)
	Print Successfully Registered
	return true
else // Could not insert data
	Print Cannot insert data
	return false
}
```


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE1NTA3OTk0MDRdfQ==
-->
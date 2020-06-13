``` java
bool DeleteSupplier(){
Print Insert ssn to delete
Input the Supplier(ssn) in screen
Connect Supplier DB 
// Check Supplier data
if (inserted ssn does not exist)
	Print Inserted ssn does not exist
	return false
// Inserted ssn exists
Connect Supplier DB 
if (Delete Supplier(ssn) in Supplier DB)
	Print Successfully Deleted
	return true
else // Could not delete data
	Print Cannot delete data
	return false
}
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5MjgwNjc3OTFdfQ==
-->
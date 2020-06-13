``` java
bool DeleteCustomer(){
Print Insert csn to delete
Input the Customer(csn) in screen
Connect Customer DB 
// Check Customer data
if (inserted csn does not exist)
	Print Inserted csn does not exist
	return false
// Inserted csn exists
Connect Customer DB 
if (Delete Customer(csn) in Customer DB)
	Print Successfully Deleted
	return true
else // Could not delete data
	Print Cannot delete data
	return false
}
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTc5MzIzMzE1M119
-->
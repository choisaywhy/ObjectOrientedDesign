``` java
bool InsertSupplier(){
Print Insert Supplier data to create
Input the Supplier(sname, saddress, stel) in screen
Connect Supplier DB 
// Check Supplier data
if (inserted sname already exists)
	Print Supplier already registered
	return false
// inserted sname does not exist
Connect Supplier DB 
if (Insert Supplier(sname, saddress, stel) in to Supplier DB)
	Print Successfully Registered
	return true
else // Could not insert data
	Print Cannot insert data
	return false
}
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTg2OTkwMjY3N119
-->
``` java
bool UpdateSupplier(){
Print Insert ssn to update
Input the Supplier(ssn) in screen
Connect Supplier DB 
// Check Supplier data
if (inserted ssn does not exist)
	Print Inserted ssn does not exist
	return false
// Inserted ssn exists
Connect Supplier DB 
// Show original datas and request to insert datas to change
Print Original datas and Request Insert datas to update
Input Supplier(ssn, sname, saddress, stel) in screen
Connect Supplier DB 
if (Update Supplier(ssn, sname, saddress, stel) in Supplier DB)
	Print Successfully Updated
	return true
else // Could not update data
	Print Cannot update data
	return false
}
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbOTAzMjc5MDddfQ==
-->
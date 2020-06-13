``` java
bool UpdateCustomer(){
Print Insert csn to update
Input the Customer(csn) in screen
Connect Customer DB 
// Check Customer data
if (inserted csn does not exist)
	Print Inserted csn does not exist
	return false
// Inserted csn exists
Connect Customer DB 
// Show original datas and request to insert datas to change
Print Original datas and Request Insert datas to update
Input Customer(csn, cname, caddress, ctel, cpassport, cpassword) in screen
Connect Customer DB 
if (Update Customer(cname, caddress, ctel, cpassport, cpassword) in Customer DB)
	Print Successfully Updated
	return true
else // Could not update data
	Print Cannot update data
	return false
}
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTYzNDk2OTY3NV19
-->
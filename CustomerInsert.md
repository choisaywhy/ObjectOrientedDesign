``` java
bool InsertCustomer(){
Print Insert Customer data to create
Input the Customer(cname, caddress, ctel, cpassport, cpassword) in screen
Connect Customer DB 
// Check Customer data
if (inserted cpassport already exists)
	Print You already registered
	return false
// inserted cpassport does not exist
Connect Customer DB 
if (Insert Customer(cname, caddress, ctel, cpassport, cpassword) in to Customer DB)
	Print Successfully Registered
	return true
else // Could not insert data
	Print Cannot insert data
	return false
}
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbNjc0ODI3MTg0XX0=
-->
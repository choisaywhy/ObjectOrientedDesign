``` java
bool InsertEmployee(){
Print Insert Employee data to create
Input the Employee(ename, eaddress, etel, epassword) in screen
Connect Employee DB 
// Check Employee data
if (inserted etel already exists)
	Print You already registered
	return false
// inserted etel does not exist
Connect Employee DB 
if (Insert Employee(ename, eaddress, etel, epassword) in to Employee DB)
	Print Successfully Registered
	return true
else // Could not insert data
	Print Cannot insert data
	return false
}
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbMjMwNjk0ODcyXX0=
-->
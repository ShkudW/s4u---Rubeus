# s4u---Rubeus

for situations you have machine with constrained delegtion (any protocol) with SPN of:
MSSQLSvc/sqlserver.domain.com:1433

rubeus doesn't know how to handle with "altservice" and transform the mssqlsvc to CIFS or HOST without removing the port ":1433"

so copy this code instead S4u.cs 

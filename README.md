<div align="center">

## ADO\.Net


</div>

### Description

Make a Simple Connection to an Access/SQL Server Database
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Ravindrar\(RMKT\.Net\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/ravindrar-rmkt-net.md)
**Level**          |Beginner
**User Rating**    |2.4 (65 globes from 27 users)
**Compatibility**  |VB\.NET
**Category**       |[Databases](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/databases__10-5.md)
**World**          |[\.Net \(C\#, VB\.net\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/net-c-vb-net.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/ravindrar-rmkt-net-ado-net__10-595/archive/master.zip)





### Source Code

```
ADO.Net - The new data access model for the .Net framework(Microsoft).
ADO.Net is essentially a set of classes that allow a .Net Application to read and write data from and to a data source respectively.
To Create a Connection to an Access Data Base:
1. Imports System.Data
2. Create a connection object
Dim conAccess as new OLEDB.OLEDBConnection
ConAccess.ConnectionString = "Provider = Microsoft.Jet.OLEDB.4.0;Data Source = C:\Program files\DataBase Name;"
3. ConAccess.Open() ' To Open the Connection
To Connect to SQL Server
1. Dim Consql as new sqlclient.sqlconnection()
2. ConSql.connectionstring = "Integrated Security = True;Data Source = LocalHost;Initial Catalog = Database Name;"
3. Consql.open() 'To Open the Connection
```


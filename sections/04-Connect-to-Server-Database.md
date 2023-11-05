Connect to the SQL Server Database 
============
- [Windows Authentication](04-Connect-to-Server-Database.md#Windows-Authentication)
- [SQL Server Authentication](04-Connect-to-Server-Database.md#SQL-Server-Authentication)

![11](/images/11-SSMS.png)

# Windows Authentication
To connect server database by Windows Authentication, follow these steps:
1. select the type of server to connect to **Database Engine**.<br>
2. connecting to Microsoft SQL Server Database Engine. In most cases, you can connect by **entering the computer name** of the database server in the **Server name box**.<br>
3. select the mode of Authentication to connect to **Windows Authentication**.<br>
4. select to **connect** to the server.
![12](/images/12-SSMS.png)

# SQL Server Authentication
Before you begin, you must **first create the new login using** [Here](sections/03-Create-a-login-using.md)
![14](/images/14-SSMS.png)
To connect server database by SQL Server Authentication, follow these steps:<br>
1. select the type of server to connect to **Database Engine**.<br>
2. entering the computer name of the database server in the **Server name** box.<br>
3. select the mode of Authentication to connect to **SQL Server Authentication**.<br>
4. enter the **login** to connect with server database.<br>
5. enter the **password** for the login.<br>
6. select to **connect** to the server.
![13](/images/13-SSMS.png)


For more information on connecting SQL Server Database [Here](https://learn.microsoft.com/en-us/sql/ssms/f1-help/connect-to-server-login-page-database-engine?view=sql-server-ver16)

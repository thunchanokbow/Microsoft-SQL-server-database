How to create a login in SQL Server 
============
![10](/images/10-SSMS.png)
## To create a login using SSMS for SQL Server follow these steps:
1. In Object Explorer, expand the folder of the server instance in which you want to create the new login.<br>
2. Right-click the **Security** folder, point to New, and select **Login**.<br>
3. In the **Login - New** dialog box, on the **General page**, enter the name of a user in the Login name box. Alternately, select **Search** to open the **Select User or Group** dialog box.<br>
4. To create a login that is saved on a SQL Server database, select **SQL Server authentication**.
- **Enter a password for the new user**. Enter that password again into the **Confirm Password**.
- **Do not select** the Enforce password **expiration**.
5. Select **OK**.
![9](/images/09-SSMS.png)
For more information on creating a login using [Here](https://learn.microsoft.com/en-us/sql/relational-databases/security/authentication-access/create-a-login)

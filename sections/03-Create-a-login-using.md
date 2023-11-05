How to create a login in SQL Server 
============
- [Create a new login using](03-Create-a-login-using.md#Create-a-new-login-using)
- [Setup Authentication mode](03-Create-a-login-using.md#Setup-Authentication-mode)


![10](/images/10-SSMS.png)
# Create a new login using
To create a login using SSMS for SQL Server follow these steps:
1. In Object Explorer, expand the folder of the server instance in which you want to create the new login.<br>
2. Right-click the **Security** folder, point to New, and select **Login**.<br>
3. In the **Login - New** dialog box, on the **General page**, enter the name of a user in the Login name box. Alternately, select **Search** to open the **Select User or Group** dialog box.<br>
4. To create a login that is saved on a SQL Server database, select **SQL Server authentication**.
- **Enter a password for the new user**. Enter that password again into the **Confirm Password**.
- **Do not select** the Enforce password **expiration**.
5. Select **OK**.
![9](/images/09-SSMS.png)

# Setup Authentication mode
To setup Authentication mode follow these steps:
1. In SQL Server Management Studio (SSMS) Object Explorer, right-click the server, and then select **Properties.**
2. On the **Security** page, under **Server authentication**, select the new server authentication mode, and then select **OK**.
3. In the SQL Server Management Studio dialog box, select **OK** to acknowledge the requirement to restart SQL Server.
4. In Object Explorer, right-click your server, and then select **Restart**. If SQL Server Agent is running, it must also be restarted.

![15](/images/15-SSMS.png)
![16](/images/16-SSMS.png)
5. In Object Explorer, expand **Security**, expand Logins, right-click **a new login using**, and then select **Properties**.
6. On the **General** page, you might have to create and confirm a password for the **new login using**.
7. On the **Status** page, in the Login section, select **Enabled**, and then select **OK**.

![17](/images/17-SSMS.png)

For more information on creating a login using [Here](https://learn.microsoft.com/en-us/sql/relational-databases/security/authentication-access/create-a-login)

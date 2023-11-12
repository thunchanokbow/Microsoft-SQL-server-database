Allow Remote Connections to SQL Server
============
- [Enabling SQL Server to accept remote connection](04-Connect-to-Server-Database.md#Windows-Authentication)

# Enabling SQL Server to accept remote connection
![0](/images/0-Remote.png)
To enabling sql server to accept remote connection, follow these steps:
1. Check the **IP Address** of the server.
2. Press the windows button and open **SQL server configuration manager**.
3. Click on **SQL Server Network Configuration**.
4. Click **Protocols for MSSQLSERVER** then select the last option TCP/IP **right-click Enable** and **OK**.
5. Select **SQL Server Service** then **right-click Restart**.
6. Go back and click **TCP/IP** in the properties select **IP Addresses** move down to **TCP Post** enter port number **1433** and **OK**
7. Select **SQL Server Service** and **Restart** again.
![1](/images/1-Remote.png)
![2](/images/2-Remote.png)
![3](/images/3-Remote.png)


Adding SQL Server connection port in firewall

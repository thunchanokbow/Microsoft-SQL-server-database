Allow Remote Connections to SQL Server
============
- [Enabling SQL Server to accept remote connection](04-Connect-to-Server-Database.md#Enabling-SQL-Server-to-accept-remote-connection)
- [Adding SQL Server connection port in windows firewall](Adding-SQL-Server-connection-port-in-windows-firewall)

# Enabling SQL Server to accept remote connection
![0](/images/0-Remote.png)
To enabling sql server to accept remote connection, follow these steps:
1. Check the **IP Address** of the server.
2. Press the windows button and open **SQL server configuration manager**.<br>
3. Click on **SQL Server Network Configuration**.
4. Click **Protocols for MSSQLSERVER** then select the last option TCP/IP **right-click Enable** and **OK**.
5. Select **SQL Server Service** then **right-click Restart**.
6. Go back and click **TCP/IP** in the properties select **IP Addresses** move down to **TCP Post** enter port number **1433** and **OK**
7. Select **SQL Server Service** and **Restart** again.
![1](/images/1-Remote.png)
SQL Server Configuration Manager is a tool to manage the services associated with SQL Server, to configure the network protocols used by SQL Server, and to manage the network connectivity configuration from SQL Server client computers. It is installed with your SQL Server installation.<br>

![2](/images/2-Remote.png)
![3](/images/3-Remote.png)
# Adding SQL Server connection port in windows firewall
To adding sql server connection port in firewall, follow these steps:
1. Go to search box enter **Windows Security** then click **Advanced setting**. 
2. On the right side of **Inbound rules** click **New Rule..**.
3. In the **New Inbound Rule Wizard** select the second **Port** then **Next**. 
4. In specific local ports enter **1433** then **Next**.
5. Last one give a **name** that the same port number then**Finish**..
![4](/images/4-Remote.png)
![5](/images/5-Remote.png)

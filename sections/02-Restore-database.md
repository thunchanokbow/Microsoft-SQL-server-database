Restore the database in SSMS
============
### Check that this step has been completed before START

![5](/images/05-SSMS.png)
- Launch SSMS
- Connect to the SQL Server
- **Download** the sample database [files](https://github.com/Microsoft/sql-server-samples/releases/tag/wide-world-importers-v1.0)

## To restore a database in SSMS, follow these steps:
![3](/images/03-SSMS.png)

1. Copy the sample database files and locate **the MSSQLSERVER folder in Program Files (x86)**
2. Open the **Backup folder** and add the sample database files to the data files.

![4](/images/04-SSMS.png) 

3. In **Object Explorer, right-click** the Databases node and select Restore Database.
4. In the Restore Database dialog box, select **the Database to restore.**
5. In the **Source section**, select Device and then ***click the ellipsis (...) button*** to locate your backup file.
6. Select **Add and navigate** to where your .bak file is located.
7. Select **the .bak file** and then select **OK**.  
![6](/images/06-SSMS.png)

8. In the Destination section, confirm that the Database box is populated with the name of the database to be restored.
9. To change the name of the database,**enter the new name in the Database box**.
10. In the **Restore options** section, select the following options:
- Overwrite the existing database (WITH REPLACE)
- Close existing connections to destination database
11. Click **OK to start the restore process.**
![7](/images/07-SSMS.png)
![8](/images/08-SSMS.png)

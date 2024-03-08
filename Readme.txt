
 
  Project Title: Migrating Azure Data Lake Australian Road Crashes Data to Azure SQL Database

A.  Data Source: Data Lake
	  File Format: csv


B.  Data Destination: Azure SQL Database 
	

C.  Business requirments:
    Migrate Australian Road Crashes Data from Azure Data Lake to Azure SQL Database
	

D.  Solution Steps: 
   	 -Create RBAC for user to have read/write access to azure storage account files
	 -Establish a connection to data lake gen2 from data factory in microsoft fabric using access key authentication
	 -Establish a connection to azure sql database from data factory using sql admin authentication
   	 -Start copying Roadcrash.csv file data from azure data lake storage to azure sql database
   	 -Confirm the file was copied successfully by running query statement on Roadcrashes table in azure sql database


E.  Tech Stack: 
   	 -Azure Data Lake Gen2
   	 -Azure SQl Database
   	 -Microsoft Fabric (Data Factory persona)


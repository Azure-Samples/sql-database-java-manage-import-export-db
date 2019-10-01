---
page_type: sample
languages:
- java
products:
- azure
description: "Getting Started with Sql - Manage Sql Import Export Database - in Java"
urlFragment: sql-database-java-manage-import-export-db
---

# Getting Started with Sql - Manage Sql Import Export Database - in Java


  Azure SQL sample for managing import/export SQL Database -
   - Create a SQL Server with one database from a pre-existing sample.
   - Create a storage account and export a database
   - Create a new database from a backup using the import functionality
   - Update an empty database with a backup database using the import functionality
   - Delete storage account, databases and SQL Server
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

```bash
git clone https://github.com/Azure-Samples/sql-database-java-manage-import-export-db.git

cd sql-database-java-manage-import-export-db

mvn clean compile exec:java
```

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

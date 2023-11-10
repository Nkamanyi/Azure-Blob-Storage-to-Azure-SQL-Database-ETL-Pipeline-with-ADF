## Blob-Storage-to-SQL-Database-ETL-Pipeline-with-Azure-Data-Factory
In this tutorial, I create a data factory by using the Azure Data Factory user interface (UI). The pipeline in this data factory copies data from Azure Blob storage to a database in Azure SQL Database. The configuration pattern in this tutorial applies to copying from a file-based data store to a relational data store.

In this tutorial, I perform the following steps:
- Create a storage account.
- Create a SQL database.
- Create a data factory.
- Create a pipeline with a copy activity.
- Test run the pipeline.
- Trigger the pipeline manually.
- Trigger the pipeline on a schedule.
- Monitor the pipeline and activity runs.

### Azure Blob Storage with the medals.csv data.
![Azure Blob storage](https://github.com/Nkamanyi/Blob-Storage-to-SQL-Database-ETL-Pipeline-with-Azure-Data-Factory/blob/main/data%20in%20blob%20store.png)

### Create a table in Azure SQL Database.
![Azure Blob storage](https://github.com/Nkamanyi/Blob-Storage-to-SQL-Database-ETL-Pipeline-with-Azure-Data-Factory/blob/main/Create%20a%20table%20in%20sql%20database.png)

### Create a copy pipeline in ADF.
![create a copy pipeline](https://github.com/Nkamanyi/Blob-Storage-to-SQL-Database-ETL-Pipeline-with-Azure-Data-Factory/blob/main/copy%20pipeline.png)

### Monitor the pipeline.
![monitor the pipeline](https://github.com/Nkamanyi/Blob-Storage-to-SQL-Database-ETL-Pipeline-with-Azure-Data-Factory/blob/main/monitor%20pipeline.png)

### Pipeline activity details.
![pipeline activity details](https://github.com/Nkamanyi/Blob-Storage-to-SQL-Database-ETL-Pipeline-with-Azure-Data-Factory/blob/main/activity%20details.png)

![pipeline activity details](https://github.com/Nkamanyi/Blob-Storage-to-SQL-Database-ETL-Pipeline-with-Azure-Data-Factory/blob/main/activity%20detals%202.png)

### Query the data in the SQL database.
![query the data in the database](https://github.com/Nkamanyi/Blob-Storage-to-SQL-Database-ETL-Pipeline-with-Azure-Data-Factory/blob/main/query%20on%20the%20data.png)

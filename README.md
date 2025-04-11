# Databricks-Autoloader

Designed and implemented a medallion architecture on Azure Databricks, using Unity Catalog for data governance and Azure Data Lake Gen2 for storage. Created schemas with Spark SQL, ingested data from ADLS into the Bronze layer, and transformed it into Silver and Gold layers to improve data quality and accessibility for downstream use cases.

Technologies Used
Azure Datapricks
Python, SQL, PySpark, Spark SQL, Spark Structured Streaming
Azure Data Lake Storage Gen2
Unity Catalog
Databricks Autoloader
Schema Enforcement
Check Points and Time Travel
Delta Tables
Delta Lake


ADLS Storage and containers used

![image](https://github.com/user-attachments/assets/ef1f0079-7b3a-410d-b24a-4ddd14ef384e)

External locations created for above containiers

![image](https://github.com/user-attachments/assets/206c6a04-60ae-45a8-aaeb-bd4730e8e034)

1 External credential used here

![image](https://github.com/user-attachments/assets/55cf1738-56d1-4d7d-b8de-25a9683301a7)


Azure Roles

![image](https://github.com/user-attachments/assets/9d20db1b-759a-437b-adb1-aaa59aa22b04)


Databricks Workspace Structure

![image](https://github.com/user-attachments/assets/ffb82ecc-4c1d-4ad1-8c8f-7f8c148ca1ea)


Execute below files in the order after uploading csv files in landing folder

![image](https://github.com/user-attachments/assets/c9807e2b-5871-498e-9c5c-5f22637c3b62)


![image](https://github.com/user-attachments/assets/34847d88-bd66-4428-94f0-c7e9b3f0ad09)

![image](https://github.com/user-attachments/assets/ee215a16-e74f-48b9-84f5-1fc7f87d3017)



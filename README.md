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


Only key parts of Bronze , Silver , Gold and workflow are highlighted here

![image](https://github.com/user-attachments/assets/40b1345e-3c07-4d02-addc-dbc301e62bac)


![image](https://github.com/user-attachments/assets/9afc3bd9-0528-417a-adaa-91b29e0c6fbf)

![image](https://github.com/user-attachments/assets/8e8410c0-6bd3-4536-ac56-f93b1f2f8863)


![image](https://github.com/user-attachments/assets/02aeed37-a674-4752-a6f3-724ff2a770bb)



![image](https://github.com/user-attachments/assets/785779f4-32d1-441d-9bdc-ab00dd44f2df)

![image](https://github.com/user-attachments/assets/35df30a4-ec75-46f4-9756-c69a60971541)



![image](https://github.com/user-attachments/assets/01a418a9-c7d7-4b2d-9f11-78bb2f84bbab)

![image](https://github.com/user-attachments/assets/7bc4872c-0f3e-4644-b694-e8382fc349dd)

![image](https://github.com/user-attachments/assets/d4905c45-df34-4fc8-922b-ee1167eed21a)



![image](https://github.com/user-attachments/assets/77d7df4f-65ad-4b34-93bd-ca0b13eef63d)

![image](https://github.com/user-attachments/assets/013b1cc6-efc3-452f-8026-15dc33ddf831)


![image](https://github.com/user-attachments/assets/58e5ee7f-c1fd-4e05-9d16-b00502fdf19c)


![image](https://github.com/user-attachments/assets/a9b2ef0b-0242-4fdd-bbf2-f8625841321a)


![image](https://github.com/user-attachments/assets/de12d6e1-3498-4674-b0ef-def922273a2e)

![image](https://github.com/user-attachments/assets/907bcb3a-3224-404c-a932-c222920019f5)




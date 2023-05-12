# Airbus_Hackathon


Here is a possible solution and approach to reduce the underlying intermediate data in the system and make the approach of departments using the data more sustainable in the long term:

Create a data lake with a normalized DB to reduce the redundancy.
A data lake is a centralized repository for all data, regardless of its source or format. This allows for the easy storage and access of all data, including intermediate data. By normalizing the data, we can reduce redundancy and improve the accuracy of the data.

Identify the current redundant data from the forecasted data.
Once the data is stored in a data lake, we can use data mining techniques to identify redundant data. This can be done by comparing the data to itself and identifying any duplicate or near-duplicate records.

Create an automation process for data stamping(approval) the real time data.
Once the redundant data has been identified, we can create an automation process to stamp it as "redundant". This will prevent the data from being used by other departments.

Create a dashboard for the users in each domain to access the data required for their domain and also allow the forecast and real time data creation.
We can create a dashboard for each domain that allows users to access the data required for their domain. This dashboard can also be used to create forecast and real time data.

Create a dashboard for the data officer to monitor the data stamping process.
The data officer can use a dashboard to monitor the data stamping process. This will allow them to ensure that the redundant data is being stamped correctly and that it is not being used by other departments.

The following are the technologies that can be used to implement the solution:

Data lake: Apache Hadoop, Apache Spark, Amazon S3, Google Cloud Storage
Data mining: Apache Spark MLlib, Google Cloud Dataproc
Data stamping: Apache Airflow, Google Cloud Dataflow
Dashboards: Apache Superset, Google Data Studio
The following are the evaluation criteria for the solution:

The platform should meet the requirements and be fully functional for the users.
The platform should have authentication and authorization for customers like: ○ User and their department.
Performance and scalability.
Creativity and innovation.
Clarity and quality of the presentation or demonstration.
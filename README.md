# Hive-Hadoop-subproject- Introduction to Hive:

Hive is a data warehousing package built on top of Hadoop.
It began its life at Facebook, processing large amounts of user and Log Data. It's now a Hadoop subproject with many contributors.

Interaction with Hive is thorugh a SQL like query language called HiveQL.
Hive's SQl inspiered language separates the user from the complexity of mapReduce programming.

While Hadoop works on a flat file structure, Hive introduces "partitions" to better manage the data for querying, through a component
called Metastore. If one lets Hive manage the data on Hadoop, it adds compression and structure to the data, to make it better equipped
for queries.

Hive stores metadata in a standard relational database. It comes with a lighweight database called Derby.


Projects: 1. Cloudfront logs - extract and run HiveQL queries on logs generated by web distribution log files.
2. Citation Data - extract data from .txt file and run HiveQL queries on it.

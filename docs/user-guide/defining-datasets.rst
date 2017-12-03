Defining Datasets
-----------------

Sparkflows allows you to define your DataSets. These DataSets are then used in Workflows as data sources. DataSet sources can be local file system when running in local mode, or HDFS & HIVE when running on a Spark cluster.



**Schema**
 
DataSets have Schema defined for them. This allows Sparkflows to create a Spark DataFrame from them in the workflows.
 
File formats
 
Sparkflows support various File formats and is able to infer the schema. These include text files, Parquet files, HIVE etc.
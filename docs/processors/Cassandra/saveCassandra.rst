
SaveCassandra
========== 

Saves the rows of the incoming DataFrame into Cassandra

Type
---------- 

transform

Class
---------- 

fire.nodes.cassandra.NodeSaveCassandra

Fields
---------- 

+----------+-------------------------+----------------------------------------------------+
| Name     | Title                   | Description                                        |
+==========+=========================+====================================================+
| table    | Cassandra Table Name    | Cassandra Table into which data gets loaded        |
+----------+-------------------------+----------------------------------------------------+
| keyspace | Cassandra Keyspace Name | The keyspace where table is looked for             |
+----------+-------------------------+----------------------------------------------------+
| cluster  | Cluster                 | The group of the Cluster Level Settings to inherit |
+----------+-------------------------+----------------------------------------------------+
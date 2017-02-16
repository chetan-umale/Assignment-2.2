Q1-HDFS
answer:
1.HDSF (Hadoop Distributed File System) is a distributed file system designed to run on commodity hardware.
2.HDFS is designed by assuming that regular hardware failures will take place.This is where replication comes into picture.
3.IN HDFS, files are divided into blocks of 128 MB each and stored across a collection of servers across a cluster.
4.This provides redundancy,reliability and also ensures optimim performance.
5.HDFS consists of a master-slave architecture.It has 2 types of nodes - name node(one) and data node(multiple).
6.Name node is the master server that manages the file system namespace and controls the access to files by clients.
7.Name node is also responsible for namespace operations like opening and closing files,renaming files and directories etc.
8.HDFS consistes of multiple data nodes on which the actual blocks are stored.
9.Data nodes handle read and write requests from the client.
10.Data nodes are also responsible for creation,deletion and replication of blocks when instructed by the name node.


Q2.

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


Q2-Hadoop cluster.
answer:
1.Cluster is collection of servers and other computing resources which behaves like a single system having  huge processing power and data storage capabilities.Clusters are used mostly in parallel computing applictaions.
2.Hadoop cluster is special type of cluster which consists of software daemons running on commodity hardware capable of handling large amounts of unstructured data in a distributed computing environment.
3. Hadoop cluster has a master-slave architecture.
4.The name node is the master and  it manages file system namespace.It also controls access to files by client.Only one name node exists in every cluster.
5.Data nodes act as slaves and actually serve the read-write requests from clients.Data nodes actually store the blocks and is responsible for creation,deletion and replication of blocks .


Q3-Hadoop blocks.
answer:
1.A block is the smallest unit of data that can be stored or retrieved from the disk.
2. HDFS also operates in terms of blocks, but the difference is that block size in hdfs is very large as compared to block size in traditional file systems.
3.The size of a typical hadoop block is 128 MB.
4.The blocks are stored on data nodes and have a default replication factor of 3.
5.The blocks are stored in contiguously which reduces the access time significantly.
6.The data nodes are responsible for creation,deletion and replication of these blocks.
7.The metadata associated with hadoop blocks is stored by name node.
8.Because of replication, these blocks ensure high fault tolerance and availability. 



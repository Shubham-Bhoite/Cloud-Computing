# Cloud File System:

-   A cloud file system, also known as a distributed file system or cloud storage system.

-   It is a technology that enables the storage and retrieval of data in a distributed manner across multiple servers or nodes connected over a network.

-  It provides a unified interface to access and manage files and directories as if they were stored on a single storage device, even though the data may be physically distributed across various locations.

## Benefits:
1) Scalability
2) High Availability and Reliability
3) Performance
4) Cost Savings
5) Flexibility and Accessibility

# Types:

## 1) Ghost File System :

-  Amazon Web Services (AWS) uses Ghost cloud File System (CFS).

- GFS run over Amazon's EC2, simpleDB web service and s3.

- GFS is elastic and cost efficient. It is highly secure. It can be mounted on server,client or access files via web page.

## 2) Hadoop File System :
-  Hadoop File System (HDFS) is a distributed file system that is part of the Apache Hadoop framework.
-  It is designed to store and process large amounts of data across multiple machines in a reliable and scalable manner.
-  Handoop Distributed File System is a block - structured file system where each file is divided into blocks Of a pre - determined size. These blocks are stored across a cluster of one or several machines.

## 3) Kosmos File System (KFS) :
-  KFS is an open source project written in C++ by search startup Kosmix.
-  The Kosmos filesystem consists of three components :
a) One or multiple chunk servers that store the data on their own hard disks,
b) A metaserver that keeps an eye on the chunk servers, and
c) An application that quickly gets rid of a single large file.
-  KFS first splits a file into handy 64 MB blocks.
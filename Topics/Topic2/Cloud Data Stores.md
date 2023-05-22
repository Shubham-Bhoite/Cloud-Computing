# Cloud Data Stores:

-   Cloud data stores, also referred to as cloud databases or database as a service (DBaaS), are data storage solutions provided by cloud service providers. 

-   These data stores are designed to store and manage large amounts of data in a cloud computing environment. 

-  Instead of deploying and managing their own physical infrastructure and database systems, organizations can leverage cloud data stores to offload the responsibility of data management to the cloud provider.

# Data Store Types-

## 1) Big Table:

-   Bigtable is a distributed storage system that is used for managing and storing structured data at Google.

-  Bigtable is designed to reliably scale to petabytes of data and thousands of machine. Bigtable has multiple goals like applicability, high availability, scalability,high performance.

-  It is used by approximate sixty Google project or product like Google Analytic,Google Finance, Personalized search, Writely and Google Earth.
## Features-
- Bigtable is a distributed storage system for managing strcutured data.
-  Bigtable uses the distributed Google File System (GFS) to store log and data
files.

-  A Bigtable cluster stores a number of tables. Each table consists of a set of tablets and each tablet contains all data associated with a row range.

## 2) Dynamo:

-  Dynamo is propriety key value structured storage system. It can act as database and also distributed hash table.

-  Dynamo dynamically partitions a set of keys over a set of storage nodes.

-  It is most powerful relational database available in WWW. 
-  Dynamo does not support replication.
-  Dynamo is used to manage high reliability.
-  Dynamo is a completely decuttralized system.
-   Dynamo uses vector clocks in order to capture causality between different versions of the same object.
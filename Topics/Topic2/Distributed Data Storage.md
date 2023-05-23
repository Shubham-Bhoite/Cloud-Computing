# Distributed Data Storage:

## 1) Amazon dynamo -
-  Dynamo stores objects associated with a key through a simple interface; it exposes two operations : get() and put().

- The get(key) operation locates the object replicas associated with the key in the storage system and returns a single object or a list of objects with conflicting versions along with a context.

- The put(key, context, object) operation determines where the replicas of the object should be placed based on the associated key and writes the replicas to disk.

- The context encodes system metadata about the object that is opaque to the caller and includes information such as the version of the object.

-  Dynamo treats both the key and the object supplied by the caller as an opaque array of bytes. It applies a MD5 hash on the key to generate a 128 - bit identifier.

## 2) CouchDB  -

-  Apache CouchDB is open source database software that has a document - oriented NoSQL database architecture and is implemented in the concurrency - oriented language Erlang; it uses JSON to store data.

-  CouchDB is ad-hoc and schema - free with a flat address space. CouchDB comes with a developer - friendly query language and optionally MapReduce for simple, efficient and comprehensive data retrieval.

-  Data is stored within JSON documents which can be accessed and its indices
queried via HTTP.

-  Indexing, transforming and combining of dcxuments are performed through
JavaScript. Because it uses all of these web - friendly standards and technologies,CouchDB works very well with web and mobile applications.

-  CouchDB is designed to store and report on large amounts of semi - structured, document oriented data.

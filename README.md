##VenusDB
It’s a high performance key-value storage library that provides an ordered mapping from string keys to string values.  
* High performance in reading and writing sequentially or random by using hashing & B-tree indexing structure. The average time of random searching a target key in this DB is 6.2 microseconds.  
* Suport real-time inserting new k-v pairs during the searching process with a seamless update based on grouping locks of shared memory.
# datenbankvergleich
Comparaison de bases de données / Vergleich der Datenbanken / Comparison of databases

the information is taken from these source: [Kristof Kovacs](https://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis).
Die Information wurde aus dieser Quelle: [Kristof Kovacs](https://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis) gebracht.
L'information a été prise de cette source: [Kristof Kovacs](https://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis).

## Redis (V3.2)
  
*    Written in: C
*    Main point: Blazing fast
*    License: BSD
*    Protocol: Telnet-like, binary safe
*    Disk-backed in-memory database,
*    Master-slave replication, automatic failover
*    Simple values or data structures by keys
*    but complex operations like ZREVRANGEBYSCORE.
*    INCR & co (good for rate limiting or statistics)
*    Bit and bitfield operations (for example to implement bloom filters)
*    Has sets (also union/diff/inter)
*    Has lists (also a queue; blocking pop)
*    Has hashes (objects of multiple fields)
*    Sorted sets (high score table, good for range queries)
*    Lua scripting capabilities
*    Has transactions
*    Values can be set to expire (as in a cache)
*    Pub/Sub lets you implement messaging
*    GEO API to query by radius (!) 

Best used:
>For rapidly changing data with a foreseeable database size (should fit mostly in memory).

For example:
>To store real-time stock prices. Real-time analytics. Leaderboards. Real-time communication. And wherever you used memcached before. 

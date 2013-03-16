EVCache
=======

EVCache is a memcached & spymemcached based caching solution that is mainly used for AWS EC2 infrastructure for caching frequently used data. 

EVCache is an abbreviation for:
* Ephemeral  - The data stored is for a short duration as specified by its TTL (Time To Live).
* Volatile  - The data can disappear any time (Evicted).
* Cache - An in-memory key-value store.

## Features
* Distributed Key-Value store,  i.e., the cache is spread across multiple instances
* AWS Zone-Aware - Data can be replicated across zones.
* Registers and works with [Eureka] (https://github.com/ScopeCode/eureka/) for automatic discovery of new nodes/services.

##Licence
* Released under an Apache License
* Built by Geoff Momin and is deployed on Scope Play, Netflix, & other unreleased applications.

If you'd like to see your application listed here, email us: info@thescope.tv

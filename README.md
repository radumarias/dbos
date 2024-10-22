# dbos

This is an operating system optimized for hosting a database system, taking advantage of new technologies and benefiting of the new hardware optimizations. The operating system will be designed to run a single workload, a database system, using the minimum possible resources for the operating system itself. The database system will be executed in kernel space, to avoid the overhead of context switching between user space and kernel space.

Everything will be written in Rust to ensure performance, safety and reliability.

# High level components
- hardware abstraction - very thin layer
- multitasking - handling concurrent tasks
- memory management - optimized for the specific database workload
- file system - specialized for the specific database workload
- networking - simplified networking stack with the minimum required features
- database
- monitoring - metrics, logs, etc.
- security
- administration - updates, backups, etc.

# Wiki

[Wiki](https://github.com/radumarias/dbos/wiki)

# Credits

The original idea is of [Andrei Bozântan](https://github.com/andreiBozantan/).

# dbos

This is an operating system optimized for hosting a database system, taking advantage of new technologies and benefiting of the new hardware optimizations. The operating system will be designed to run a single workload, a database system, using the minimum possible resources for the operating system itself. The database system will be executed in kernel space, to avoid the overhead of context switching between user space and kernel space.

Everything will be written in Rust to ensure performance, safety and reliability.

# High level components
- operating system - very thin layer specialized for the database workload
- networking - simplified networking stack with the minimum required features
- file system - specialized for the database workload
- database
- monitoring - metrics, logs, etc.
- security
- administration - updates, backups, etc.

[Wiki](https://github.com/radumarias/dbos/wiki)


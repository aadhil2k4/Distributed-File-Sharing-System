# Chord Algorithm File Sharing System

This project implements a decentralized peer-to-peer file sharing system using the Chord distributed hash table (DHT) protocol. It allows for dynamic node management, efficient file lookup, replication for fault tolerance, and supports various concurrency control mechanisms.

## Features

- **Decentralized Architecture**: No central servers, eliminating single points of failure and scaling efficiently.
- **Efficient Lookup**: Uses Chord protocol's logarithmic lookup for fast file location.
- **File Replication**: Enhances data availability by replicating files across multiple successor nodes.
- **Concurrency Control**: Supports file locking and leases to enable parallel file access.
- **Dynamic Node Management**: Nodes can join or leave without disrupting the network.
- **Failure Handling**: Periodic checks and stabilization routines maintain consistency.
- **Scalability**: Logarithmic routing complexity helps the system scale with the number of nodes.

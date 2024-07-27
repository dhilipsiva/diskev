# DisKeV

![License](https://img.shields.io/badge/license-MIT-blue.svg)

DisKeV is an extremely fast, distributed key-value store designed to be an alternative to Redis. Built with Rust, it leverages Conflict-free Replicated Data Types (CRDTs) to ensure strong eventual consistency.

## Features

- **Distributed by Default**: Built-in support for distributed architectures, ensuring scalability and fault tolerance.
- **Strong Eventual Consistency**: Utilizes CRDTs to guarantee consistency across distributed nodes without sacrificing performance.
- **Versatile Data Types**: Supports a wide range of data types for values, including `bool`, `int`, `float`, `string`, `char`, `list`, and `map`.
- **Configurable Policies**: Flexible replication and partitioning policies to suit various use cases and performance requirements.
- **Blazing Fast Serialization**: Employs FlatBuffers for ultra-fast serialization and deserialization, minimizing overhead and maximizing throughput.
- **Robust Type System**: Strongly typed clients ensure type safety and reduce runtime errors.
- **Actor Model**: Built using the actor model with `ractor` and `ractor-cluster` for efficient concurrency and easy scalability.

## Why DisKeV?

DisKeV is designed to meet the needs of modern distributed systems with the following advantages:
- **Performance**: Rust’s performance and memory safety guarantees make DisKeV an ideal choice for high-throughput, low-latency applications.
- **Consistency**: CRDTs provide a robust framework for eventual consistency, allowing for seamless data synchronization across nodes.
- **Scalability**: Leveraging the actor model with `ractor` and `ractor-cluster`, DisKeV scales effortlessly across multiple nodes, providing high availability and resilience.
- **Flexibility**: Whether you need strong consistency or are optimizing for performance, DisKeV’s configurable policies let you tailor the system to your needs.
- **Ease of Use**: With support for a variety of data types and a strongly typed client interface, integrating DisKeV into your projects is straightforward and error-free.

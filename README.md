**DisKeV** is an extremely fast, distributed key-value store designed to be an alternative to Redis. Built with Rust, it leverages Conflict-free Replicated Data Types (CRDTs) to ensure strong eventual consistency.

## Features

- **Distributed by Default**: Built-in support for distributed architectures, ensuring scalability and fault tolerance through advanced partitioning and replication strategies.
- **Strong Eventual Consistency**: Utilizes CRDTs to guarantee consistency across distributed nodes without sacrificing performance. CRDTs automatically resolve conflicts, minimizing coordination overhead.
- **Versatile Data Types**: Supports a wide range of data types for values, including `bool`, `int`, `float`, `string`, `char`, `list`, and `map`, making it suitable for diverse use cases.
- **Configurable Policies**: Offers flexible replication and partitioning policies to suit various use cases and performance requirements. Configure policies to balance between consistency and performance as needed.
- **Blazing Fast Serialization**: Employs FlatBuffers for ultra-fast serialization and deserialization, minimizing overhead and maximizing throughput. Compared to traditional methods, FlatBuffers provide significant performance gains.
- **Robust Type System**: Strongly typed clients ensure type safety, reducing runtime errors and improving developer productivity.

## Why DisKeV?

DisKeV is designed to meet the needs of modern distributed systems with the following advantages:
- **Performance**: Rust’s performance and memory safety guarantees make DisKeV an ideal choice for high-throughput, low-latency applications. Benchmark tests show DisKeV outperforming traditional key-value stores.
- **Consistency**: CRDTs provide a robust framework for eventual consistency, allowing for seamless data synchronization across nodes without manual conflict resolution.
- **Scalability**: Designed with scalability in mind, DisKeV can effortlessly scale out to accommodate growing workloads. Its distributed nature and efficient data partitioning enable seamless expansion without sacrificing performance.
- **Flexibility**: Whether you need strong consistency or are optimizing for performance, DisKeV’s configurable policies let you tailor the system to your needs. Adapt the replication strategy to match your application’s requirements.
- **Ease of Use**: With support for a variety of data types and a strongly typed client interface, integrating DisKeV into your projects is straightforward and error-free. Example integrations and extensive documentation make onboarding easy.

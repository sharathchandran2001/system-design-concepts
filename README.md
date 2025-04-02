# system-design-concepts

System Design Concepts - An architect's perspective and emphasizing the importance in system design.

1. Client-Server Architecture:

Summary: Defines the fundamental communication pattern where clients request services from servers. Crucial for distributed systems.
Architect's View: Essential for understanding how components interact, impacts scalability, security, and resource management.
2. IP Address:

Summary: Unique numerical label assigned to each device participating in a computer network.
Architect's View: Vital for network routing, load balancing, and understanding communication paths.
3. DNS (Domain Name System):

Summary: Translates domain names (e.g., google.com) to IP addresses.
Architect's View: Critical for service discovery, load balancing, and managing distributed systems.
4. Proxy/Reverse Proxy:

Summary: Proxies act as intermediaries. Forward proxies on the client side, reverse proxies on the server side.
Architect's View: Essential for security (firewalls), load balancing, caching, and request routing.
5. Latency:

Summary: Delay in data transfer.
Architect's View: A key performance metric, impacts user experience, and drives decisions on caching, CDN usage, and network optimization.
6. HTTP/HTTPS:

Summary: Foundation of data communication on the web. HTTPS provides secure communication.
Architect's View: Understanding request/response cycles, headers, methods, and security is vital for building web applications.
7. APIs (Application Programming Interfaces):

Summary: Enable interaction between software applications.
Architect's View: Design APIs for reusability, scalability, and maintainability. REST and GraphQL are common API styles.
8. REST API:

Summary: Architectural style using HTTP methods for data operations.
Architect's View: Focus on statelessness, resource-oriented design, and standardized communication.
9. GraphQL:

Summary: Query language for APIs, enables clients to request specific data.
Architect's View: Provides flexibility, reduces over-fetching, and improves performance for complex data requirements.
10. Databases:

Summary: Organized collection of data.
Architect's View: Choose the right database (relational or NoSQL) based on data structure, scalability, and consistency needs.
11. SQL vs NoSQL:

Summary: SQL for structured data, NoSQL for unstructured or semi-structured data.
Architect's View: Understand trade-offs between consistency, scalability, and flexibility.
12. Vertical Scaling:

Summary: Increasing resources (CPU, RAM) of a single server.
Architect's View: Simple but limited by hardware constraints.
13. Horizontal Scaling:

Summary: Adding more servers to distribute load.
Architect's View: Complex but provides better scalability and fault tolerance.
14. Load Balancers:

Summary: Distribute network traffic across multiple servers.
Architect's View: Essential for high availability and performance.
15. Database Indexing:

Summary: Data structure to improve data retrieval speed.
Architect's View: Balance index size with query performance.
16. Replication:

Summary: Copying data across multiple servers for redundancy and availability.
Architect's View: Choose replication strategies (master-slave, master-master) based on data consistency and performance needs.
17. Sharding:

Summary: Partitioning a database into smaller, manageable pieces (shards).
Architect's View: Complex but crucial for scaling large databases.
18. Vertical Partitioning:

Summary: Dividing a table into multiple tables with fewer columns.
Architect's View: Improves performance by reducing data size.
19. Caching:

Summary: Storing frequently accessed data in memory for faster retrieval.
Architect's View: Improves performance and reduces load on backend systems.
20. Denormalization:

Summary: Adding redundant data to improve read performance.
Architect's View: Trade-off between read performance and data consistency.
21. CAP Theorem:

Summary: States that a distributed system can only guarantee two of Consistency, Availability, and Partition Tolerance.
Architect's View: Understand trade-offs when designing distributed systems.
22. Blob Storage:

Summary: Storage for large, unstructured binary data.
Architect's View: Suitable for images, videos, and other large files.
23. CDN (Content Delivery Network):

Summary: Distributed servers that cache content closer to users.
Architect's View: Improves performance and reduces latency for globally distributed users.
24. WebSockets:

Summary: Provides full-duplex communication over a single TCP connection.
Architect's View: Suitable for real-time applications (chat, gaming).
25. Webhooks:

Summary: User-defined HTTP callbacks triggered by events.
Architect's View: Enables real-time communication between applications.
26. Microservices:

Summary: Architectural style where applications are composed of small, independent services.
Architect's View: Improves scalability, maintainability, and fault tolerance.
27. Message Queues:

Summary: Asynchronous communication mechanism for decoupled services.
Architect's View: Improves reliability and scalability of distributed systems.
28. Rate Limiting:

Summary: Controlling the number of requests a user can make within a given time frame.
Architect's View: Protects against abuse and ensures system stability.
29. API Gateways:

Summary: Single entry point for all API requests, handles routing, security, and monitoring.
Architect's View: Simplifies API management and improves security.
30. Idempotency:

Summary: Ensuring that an operation has the same effect regardless of how many times it's executed.
Architect's View: Critical for reliable distributed systems, especially in payment processing.

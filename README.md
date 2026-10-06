# Thread-Safe-In-Memory-Key-Value-Store-with-LRU-Eviction
Every major system (YouTube, Google Search, Gmail) uses in-memory caches like this to avoid hitting databases repeatedly. Building one shows you understand the fundamentals behind those systems.

 A thread-safe in-memory key-value store implemented in Java with LRU(Least Recently Used) eviction.

 This project demonstrates Java Collections, OOP, generics, LRU caching, and concurrent programming.

 ---
 ## Features

 - Generic key-value storage
 - 0(1) average lookup
 - LRU eviction policy
 - Configurable cache capacity
 - Thread-safe operations
- Support for `put`, `get`, `remove`, and `containsKey`
- Automatic eviction when the cache reaches its capacity
- Generic `K` and `V` types
- Unit testing

  ---
  ## 🧠 What Is This Project?

An in-memory cache stores frequently accessed data in memory so that applications do not need to repeatedly access a database or another slower data source.

Instead of:

```text
Application → Database
Application → Database
Application → Database

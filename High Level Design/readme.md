# High Level Design (HLD) / System Design

System design fundamentals and practice on classic large-scale system design interview problems.

## 📂 Structure

```
HLD/
├── fundamentals/
│   ├── scalability/          # Horizontal vs vertical, load balancing
│   ├── databases/            # SQL vs NoSQL, sharding, replication, indexing
│   ├── caching/               # Cache strategies, eviction policies, CDN
│   ├── message-queues/       # Kafka, RabbitMQ, pub-sub patterns
│   ├── consistent-hashing/
│   ├── cap-theorem/
│   └── api-design/           # REST, GraphQL, rate limiting, pagination
├── problems/
│   ├── url-shortener/
│   ├── rate-limiter/
│   ├── chat-application/
│   ├── news-feed/
│   ├── notification-system/
│   ├── ride-sharing/
│   ├── video-streaming/
│   └── distributed-cache/
└── diagrams/                  # Architecture diagrams (draw.io / excalidraw exports)
```

## 🎯 Standard Approach for Each Problem

1. **Clarify requirements** — functional & non-functional (scale, latency, availability)
2. **Estimate scale** — back-of-envelope: QPS, storage, bandwidth
3. **Define API contract**
4. **High-level architecture** — draw the boxes: clients, load balancer, services, DB, cache
5. **Deep dive into 1–2 components** — e.g., database schema, caching strategy
6. **Identify bottlenecks & trade-offs**
7. **Discuss scaling further** — sharding, replication, async processing

## 📌 Problem Log

| Problem | Key Concepts | Status | Notes |
|---|---|---|---|
| URL Shortener | Hashing, DB design, caching | ⬜ | |
| Rate Limiter | Token bucket, sliding window | ⬜ | |
| Chat Application | WebSockets, message queues | ⬜ | |
| News Feed | Fan-out on write/read, ranking | ⬜ | |

## 🧠 Core Concepts Checklist

- [ ] Load balancing algorithms
- [ ] SQL vs NoSQL trade-offs
- [ ] Caching strategies (write-through, write-back, cache-aside)
- [ ] CAP theorem in practice
- [ ] Consistent hashing
- [ ] Message queues & event-driven architecture
- [ ] Database sharding & replication

## 🔗 Resources

- "Designing Data-Intensive Applications" — Martin Kleppmann
- System Design Primer (GitHub)
- ByteByteGo

## 📝 Notes

Focus on trade-off reasoning over memorized architectures — interviewers care more about *why* than *what*. Keep back-of-envelope calculation shortcuts (e.g., common QPS/storage estimates) in `fundamentals/`.
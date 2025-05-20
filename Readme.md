# System Design Excercises

### Beginner Exercises

**Focus:** Core concepts, basic system components, trade-offs

1. **URL Shortener**
    - Design a service like bit.ly.
    - **Key Concepts:** Hashing, database design, basic API.
2. **Pastebin**
    - Design a tool for sharing text/code snippets.
    - **Focus:** CRUD, data expiration, basic authentication.
3. **Design a Rate Limiter**
    - Implement user request throttling.
    - **Concepts:** Token Bucket, Leaky Bucket, Redis/memory cache.
4. **Design a Notification System**
    - Email/SMS/push notifications.
    - **Components:** Message queue (e.g., RabbitMQ), retry logic.
5. **Design an API Rate Logger**
    - Log and analyze API requests.
    - **Focus:** Data storage (SQL vs NoSQL), indexing, retention policies.  

---

### Intermediate Exercises

**Focus:** Scalability, fault tolerance, consistency, performance
1. **Design Instagram (Core Features)**
    - Posting images, timeline feed, likes.
    - **Topics:** Sharding, data modeling, media storage (S3, CDN).
2. **Design a File Storage System like Dropbox**
    - Upload/download/sync files across devices.
    - **Challenges:** Chunking, versioning, deduplication.
3. **Design a Chat System (e.g., WhatsApp)**
    - 1-on-1 and group messaging.
    - **Concepts:** Real-time communication, WebSockets, message delivery guarantees.
4. **Design a Ride-Sharing System (like Uber)**
    - Matching drivers with riders, real-time tracking.
    - **Topics:** Geo-indexing, matching algorithms, data partitioning.
5. **Design a Real-Time Collaboration Tool (e.g., Google Docs)**
    - Multiple users editing a document simultaneously.
    - **Focus:** Operational transformation, consistency, conflict resolution.  

---

### Advanced Exercises

**Focus:** Distributed systems, CAP theorem, microservices, observability
1. **Design a Scalable Search Engine**
    - Full-text search, ranking, crawling.
    - **Concepts:** Inverted index, MapReduce, distributed crawlers.
2. **Design a YouTube-like Video Streaming Platform**
    - Video upload, transcoding, recommendation engine.
    - **Deep Topics:** CDN design, video chunking, data pipelines.
3. **Design a Distributed Cache System (like Memcached)**
    - Cache eviction, consistency, horizontal scaling.
    - **Trade-offs:** Consistency vs availability, TTL management.
4. **Design a Multi-Region Deployment System**
    - Handle failovers, data replication across continents.
    - **Topics:** Leader election, consensus (Paxos/Raft), eventual consistency.
5. **Design a Monitoring and Alerting System**
    - Metrics collection, dashboards, alerts.
    - **Tools:** Prometheus, Grafana, anomaly detection algorithms.  

---

### Stretch Challenge
1. **Design Your Own Cloud Provider (AWS Lite)**
    - Include compute (VMs), storage (S3), and simple networking.
    - Combine multiple advanced topics into a cohesive architecture.
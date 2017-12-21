# Architecture Bytes (Thursdays)

## 2017-11-02 (Thursday)

### Architecture Byte
**Circuit Breaker Pattern** — Fail fast when downstream services are unhealthy. Monitor error rates and latency, trip on thresholds, then half-open to probe recovery. Prevents cascading failures and improves system resilience.

https://martinfowler.com/bliki/CircuitBreaker.html

---

## 2017-11-09 (Thursday)

### Architecture Byte
**Monolith vs. Microservices** — A monolithic application is built as a single, unified unit. Microservices architecture is an approach where a large application is built as a suite of modular services. Each service runs in its own process and communicates via APIs.

https://martinfowler.com/articles/microservices.html

---

## 2017-11-16 (Thursday)

### Architecture Byte
**CQRS (Command Query Responsibility Segregation)** — CQRS is a pattern that separates read and write operations for a data store. Commands update data, while Queries read data. This can help optimize performance, scalability, and security.

https://martinfowler.com/bliki/CQRS.html

---

## 2017-11-23 (Thursday)

### Architecture Byte
**The Strangler Fig Pattern** — Incrementally replace a legacy system by gradually creating a new system around the edges of the old one. Over time, the new system 'strangles' the old one until it can be safely decommissioned.

https://martinfowler.com/bliki/StranglerFigApplication.html

---

## 2017-11-30 (Thursday)

### Architecture Byte
**The Bulkhead Pattern** — Isolate elements of an application into pools so that if one fails, the others will continue to function. It's like the sectioned partitions of a ship's hull; if one compartment floods, the ship doesn't sink.

https://learn.microsoft.com/en-us/azure/architecture/patterns/bulkhead

---

## 2017-12-07 (Thursday)

### Architecture Byte
**Event Sourcing** — Instead of storing just the current state of the data in a domain, use an append-only store to record the full series of actions taken on that data. This provides a reliable audit log and makes it possible to reconstruct past states.

https://martinfowler.com/eaaDev/EventSourcing.html

---

## 2017-12-14 (Thursday)

### Architecture Byte
**API Gateway** — An API gateway is a single entry point for all clients. It handles requests by routing them to the appropriate microservice, and can also handle concerns like authentication, rate limiting, and logging.

https://microservices.io/patterns/apigateway.html

---

## 2017-12-21 (Thursday)

### Architecture Byte
**Service Discovery** — In a microservices architecture, how do services find each other? Service Discovery patterns (e.g., using tools like Consul or Eureka) provide a way for services to dynamically register and find other services on the network.

https://microservices.io/patterns/service-registry.html

---


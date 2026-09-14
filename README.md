# Engineering Journey 🚀

> **From writing code → building production systems → designing system architecture → becoming a Senior/Staff-level engineer.**

This repository is the single learning system for **Engineering + System Design + System Architecture + AWS + DevOps + Distributed Systems + AI**.

## 🧠 Core Learning Loop

```text
Learn → Build → Measure → Break → Fix → Scale → Document → Explain
```

For every important topic:

- [ ] Learn the concept
- [ ] Practice it
- [ ] Build something with it
- [ ] Deploy it when practical
- [ ] Measure/profile it
- [ ] Introduce a failure or bottleneck
- [ ] Fix and improve it
- [ ] Document the lesson
- [ ] Explain it without notes

---

# 🗺️ Unified Engineering Journey

```text
01 Engineering Fundamentals
        ↓
02 Ruby & Backend Engineering
        ↓
03 Rails Production Engineering
        ↓
04 Database Engineering
        ↓
05 Linux & Operating Systems
        ↓
06 Networking
        ↓
07 Caching & Messaging
        ↓
08 System Design
        ↓
09 System Architecture
        ↓
10 Distributed Systems
        ↓
11 AWS Fundamentals
        ↓
12 AWS System Architecture
        ↓
13 DevOps & CI/CD
        ↓
14 Terraform & Infrastructure as Code
        ↓
15 Observability & Reliability
        ↓
16 Kubernetes & Platform Engineering
        ↓
17 Security Engineering
        ↓
18 AI Engineering
        ↓
19 AI System Design
        ↓
20 Architecture Projects
        ↓
21 Senior/Staff Engineering
```

**System Architecture is integrated into the Engineering Journey, not treated as an isolated subject.**

Detailed architecture curriculum: **[SYSTEM-ARCHITECTURE.md](./SYSTEM-ARCHITECTURE.md)**

---

# 📊 Progress Dashboard

| Phase | Area | Status |
|---|---|---|
| 01 | Engineering Fundamentals | ⬜ Not Started |
| 02 | Ruby & Backend Engineering | ⬜ Not Started |
| 03 | Rails Production Engineering | ⬜ Not Started |
| 04 | Database Engineering | ⬜ Not Started |
| 05 | Linux & Operating Systems | ⬜ Not Started |
| 06 | Networking | ⬜ Not Started |
| 07 | Caching & Messaging | ⬜ Not Started |
| 08 | System Design | ⬜ Not Started |
| 09 | System Architecture | ⬜ Not Started |
| 10 | Distributed Systems | ⬜ Not Started |
| 11 | AWS Fundamentals | ⬜ Not Started |
| 12 | AWS Architecture | ⬜ Not Started |
| 13 | DevOps & CI/CD | ⬜ Not Started |
| 14 | Terraform / IaC | ⬜ Not Started |
| 15 | Observability & Reliability | ⬜ Not Started |
| 16 | Kubernetes / Platform | ⬜ Not Started |
| 17 | Security | ⬜ Not Started |
| 18 | AI Engineering | ⬜ Not Started |
| 19 | AI System Design | ⬜ Not Started |
| 20 | Architecture Projects | ⬜ Not Started |
| 21 | Senior/Staff Engineering | ⬜ Not Started |

### Status convention

- ⬜ Not Started
- 🟡 In Progress
- 🟢 Completed
- 🔵 Needs Review

---

# Phase 01 — Engineering Fundamentals

- [ ] Big-O time complexity
- [ ] Space complexity
- [ ] Arrays
- [ ] Hash tables
- [ ] Sets
- [ ] Stacks
- [ ] Queues
- [ ] Linked lists
- [ ] Trees
- [ ] Heaps
- [ ] Graphs
- [ ] Binary search
- [ ] Two pointers
- [ ] Sliding window
- [ ] Recursion
- [ ] BFS / DFS
- [ ] Sorting algorithms
- [ ] Dynamic programming concepts
- [ ] OOP
- [ ] Composition vs inheritance
- [ ] SOLID
- [ ] Clean code
- [ ] Design principles
- [ ] Error handling
- [ ] Unit testing
- [ ] Integration testing
- [ ] Refactoring
- [ ] Code review
- [ ] Process vs thread
- [ ] Concurrency vs parallelism
- [ ] Race conditions
- [ ] Deadlocks
- [ ] Mutexes / locks
- [ ] Memory basics
- [ ] Git branching
- [ ] Git merge / rebase
- [ ] Git cherry-pick
- [ ] Git reset / revert
- [ ] Git stash
- [ ] Git bisect
- [ ] Git reflog

**Milestone:** Explain complexity and trade-offs before implementing a solution.

---

# Phase 02 — Ruby & Backend Engineering

- [ ] Ruby object model
- [ ] Method lookup
- [ ] Blocks
- [ ] Proc
- [ ] Lambda
- [ ] Modules / mixins
- [ ] Metaprogramming
- [ ] Exceptions
- [ ] Memory management
- [ ] Garbage collection
- [ ] Concurrency
- [ ] Profiling
- [ ] Benchmarking
- [ ] API design
- [ ] Authentication
- [ ] Authorization
- [ ] Background processing
- [ ] Idempotency
- [ ] Rate limiting
- [ ] Error handling
- [ ] Performance optimization

**Milestone:** Understand what Ruby is doing internally, not only its syntax.

---

# Phase 03 — Rails Production Engineering

- [ ] Rails request lifecycle
- [ ] Routing
- [ ] Controllers
- [ ] Models
- [ ] ActiveRecord internals
- [ ] Associations
- [ ] Validations
- [ ] Transactions
- [ ] Locks
- [ ] Connection pooling
- [ ] N+1 queries
- [ ] Service objects
- [ ] Domain boundaries
- [ ] Background jobs
- [ ] Caching
- [ ] ActionCable / WebSockets
- [ ] ActiveStorage
- [ ] Authentication
- [ ] Authorization
- [ ] API versioning
- [ ] Rate limiting
- [ ] Testing strategy
- [ ] Deployment
- [ ] Performance profiling
- [ ] Production troubleshooting

### Architecture progression

```text
CRUD Rails App → Clean Monolith → Modular Monolith → Async Components → Event-driven Components → Selective Services
```

**Milestone:** Build and operate a production-style Rails application.

---

# Phase 04 — Database Engineering

### PostgreSQL

- [ ] SQL fundamentals
- [ ] JOINs
- [ ] CTEs
- [ ] Window functions
- [ ] Constraints
- [ ] Normalization
- [ ] Denormalization
- [ ] Transactions
- [ ] Indexes
- [ ] B-tree
- [ ] GIN / GiST
- [ ] Composite indexes
- [ ] Covering indexes
- [ ] EXPLAIN
- [ ] EXPLAIN ANALYZE
- [ ] Query planner
- [ ] MVCC
- [ ] Locks
- [ ] Isolation levels
- [ ] Connection pooling
- [ ] Replication
- [ ] Read replicas
- [ ] Partitioning
- [ ] Sharding concepts
- [ ] Backup / restore

**Milestone:** Diagnose a slow query and explain the execution plan and trade-off of the fix.

---

# Phase 05 — Linux & Operating Systems

- [ ] Processes
- [ ] Threads
- [ ] Signals
- [ ] Filesystems
- [ ] Permissions
- [ ] Users / groups
- [ ] systemd
- [ ] SSH
- [ ] Cron
- [ ] Environment variables
- [ ] Logs
- [ ] CPU
- [ ] Memory
- [ ] Disk
- [ ] File descriptors
- [ ] Process inspection
- [ ] Network inspection

### Commands

```text
ps  top  htop  free  df  du  vmstat  iostat
ss  curl  dig  grep  awk  sed  find  xargs
journalctl  systemctl  tcpdump
```

**Milestone:** Troubleshoot a Linux server using evidence instead of guesswork.

---

# Phase 06 — Networking

- [ ] OSI model
- [ ] TCP/IP
- [ ] IP addressing
- [ ] CIDR
- [ ] Subnets
- [ ] Routing
- [ ] NAT
- [ ] DNS
- [ ] TCP
- [ ] UDP
- [ ] HTTP/1.1
- [ ] HTTP/2
- [ ] HTTP/3 concepts
- [ ] TLS
- [ ] HTTPS
- [ ] Reverse proxy
- [ ] Forward proxy
- [ ] Load balancer
- [ ] CDN
- [ ] Firewall

**Milestone:** Design the path browser → DNS → CDN → load balancer → application → database.

---

# Phase 07 — Caching & Messaging

### Redis

- [ ] Cache-aside
- [ ] Write-through
- [ ] TTL
- [ ] Eviction
- [ ] Distributed locks
- [ ] Counters
- [ ] Rate limiting
- [ ] Sessions
- [ ] Pub/Sub
- [ ] Sorted sets
- [ ] Leaderboards

### Messaging

- [ ] Queue
- [ ] Pub/Sub
- [ ] Event bus
- [ ] Event stream
- [ ] RabbitMQ
- [ ] Kafka
- [ ] AWS SQS
- [ ] AWS SNS
- [ ] AWS EventBridge
- [ ] At-most-once delivery
- [ ] At-least-once delivery
- [ ] Ordering
- [ ] Retries
- [ ] Dead-letter queues
- [ ] Idempotency
- [ ] Deduplication
- [ ] Backpressure

**Milestone:** Design an asynchronous workflow that remains correct when messages are duplicated or delayed.

---

# Phase 08 — System Design

- [ ] Requirements gathering
- [ ] Functional requirements
- [ ] Non-functional requirements
- [ ] Capacity estimation
- [ ] Latency
- [ ] Throughput
- [ ] Availability
- [ ] Reliability
- [ ] Durability
- [ ] Scalability
- [ ] Fault tolerance
- [ ] CAP theorem
- [ ] PACELC
- [ ] Strong consistency
- [ ] Eventual consistency
- [ ] Load balancers
- [ ] Caches
- [ ] Databases
- [ ] Queues
- [ ] Object storage
- [ ] CDN
- [ ] Search
- [ ] API gateways
- [ ] Rate limiters

### Design practice

- [ ] URL shortener
- [ ] Rate limiter
- [ ] Notification system
- [ ] File storage
- [ ] News feed
- [ ] Chat system
- [ ] Video platform
- [ ] Ride sharing
- [ ] Payment system
- [ ] E-commerce system

**Milestone:** Design an unfamiliar system from requirements through scaling and failure strategy.

---

# Phase 09 — System Architecture 🏗️

Use **SYSTEM-ARCHITECTURE.md** as the detailed curriculum.

- [ ] Architecture fundamentals
- [ ] Quality attributes
- [ ] Layered architecture
- [ ] Modular monolith
- [ ] Hexagonal architecture
- [ ] Clean architecture
- [ ] Domain-driven design concepts
- [ ] Bounded contexts
- [ ] Service boundaries
- [ ] Data ownership
- [ ] API boundaries
- [ ] Communication boundaries
- [ ] Failure boundaries
- [ ] Deployment boundaries
- [ ] Scalability architecture
- [ ] High availability
- [ ] Reliability / resilience
- [ ] Consistency architecture
- [ ] Security architecture
- [ ] Observability architecture
- [ ] Deployment architecture
- [ ] Multi-region architecture
- [ ] Cost architecture
- [ ] Architecture trade-offs
- [ ] Architecture documentation
- [ ] ADRs
- [ ] C4 diagrams

### Architecture method

```text
Requirements → Constraints → Capacity → Boundaries → Data → Communication → Failure → Scale → Security → Operations → Cost → Trade-offs
```

**Milestone:** Produce a defensible production architecture and explain every major decision.

---

# Phase 10 — Distributed Systems

- [ ] Replication
- [ ] Partitioning
- [ ] Sharding
- [ ] Leader / follower
- [ ] Leader election
- [ ] Consensus concepts
- [ ] Distributed locks
- [ ] Distributed transactions
- [ ] Idempotency
- [ ] Eventual consistency
- [ ] Ordering
- [ ] Clock problems
- [ ] Failure detection
- [ ] Outbox pattern
- [ ] Inbox / deduplication
- [ ] Saga pattern
- [ ] CQRS
- [ ] Event sourcing
- [ ] CDC
- [ ] Retry pattern
- [ ] Circuit breaker
- [ ] Bulkhead

**Milestone:** Explain behavior when machines, networks, queues, or databases fail independently.

---

# Phase 11 — AWS Fundamentals

### Compute

- [ ] EC2
- [ ] Auto Scaling
- [ ] ECS
- [ ] Fargate
- [ ] Lambda
- [ ] EKS concepts

### Networking

- [ ] VPC
- [ ] Public / private subnets
- [ ] Route tables
- [ ] Internet Gateway
- [ ] NAT Gateway
- [ ] Security Groups
- [ ] Network ACL
- [ ] ALB
- [ ] NLB
- [ ] Route 53
- [ ] CloudFront

### Data / storage

- [ ] S3
- [ ] EBS
- [ ] EFS
- [ ] RDS
- [ ] Aurora
- [ ] DynamoDB
- [ ] ElastiCache

### Messaging / security

- [ ] SQS
- [ ] SNS
- [ ] EventBridge
- [ ] Kinesis concepts
- [ ] IAM
- [ ] KMS
- [ ] Secrets Manager
- [ ] WAF
- [ ] CloudTrail
- [ ] CloudWatch

**Milestone:** Deploy a secure Rails system on AWS using managed infrastructure where appropriate.

---

# Phase 12 — AWS System Architecture

```text
Level 1: Route 53 → EC2 → RDS
Level 2: Route 53 → CloudFront → ALB → EC2 → RDS
Level 3: CloudFront → WAF → ALB → Auto Scaling → RDS + Redis + SQS + Workers
Level 4: Multi-AZ + replicas + autoscaling + observability + DR
Level 5: Multi-region when business requirements justify it
```

- [ ] AWS Well-Architected Framework
- [ ] Operational excellence
- [ ] Security
- [ ] Reliability
- [ ] Performance efficiency
- [ ] Cost optimization
- [ ] Sustainability
- [ ] Multi-AZ design
- [ ] Disaster recovery
- [ ] Multi-region design
- [ ] AWS service trade-offs

**Milestone:** Defend AWS service choices using requirements, constraints, cost, and failure analysis.

---

# Phase 13 — DevOps & CI/CD

- [ ] CI
- [ ] Automated tests
- [ ] Linting
- [ ] Security scanning
- [ ] Build pipelines
- [ ] Artifact management
- [ ] Deployment workflows
- [ ] Environment promotion
- [ ] Rollbacks
- [ ] Health checks
- [ ] Rolling deployment
- [ ] Blue/green deployment
- [ ] Canary deployment
- [ ] Feature flags
- [ ] Zero-downtime deployment

**Milestone:** Push code → test → build → deploy → verify → rollback safely.

---

# Phase 14 — Terraform & Infrastructure as Code

- [ ] Terraform fundamentals
- [ ] Providers
- [ ] Resources
- [ ] Variables
- [ ] Outputs
- [ ] Modules
- [ ] State
- [ ] Remote state
- [ ] State locking
- [ ] Secrets
- [ ] Environments
- [ ] Drift detection
- [ ] Reusable infrastructure modules

**Milestone:** Recreate an environment from code without manually configuring every resource.

---

# Phase 15 — Observability & Reliability

### Observability

- [ ] Structured logging
- [ ] Metrics
- [ ] Distributed tracing
- [ ] Correlation IDs
- [ ] Request IDs
- [ ] Golden signals
- [ ] SLI
- [ ] SLO
- [ ] SLA
- [ ] Alert design
- [ ] Dashboards
- [ ] OpenTelemetry
- [ ] Prometheus
- [ ] Grafana
- [ ] CloudWatch

### Reliability

- [ ] Timeouts
- [ ] Retries
- [ ] Exponential backoff
- [ ] Jitter
- [ ] Circuit breakers
- [ ] Bulkheads
- [ ] Load shedding
- [ ] Backpressure
- [ ] Graceful degradation
- [ ] Fault isolation
- [ ] Disaster recovery
- [ ] RTO
- [ ] RPO
- [ ] Incident response

**Milestone:** Investigate a simulated production incident using logs, metrics, and traces.

---

# Phase 16 — Kubernetes & Platform Engineering

- [ ] Pod
- [ ] Deployment
- [ ] Service
- [ ] Ingress
- [ ] ConfigMap
- [ ] Secret
- [ ] Namespace
- [ ] StatefulSet
- [ ] DaemonSet
- [ ] Job
- [ ] CronJob
- [ ] HPA
- [ ] RBAC
- [ ] EKS cluster architecture
- [ ] Kubernetes networking
- [ ] Load balancers
- [ ] Autoscaling
- [ ] IAM integration
- [ ] Deployment strategy
- [ ] Observability
- [ ] EC2 vs ECS
- [ ] ECS vs EKS
- [ ] Containers vs Lambda

**Milestone:** Deploy and operate a production-style workload on Kubernetes and justify its operational cost.

---

# Phase 17 — Security Engineering

- [ ] OWASP Top 10
- [ ] Threat modeling
- [ ] Trust boundaries
- [ ] Authentication
- [ ] Authorization
- [ ] OAuth2
- [ ] OIDC
- [ ] JWT trade-offs
- [ ] Session security
- [ ] Secrets management
- [ ] Encryption in transit
- [ ] Encryption at rest
- [ ] IAM
- [ ] Least privilege
- [ ] Network segmentation
- [ ] WAF
- [ ] DDoS protection concepts
- [ ] Audit logging
- [ ] Security monitoring

**Milestone:** Threat-model a production architecture and identify realistic attack paths and mitigations.

---

# Phase 18 — AI Engineering

- [ ] Python for AI engineering
- [ ] LLM APIs
- [ ] Prompt engineering
- [ ] Embeddings
- [ ] Vector search
- [ ] pgvector
- [ ] RAG
- [ ] Hybrid search
- [ ] Reranking
- [ ] Context management
- [ ] Tool calling
- [ ] Agents
- [ ] AI workflow orchestration
- [ ] Streaming responses
- [ ] AI caching
- [ ] Evaluation
- [ ] Guardrails
- [ ] Model fallback
- [ ] AI observability
- [ ] AI cost control

**Milestone:** Build a reliable AI feature with retrieval, evaluation, guardrails, observability, and cost awareness.

---

# Phase 19 — AI System Design

- [ ] LLM gateway
- [ ] Model routing
- [ ] Model fallback
- [ ] Prompt/version management
- [ ] Retrieval architecture
- [ ] Vector database architecture
- [ ] RAG pipelines
- [ ] Agent architecture
- [ ] Tool execution architecture
- [ ] AI queues / async jobs
- [ ] Streaming architecture
- [ ] AI caching
- [ ] AI evaluation pipelines
- [ ] AI safety / guardrails
- [ ] AI cost architecture
- [ ] AI observability

**Milestone:** Design an AI platform that remains reliable and economically viable as usage grows.

---

# Phase 20 — Architecture Projects 🧩

- [ ] URL Shortener
- [ ] Rate Limiter
- [ ] Notification System
- [ ] File Storage System
- [ ] News Feed
- [ ] Chat System
- [ ] Video Streaming Platform
- [ ] Search System
- [ ] Ride Sharing System
- [ ] Payment System
- [ ] E-commerce Platform
- [ ] Learning Management System
- [ ] AI Assistant Platform

For each project:

- [ ] Requirements
- [ ] Assumptions
- [ ] Capacity estimation
- [ ] API design
- [ ] Data model
- [ ] High-level architecture
- [ ] Detailed component design
- [ ] Failure analysis
- [ ] Scaling strategy
- [ ] Security design
- [ ] Observability design
- [ ] Disaster recovery
- [ ] Cost analysis
- [ ] Trade-offs
- [ ] Architecture diagram
- [ ] Implementation / prototype
- [ ] Load/performance experiment
- [ ] Final architecture review

---

# Phase 21 — Senior/Staff Engineering

- [ ] Technical decision making
- [ ] Architecture reviews
- [ ] ADR writing
- [ ] RFC writing
- [ ] Technical documentation
- [ ] Incident leadership
- [ ] Root-cause analysis
- [ ] Mentoring
- [ ] Code review leadership
- [ ] Cross-team communication
- [ ] Technical strategy
- [ ] Roadmap planning
- [ ] Risk management
- [ ] Cost/performance trade-offs
- [ ] Migration planning
- [ ] Legacy modernization
- [ ] Build vs buy decisions
- [ ] Communicating architecture to technical and non-technical stakeholders

**Final milestone:** Drive an ambiguous requirement from requirements → architecture → implementation strategy → deployment → observability → scaling → incident readiness → long-term evolution.

---

# 📅 12-Month Target

| Month | Focus |
|---|---|
| 01 | Fundamentals + Ruby + Rails |
| 02 | PostgreSQL + Redis + performance |
| 03 | Linux + Networking |
| 04 | System Design |
| 05 | System Architecture + Distributed Systems |
| 06 | AWS Fundamentals |
| 07 | AWS Architecture |
| 08 | DevOps + CI/CD + Containers |
| 09 | Terraform + Observability + Security |
| 10 | Kubernetes + EKS |
| 11 | AI Engineering |
| 12 | AI System Design + Architecture Projects |

---

# 🗓️ Weekly Checklist

Target: **~20 hours/week**.

### Monday–Friday

- [ ] 1 hour theory
- [ ] 1 hour coding/practice
- [ ] 1 hour project/experiment

### Saturday

- [ ] 2 hours project
- [ ] 1 hour system design
- [ ] 1 hour review
- [ ] 1 hour documentation

### Sunday

- [ ] Rest
- [ ] Optional 1–2 hour review

### Weekly definition of done

- [ ] Learned the concepts
- [ ] Solved exercises
- [ ] Built/implemented something
- [ ] Performed an experiment
- [ ] Investigated one bottleneck/failure
- [ ] Documented lessons
- [ ] Explained the topic without notes

---

# 📁 Repository Structure

```text
engineering-journey/
├── README.md
├── SYSTEM-ARCHITECTURE.md
├── 01-engineering-fundamentals/
├── 02-ruby-backend/
├── 03-rails/
├── 04-database/
├── 05-linux/
├── 06-networking/
├── 07-caching-messaging/
├── 08-system-design/
├── 09-system-architecture/
├── 10-distributed-systems/
├── 11-aws/
├── 12-aws-architecture/
├── 13-devops/
├── 14-terraform/
├── 15-observability-reliability/
├── 16-kubernetes/
├── 17-security/
├── 18-ai-engineering/
├── 19-ai-system-design/
├── 20-architecture-projects/
└── 21-senior-staff-engineering/
```

Each folder can contain notes, exercises, code, experiments, diagrams, ADRs, and project write-ups.

---

# 🚀 Start Here

Start with **Phase 01 → Ruby/Rails internals → PostgreSQL/Redis**, then move into system design and architecture.

Do not try to learn every technology first. Build while learning.

```text
Single machine
   ↓
Production application
   ↓
Horizontally scaled application
   ↓
Highly available system
   ↓
Distributed system
   ↓
Cloud architecture
   ↓
Global architecture
   ↓
AI-enabled architecture
```

> **The objective is engineering capability, not a technology checklist.**
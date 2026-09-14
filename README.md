# Engineering Journey 🚀

> **From writing code → building production systems → designing system architecture → becoming a Senior/Staff-level engineer.**

## Unified Learning Path

```text
01 Engineering Fundamentals
02 Ruby + Advanced Ruby
03 Rails + Modern Rails + Hotwire + Stimulus
04 JavaScript Core + TypeScript
05 Frontend Framework Engineering
06 PostgreSQL + Database Engineering
07 Linux + Networking
08 Caching + Messaging
09 System Design
10 System Architecture
11 Distributed Systems
12 AWS Fundamentals
13 AWS Architecture
14 DevOps + CI/CD + Containers
15 Terraform + Infrastructure as Code
16 Observability + Reliability
17 Kubernetes + EKS
18 Security Engineering
19 AI Engineering
20 AI System Design
21 Architecture Projects + Senior/Staff Engineering
```

> **Learning loop:** Learn → Practice → Build → Measure → Break → Fix → Scale → Document → Explain.

Detailed architecture track: [SYSTEM-ARCHITECTURE.md](SYSTEM-ARCHITECTURE.md)  
Progress tracker: [LEARNING-CHECKLIST.md](LEARNING-CHECKLIST.md)

---

# 01 — Engineering Fundamentals

- [ ] Big-O time and space complexity
- [ ] Arrays, hashes, sets, stacks, queues
- [ ] Linked lists, trees, heaps, graphs
- [ ] Sorting and searching
- [ ] Recursion and dynamic programming
- [ ] Two pointers and sliding window
- [ ] BFS / DFS
- [ ] OOP
- [ ] Composition vs inheritance
- [ ] SOLID
- [ ] Design patterns
- [ ] Clean code
- [ ] Error handling
- [ ] Unit / integration / contract testing
- [ ] Processes vs threads
- [ ] Concurrency and parallelism
- [ ] Race conditions, deadlocks, mutexes
- [ ] Advanced Git: rebase, cherry-pick, reset, revert, bisect, reflog

**Milestone:** [ ] Explain complexity and engineering trade-offs before implementing a solution.

# 02 — Ruby + Advanced Ruby

### Ruby Core
- [ ] Object model and method lookup
- [ ] Classes and modules
- [ ] Singleton classes
- [ ] Blocks, Proc, Lambda, closures
- [ ] Enumerable internals
- [ ] Exceptions
- [ ] Pattern matching
- [ ] Fibers
- [ ] Threads
- [ ] Ractors concepts

### Ruby Internals
- [ ] VM concepts
- [ ] Object allocation
- [ ] Garbage collection
- [ ] Memory profiling
- [ ] CPU profiling
- [ ] Metaprogramming
- [ ] Performance optimization

**Milestone:** [ ] Explain what happens internally when Ruby executes a method and profile a slow Ruby program.

# 03 — Rails + Modern Rails + Hotwire + Stimulus

### Rails
- [ ] Request lifecycle
- [ ] Routing / controllers / views / models
- [ ] Active Record / Active Model
- [ ] Associations
- [ ] Validations / callbacks / concerns
- [ ] Service and domain objects
- [ ] Transactions
- [ ] Active Job
- [ ] Active Storage
- [ ] Action Mailer
- [ ] Action Cable
- [ ] Caching
- [ ] Sessions
- [ ] Authentication / authorization
- [ ] API design / versioning
- [ ] Rate limiting
- [ ] Security
- [ ] Testing
- [ ] Performance
- [ ] Deployment architecture

### Hotwire
- [ ] Hotwire architecture
- [ ] Turbo Drive
- [ ] Turbo Frames
- [ ] Turbo Streams
- [ ] Turbo Morphing concepts
- [ ] Turbo caching
- [ ] Turbo Native concepts
- [ ] Progressive enhancement
- [ ] Server-rendered interactions
- [ ] Real-time UI with Turbo Streams

### Stimulus
- [ ] Controller lifecycle
- [ ] Actions
- [ ] Targets
- [ ] Values
- [ ] Classes
- [ ] Events
- [ ] Reusable controllers
- [ ] Stimulus + forms
- [ ] Stimulus + Turbo
- [ ] Async interactions
- [ ] UI state management
- [ ] Testing Stimulus behavior

### Architecture
```text
Rails Monolith → Modular Monolith → Async Components → Event-driven Components → Selective Services
```

**Milestone:** [ ] Build a production-quality Rails application using Rails + Hotwire + Stimulus and explain when it is preferable to a SPA.

# 04 — JavaScript Core + TypeScript

### JavaScript Language
- [ ] Variables and scope
- [ ] Primitive vs reference values
- [ ] Objects and arrays
- [ ] Functions and arrow functions
- [ ] Closures
- [ ] `this`
- [ ] call / apply / bind
- [ ] Prototypes and prototype chain
- [ ] Classes and inheritance
- [ ] ESM / modules
- [ ] Destructuring
- [ ] Spread / rest
- [ ] Iterators
- [ ] Generators
- [ ] Symbols
- [ ] Map / Set
- [ ] WeakMap / WeakSet
- [ ] Optional chaining / nullish coalescing

### Runtime + Browser
- [ ] Execution context
- [ ] Call stack
- [ ] Heap
- [ ] Event loop
- [ ] Microtasks / macrotasks
- [ ] Promises
- [ ] async / await
- [ ] Timers
- [ ] Fetch
- [ ] AbortController
- [ ] Web Workers
- [ ] Service Workers concepts
- [ ] DOM
- [ ] Event propagation / delegation
- [ ] Forms
- [ ] Cookies
- [ ] Local / session storage
- [ ] IndexedDB concepts
- [ ] CORS
- [ ] CSP concepts
- [ ] WebSockets
- [ ] SSE
- [ ] Browser rendering pipeline
- [ ] Memory leaks

### Tooling
- [ ] npm / Yarn
- [ ] package.json
- [ ] Vite
- [ ] Bundling
- [ ] Code splitting
- [ ] Tree shaking
- [ ] Source maps
- [ ] Linting / formatting
- [ ] Unit testing
- [ ] Browser testing

### TypeScript
- [ ] Interfaces / type aliases
- [ ] Union / intersection types
- [ ] Generics
- [ ] Literal types
- [ ] Utility types
- [ ] Conditional / mapped types
- [ ] Type narrowing
- [ ] Type guards
- [ ] `unknown` vs `any`
- [ ] Declaration files
- [ ] tsconfig
- [ ] Type-safe API clients

**Milestone:** [ ] Explain the event loop from memory, debug an async race, and build a type-safe application.

# 05 — Frontend Framework Engineering

## React
- [ ] JSX
- [ ] Components / props / state
- [ ] Events
- [ ] Controlled and uncontrolled forms
- [ ] Hooks
- [ ] useState / useEffect / useMemo / useCallback / useRef
- [ ] Custom hooks
- [ ] Context
- [ ] Composition
- [ ] Error boundaries
- [ ] Suspense concepts
- [ ] Concurrent rendering concepts
- [ ] Server Components concepts
- [ ] Client/server state
- [ ] Data fetching
- [ ] Optimistic UI
- [ ] State management
- [ ] Forms and validation
- [ ] Testing
- [ ] Accessibility
- [ ] Performance

## Next.js
- [ ] App Router
- [ ] Routing / layouts
- [ ] Server vs Client Components
- [ ] Server Actions concepts
- [ ] Route handlers
- [ ] Middleware/proxy concepts
- [ ] SSR
- [ ] SSG
- [ ] ISR
- [ ] Streaming
- [ ] Caching
- [ ] Revalidation
- [ ] Metadata
- [ ] Authentication architecture
- [ ] Deployment

## Vue 3
- [ ] Composition API
- [ ] Reactivity
- [ ] ref / reactive / computed / watch
- [ ] Lifecycle
- [ ] Composables
- [ ] Component communication
- [ ] Slots
- [ ] Forms
- [ ] Routing
- [ ] Pinia
- [ ] Performance
- [ ] Testing

## Angular
- [ ] Angular architecture
- [ ] Components / templates
- [ ] Directives
- [ ] Dependency injection
- [ ] Services
- [ ] Signals
- [ ] Reactive forms
- [ ] Routing
- [ ] Guards
- [ ] HTTP client
- [ ] Interceptors
- [ ] RxJS
- [ ] Observables / operators
- [ ] Change detection
- [ ] Standalone components
- [ ] State management
- [ ] Testing
- [ ] Performance

## Frontend Architecture
- [ ] Component architecture
- [ ] Design systems
- [ ] Design tokens
- [ ] Client vs server state
- [ ] API integration
- [ ] Auth flows
- [ ] Loading / empty / error states
- [ ] Optimistic updates
- [ ] Offline-first concepts
- [ ] WebSockets / SSE
- [ ] Performance budgets
- [ ] Core Web Vitals concepts
- [ ] Accessibility / WCAG concepts
- [ ] Internationalization
- [ ] Frontend security
- [ ] Testing strategy
- [ ] Frontend observability

### Framework Decision Practice
- [ ] Rails + Hotwire + Stimulus
- [ ] Rails + React
- [ ] Rails + Vue
- [ ] Rails + Angular
- [ ] Rails API + Next.js

For each: document [ ] when to choose it, [ ] when not to choose it, [ ] performance trade-offs, [ ] operational complexity.

**Milestone:** [ ] Build the same feature with Rails/Hotwire and a SPA framework and defend the architectural choice.

# 06 — PostgreSQL + Database Engineering

- [ ] SQL / joins / CTEs / window functions
- [ ] Constraints
- [ ] Normalization / denormalization
- [ ] ACID / transactions
- [ ] Indexes
- [ ] B-tree / GIN / GiST
- [ ] Composite and covering indexes
- [ ] EXPLAIN / EXPLAIN ANALYZE
- [ ] Query planner
- [ ] MVCC
- [ ] Locks
- [ ] Isolation levels
- [ ] Connection pooling
- [ ] Replication / read replicas
- [ ] Partitioning
- [ ] Backup and recovery
- [ ] Sharding concepts

**Milestone:** [ ] Diagnose and optimize a slow production-style query.

# 07 — Linux + Networking

### Linux
- [ ] Processes / threads / signals
- [ ] Filesystems / permissions
- [ ] systemd / SSH / cron
- [ ] Logs
- [ ] CPU / memory / disk
- [ ] File descriptors
- [ ] Process debugging

### Networking
- [ ] OSI / TCP-IP
- [ ] IP / CIDR / subnets
- [ ] Routing / NAT
- [ ] DNS
- [ ] TCP / UDP
- [ ] HTTP/1.1 / HTTP/2 / HTTP/3 concepts
- [ ] TLS
- [ ] Reverse proxy
- [ ] Load balancing
- [ ] CDN
- [ ] Firewall

**Milestone:** [ ] Explain browser → DNS → CDN → load balancer → application → database.

# 08 — Caching + Messaging

### Redis
- [ ] Cache-aside
- [ ] Write-through
- [ ] TTL / eviction
- [ ] Counters
- [ ] Rate limiting
- [ ] Distributed locks
- [ ] Sessions
- [ ] Pub/Sub
- [ ] Sorted sets / leaderboards

### Messaging
- [ ] Queue
- [ ] Pub/Sub
- [ ] Event bus
- [ ] Event stream
- [ ] RabbitMQ
- [ ] Kafka
- [ ] SQS / SNS / EventBridge
- [ ] Delivery guarantees
- [ ] Ordering
- [ ] Retries / DLQ
- [ ] Idempotency
- [ ] Deduplication
- [ ] Backpressure

**Milestone:** [ ] Design an async workflow that stays correct under duplicate, delayed, and failed messages.

# 09 — System Design

- [ ] Requirements analysis
- [ ] Capacity estimation
- [ ] Latency / throughput
- [ ] Availability / reliability / durability
- [ ] Scalability
- [ ] CAP / PACELC
- [ ] Consistency models
- [ ] Load balancers / caches / queues
- [ ] Object storage / search
- [ ] API gateways / rate limiters

### Design Projects
- [ ] URL shortener
- [ ] Rate limiter
- [ ] Notification system
- [ ] File storage
- [ ] News feed
- [ ] Chat
- [ ] Video platform
- [ ] Search
- [ ] Ride sharing
- [ ] Payment system

# 10 — System Architecture

Use [SYSTEM-ARCHITECTURE.md](SYSTEM-ARCHITECTURE.md) as the detailed architecture curriculum.

- [ ] Architecture fundamentals
- [ ] Application architecture
- [ ] System decomposition
- [ ] API architecture
- [ ] Data architecture
- [ ] Communication architecture
- [ ] Scalability architecture
- [ ] High availability
- [ ] Reliability / resilience
- [ ] Consistency / distributed data
- [ ] Security architecture
- [ ] Observability architecture
- [ ] Deployment architecture
- [ ] AWS system architecture
- [ ] Multi-region architecture
- [ ] Cost architecture
- [ ] AI system architecture
- [ ] Architecture documentation

**Milestone:** [ ] Defend architectural decisions from requirements and trade-offs.

# 11 — Distributed Systems

- [ ] Replication
- [ ] Partitioning
- [ ] Sharding
- [ ] Leader/follower
- [ ] Leader election
- [ ] Consensus concepts
- [ ] Distributed locks
- [ ] Distributed transactions
- [ ] Idempotency
- [ ] Ordering
- [ ] Failure detection
- [ ] Outbox / Inbox
- [ ] Saga
- [ ] CQRS
- [ ] Event sourcing
- [ ] CDC

# 12 — AWS Fundamentals

- [ ] EC2 / Auto Scaling
- [ ] ECS / Fargate
- [ ] Lambda
- [ ] VPC / subnets / routes
- [ ] Internet / NAT gateways
- [ ] Security Groups / NACLs
- [ ] ALB / NLB
- [ ] Route 53 / CloudFront
- [ ] S3 / EBS / EFS
- [ ] RDS / Aurora / DynamoDB
- [ ] ElastiCache
- [ ] SQS / SNS / EventBridge
- [ ] IAM / KMS / Secrets Manager
- [ ] WAF / CloudTrail

# 13 — AWS Architecture

- [ ] Well-Architected thinking
- [ ] Multi-AZ
- [ ] Autoscaling
- [ ] Managed databases
- [ ] Caching
- [ ] Async processing
- [ ] Disaster recovery
- [ ] Multi-region
- [ ] Cost optimization
- [ ] Global architecture

**Milestone:** [ ] Design and defend a production AWS architecture.

# 14 — DevOps + CI/CD + Containers

- [ ] GitHub Actions
- [ ] CI / automated tests
- [ ] Security scanning
- [ ] Artifacts
- [ ] Deployment workflows
- [ ] Rolling / blue-green / canary deployments
- [ ] Feature flags
- [ ] Rollback
- [ ] Docker images / containers
- [ ] Dockerfile
- [ ] Volumes / networks
- [ ] Registries
- [ ] Multi-stage builds

# 15 — Terraform + Infrastructure as Code

- [ ] Providers / resources
- [ ] Variables / outputs
- [ ] Modules
- [ ] State / remote state
- [ ] State locking
- [ ] Secrets
- [ ] Environments
- [ ] Drift
- [ ] Reusable infrastructure modules

# 16 — Observability + Reliability

- [ ] Structured logs
- [ ] Metrics
- [ ] Traces
- [ ] Correlation IDs
- [ ] OpenTelemetry
- [ ] Prometheus
- [ ] Grafana
- [ ] CloudWatch
- [ ] Alerting / dashboards
- [ ] SLI / SLO / SLA
- [ ] Error budgets
- [ ] Health checks
- [ ] Timeouts
- [ ] Retries / jitter
- [ ] Circuit breakers
- [ ] Bulkheads
- [ ] Load shedding
- [ ] Graceful degradation
- [ ] RTO / RPO

# 17 — Kubernetes + EKS

- [ ] Pods
- [ ] Deployments
- [ ] Services
- [ ] Ingress
- [ ] ConfigMaps / Secrets
- [ ] Namespaces
- [ ] StatefulSets
- [ ] DaemonSets
- [ ] Jobs / CronJobs
- [ ] HPA
- [ ] RBAC
- [ ] EKS architecture
- [ ] Networking
- [ ] IAM integration
- [ ] Autoscaling
- [ ] Observability
- [ ] EC2 vs ECS vs EKS vs Lambda

# 18 — Security Engineering

- [ ] OWASP Top 10
- [ ] Threat modeling
- [ ] Authentication / authorization
- [ ] OAuth2 / OIDC
- [ ] JWT trade-offs
- [ ] Session architecture
- [ ] Secrets management
- [ ] Encryption in transit / at rest
- [ ] IAM / least privilege
- [ ] Network segmentation
- [ ] WAF / DDoS concepts
- [ ] Audit logging
- [ ] Security monitoring

# 19 — AI Engineering

- [ ] Python for AI engineering
- [ ] LLM APIs
- [ ] Tokens / context windows
- [ ] Prompt engineering
- [ ] Structured output
- [ ] Embeddings
- [ ] Vector search
- [ ] pgvector
- [ ] RAG
- [ ] Hybrid search
- [ ] Reranking
- [ ] Tool calling
- [ ] Agents
- [ ] Streaming
- [ ] AI caching
- [ ] Evaluation
- [ ] Guardrails
- [ ] Model routing / fallback
- [ ] AI observability
- [ ] AI cost control
- [ ] Rails + LLM integration

# 20 — AI System Design

- [ ] AI gateway
- [ ] Model routing
- [ ] Multi-model architecture
- [ ] RAG architecture
- [ ] Vector database architecture
- [ ] Agent architecture
- [ ] Tool execution
- [ ] Context management
- [ ] Prompt/version management
- [ ] Evaluation pipelines
- [ ] Guardrails
- [ ] Model fallback
- [ ] AI observability
- [ ] AI security
- [ ] AI cost architecture

# 21 — Architecture Projects + Senior/Staff Engineering

For every project complete:

- [ ] Requirements
- [ ] Assumptions
- [ ] Capacity estimation
- [ ] API design
- [ ] Data model
- [ ] Architecture diagram
- [ ] Component design
- [ ] Failure analysis
- [ ] Scaling strategy
- [ ] Security design
- [ ] Observability
- [ ] Disaster recovery
- [ ] Cost analysis
- [ ] Trade-offs
- [ ] ADRs
- [ ] Runbook

### Projects
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

### Senior/Staff Skills
- [ ] Technical decision making
- [ ] Architecture reviews
- [ ] RFC writing
- [ ] ADR writing
- [ ] Technical communication
- [ ] Mentoring
- [ ] Incident leadership
- [ ] Technical strategy
- [ ] Roadmap planning
- [ ] Build vs buy
- [ ] Cost vs reliability decisions
- [ ] Technical debt management
- [ ] Cross-team architecture

---

## ✅ Definition of Done

For important topics, do not mark the checkbox complete after only watching a course.

```text
[ ] Learned
[ ] Practiced
[ ] Built
[ ] Deployed
[ ] Measured
[ ] Tested failure
[ ] Fixed
[ ] Documented
[ ] Explained
```

See `LEARNING-CHECKLIST.md` for detailed progress tracking.

> **Final goal:** Design, build, operate, scale, secure, observe, and explain production systems from a simple application to distributed cloud and AI architectures.
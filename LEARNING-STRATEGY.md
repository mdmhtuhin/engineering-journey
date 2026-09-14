# Learning Strategy 🧭

This document is the persistent learning method for the entire **Engineering Journey**. If a chat, session, or context is lost, return here to recover how the journey should be executed.

## Core Principle

Do not learn technologies as isolated tutorials. Learn them as an engineer:

```text
LEARN → PRACTICE → BUILD → MEASURE → BREAK → FIX → SCALE → DOCUMENT → EXPLAIN
```

A topic is **not complete** because a tutorial was watched.

## Daily Strategy

Target: **3 focused sessions per day, Monday–Friday (~3 hours/day).**

### Session 1 — LEARN (60 min)

- Study one focused topic.
- Understand the concepts, internals, and trade-offs.
- Take concise notes.
- Ask: **Why does this work? When does it fail?**

### Session 2 — BUILD (60 min)

- Code from scratch.
- Solve related problems.
- Implement a small production-style example.
- Avoid copying tutorials line-by-line.

### Session 3 — ARCHITECT (60 min)

- Think about production behavior.
- Analyze scalability, performance, security, reliability, and cost.
- Identify bottlenecks and failure modes.
- Connect the topic to system architecture.

### Daily Formula

```text
LEARN 1h → BUILD 1h → ARCHITECT 1h → REVIEW
```

## Saturday Strategy

Target: **4–5 focused hours.**

```text
2h  → Project implementation
1h  → System design / architecture
1h  → Weekly review
1h  → Documentation + GitHub
```

Use Saturday to integrate the week's knowledge instead of starting many unrelated topics.

## Sunday Strategy

- Rest.
- Optional 1–2 hour review.
- Do not start a major new topic unless necessary.

## Weekly Target

Aim for approximately **18–20 hours/week**.

Consistency is more important than occasional 8–10 hour study days.

## Topic Completion Standard

For every important topic, track:

```text
[ ] Learned
[ ] Practiced
[ ] Built
[ ] Deployed (when applicable)
[ ] Measured
[ ] Broke / tested failure
[ ] Fixed
[ ] Documented
[ ] Explained
```

Only mark the main topic complete when the appropriate depth has been achieved.

## Engineering Thinking

For every technology, progressively ask:

1. What problem does it solve?
2. How does it work internally?
3. What are its limitations?
4. What happens under load?
5. What happens when it fails?
6. How do we observe it?
7. How do we secure it?
8. How do we scale it?
9. What does it cost?
10. What alternatives and trade-offs exist?

## Architecture Progression

Use this sequence whenever designing a system:

```text
Requirement
    ↓
Constraints
    ↓
Capacity estimation
    ↓
Architecture
    ↓
Bottleneck analysis
    ↓
Failure analysis
    ↓
Scaling strategy
    ↓
Security + Observability
    ↓
Cost + Trade-offs
```

## Project Loop

Do not wait until the end of the roadmap to build projects.

```text
Learn concept
    ↓
Build small feature
    ↓
Build production-style component
    ↓
Measure performance
    ↓
Introduce failure/load
    ↓
Fix the problem
    ↓
Scale the design
    ↓
Document the decision
```

Every serious architecture project should eventually contain:

- Requirements
- Assumptions
- Capacity estimation
- API design
- Data model
- Architecture diagram
- Component design
- Failure analysis
- Scaling strategy
- Security design
- Observability
- Disaster recovery
- Cost analysis
- Trade-offs
- ADRs
- Runbook

## Learning Order

Follow the unified roadmap rather than randomly switching technologies:

```text
01 Engineering Fundamentals
        ↓
02 Ruby + Advanced Ruby
        ↓
03 Rails + Modern Rails + Hotwire + Stimulus
        ↓
04 JavaScript Core + TypeScript
        ↓
05 Frontend Framework Engineering
        ↓
06 PostgreSQL + Database Engineering
        ↓
07 Linux + Networking
        ↓
08 Caching + Messaging
        ↓
09 System Design
        ↓
10 System Architecture
        ↓
11 Distributed Systems
        ↓
12 AWS Fundamentals
        ↓
13 AWS Architecture
        ↓
14 DevOps + CI/CD + Containers
        ↓
15 Terraform + Infrastructure as Code
        ↓
16 Observability + Reliability
        ↓
17 Kubernetes + EKS
        ↓
18 Security Engineering
        ↓
19 AI Engineering
        ↓
20 AI System Design
        ↓
21 Architecture Projects + Senior/Staff Engineering
```

## Current Starting Point

The first milestone is to strengthen engineering fundamentals behind existing development experience before moving deeply into AWS, Kubernetes, distributed systems, and AI architecture.

### First Month

**Week 1 — Engineering Fundamentals**
- Big-O and complexity
- Data structures and algorithms
- OOP / SOLID / design patterns
- Processes, threads, concurrency
- Advanced Git

**Week 2 — Advanced Ruby**
- Object model
- Method lookup
- Blocks / Proc / Lambda
- Modules and mixins
- Metaprogramming
- Memory / GC
- Profiling and performance

**Week 3 — Advanced Rails**
- Request lifecycle
- Active Record internals
- Transactions and locking
- N+1 and query performance
- Connection pooling
- Jobs and caching
- Action Cable
- Security / API architecture

**Week 4 — PostgreSQL + Redis**
- SQL and indexing
- EXPLAIN / EXPLAIN ANALYZE
- Transactions / MVCC / locks
- Replication and partitioning concepts
- Redis caching
- TTL / eviction
- Rate limiting
- Distributed locks

## Context-Switching Rule

Do **not** spend one day randomly mixing unrelated technologies such as JavaScript + AWS + Kubernetes.

Instead:

```text
One primary theme
      ↓
Deep learning
      ↓
Hands-on implementation
      ↓
Architecture connection
```

Architecture thinking can be connected to the current theme, but the learning focus should remain coherent.

## 12-Month Direction

A realistic first pass is approximately one year of consistent work:

| Month | Focus |
|---|---|
| 1 | Engineering + Ruby + Rails |
| 2 | JavaScript + TypeScript + Frontend |
| 3 | PostgreSQL + Redis + Backend Performance |
| 4 | Linux + Networking + Messaging |
| 5 | System Design |
| 6 | System Architecture + Distributed Systems |
| 7 | AWS |
| 8 | AWS Architecture |
| 9 | DevOps + CI/CD + Terraform |
| 10 | Observability + Kubernetes |
| 11 | Security + AI Engineering |
| 12 | AI System Design + Architecture Projects |

This is a **strong working-knowledge and hands-on target**, not a promise of mastery. Deep senior/staff maturity requires continued practice beyond the first pass.

## Golden Rules

1. **Do not chase every technology.** Understand the engineering problem first.
2. **Do not just watch tutorials.** Build.
3. **Do not avoid failures.** Deliberately break systems in safe environments.
4. **Measure instead of guessing.** Benchmark, profile, inspect metrics and logs.
5. **Document decisions.** Your GitHub repository is part of the learning process.
6. **Explain what you learned.** If you cannot explain it simply, revisit it.
7. **Prefer depth over context switching.**
8. **Connect implementation to architecture.**
9. **Use the checklist as the progress source of truth.**
10. **Consistency beats intensity.**

## Source of Truth

- Master roadmap: `README.md`
- Persistent learning strategy: `LEARNING-STRATEGY.md`
- Progress tracker: `LEARNING-CHECKLIST.md`
- Detailed architecture curriculum: `SYSTEM-ARCHITECTURE.md`

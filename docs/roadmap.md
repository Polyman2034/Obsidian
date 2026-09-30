# Obsidian — Project Roadmap

## What am I building?

A database engine from scratch in C++.

## Why am I building it?

To understand how database systems work internally instead of
only using databases through APIs and SQL.

## Learning Philosophy

WHY → HOW → CODE

Understand the problem first.
Understand how the system solves it.
Then implement it.

---

# Current Progress

## Stage 0 — Foundation
- [ ] Understand how databases store data
- [ ] Understand files and pages
- [ ] Define initial architecture
- [ ] Set up CMake
- [ ] Create basic test structure

## Stage 1 — Storage Engine
- [ ] Page structure
- [ ] File/page management
- [ ] Record storage
- [ ] Read/write operations

## Stage 2 — Buffer Pool
- [ ] Understand buffer pool
- [ ] Page loading
- [ ] Page eviction
- [ ] Dirty pages

## Stage 3 — Indexing
- [ ] Understand indexing
- [ ] B+ Tree
- [ ] Insert
- [ ] Search
- [ ] Delete

## Stage 4 — Query Execution
- [ ] Query representation
- [ ] Parsing
- [ ] Execution

## Stage 5 — Transactions
- [ ] Transactions
- [ ] Concurrency
- [ ] Isolation

## Stage 6 — Recovery
- [ ] WAL
- [ ] Crash recovery

## Stage 7 — Benchmarking
- [ ] Performance tests
- [ ] Storage benchmarks
- [ ] Index benchmarks
- [ ] Buffer pool benchmarks

---
title: "Projects"
---

## Raft Consensus Core ➡️ [`Report Here!`](/pdfs/raft-core.pdf)

(May 2025 - Present)

- Developed a Go-based **Raft Consensus Core** with **gRPC** for inter-node communication, implementing leader election, heartbeat-based failure detection, log replication to ensure **Strong Consistency** and **Fault Tolerance** across the cluster.
- Integrated **Pebble KV Store** for durable **Write-Ahead Logging** and **LSM Compaction**, guaranteeing **Data Persistence** and enabling seamless **Recovery** after node crashes.
- Designed modular StateMachine API for applying and snapshot-based recovery commands, separating consensus mechanism from application logic.

## Distributed Key-Value Store ➡️ [`Report Here!`](/dist-kv-store/)

(Apr 2025 - May 2025)

- Created a Distributed **Fault-Tolerant** Key-Value Store, written in **Rust**, that automatically replicates data across primary and backup nodes, delivering **High Availability** and horizontal scalability.
- Implemented a self‑healing control plane in **gRPC** with one‑second heartbeats, Lamport‑clock convergence, and zero‑touch **Failover/Migration**, ensuring continuous service under node or network failures.
- Added idempotent **Write‑Ahead Logging** and **Quorum‑based** reads/writes, giving strong ordering, eventual consistency, and fast rejoin recovery without manual intervention.

## OS Kernel Modules

(Jan 2025 - Mar 2025)

- UMIX, a user-mode UNIX-based operating system, is written in **C** programming language.
- Implemented **Coroutine** (User-Level Thread Library), **Process Creation**, **Context Switching** for system calls.
- Designed **CPU Scheduling** Policies including FIFO, LIFO, Round Robin, MLFQ, and Proportional Scheduling.
- Developed Semaphores for **Threads Synchronization**, and integrated **Shared Memory** to support Inter-Process Communication for **Concurrency** functionality of testing application.

## DB Management Kernel

(Jan 2024 - Mar 2024)

- Developed a comprehensive **Database Management System** (DBMS), written in **C++**, by architecting and implementing a multi-layered system from the ground up.
- Built a **Paged File Manager** that performs file‑level operations for rapid record storage and retrieval.
- Implemented a **Relation Manager** and **B+ Tree Indexing** Layer that keeps persistent, multi‑attribute indexes, dramatically speeding up selections, joins, updates, and deletions.
- Unified the record and index layers and created an iterator‑based **Query Engine** that executes SQL queries efficiently, yielding a robust, scalable, high‑performance database system.

## Fabflix (Web Application)

(Apr 2023 – Jun 2023)

- Collaborated in a duo to manage **AWS**, **MySQL**, and **Tomcat** web server, and imported a vast movie database.
- Implemented **20 features** including secure login, cart checkout, bot detection, and SQL injection protection.
- Enhanced website speed by up to **fivefold** through the implementation of several **optimizations**, including MySQL connection pooling and replication and **Apache load balancing**.

## Simple Shell

(Feb 2023 – Mar 2023)

- Developed a custom shell in **C** language with support for foreground and background processes.
- Implemented robust process management, including processing exceptions with **Customized Signal Handlers**.
- Utilized various **Unix functions** to provide a user-friendly interface like **Bash** including Redirection and Pipe, allowing seamless interaction with the operating system.

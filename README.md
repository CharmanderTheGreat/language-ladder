<div align="center">

# 🗺️ Multi-Language Project Roadmap

**8 languages · 160 projects · easy → hardest**
*A structured path from beginner scripts to security tooling.*

![Progress](https://img.shields.io/badge/progress-0%2F160-red)
![Languages](https://img.shields.io/badge/languages-8-blue)
![Focus](https://img.shields.io/badge/focus-networking%20%26%20security-informational)
![Status](https://img.shields.io/badge/status-in%20progress-yellow)

</div>

---

## 📌 About

This repository documents a structured, self-directed learning path toward networking and cybersecurity specialization. It consists of 20 hands-on projects per language, ordered from easiest to hardest, with difficulty increasing gradually toward networking- and security-focused tooling.

Each language has its own directory containing the corresponding project code.

Related repository: [365-days-of-coding](https://github.com/CharmanderTheGreat/365-days-of-coding)

## 🧭 Language Order & Why

| # | Language | Difficulty | Why this order |
|---|----------|:----------:|-----------------|
| 1 | [Python](./python) | 🟢 Easy | Broad general-purpose use; accessible entry point into scripting and security tooling |
| 2 | [Bash](./bash) | 🟢 Easy | Automation-focused; complements Linux/Kali-based workflows |
| 3 | [SQL](./sql) | 🟡 Easy–Mid | Core skill for databases, used across most backend systems |
| 4 | [TypeScript](./typescript) | 🟡 Mid | Builds on JavaScript with type safety for larger applications |
| 5 | [C](./c) | 🟠 Mid–Hard | Low-level understanding of memory and networking fundamentals |
| 6 | [Go](./go) | 🟠 Hard | Modern, concurrent language widely used in networking/backend tooling |
| 7 | [Kotlin](./kotlin) | 🟠 Hard | Mobile development, complementary to Flutter experience |
| 8 | [Rust](./rust) | 🔴 Hardest | Memory-safe systems programming for security tool development |

## 📂 Repo Structure

```
multi-lang-roadmap/
├── python/
├── bash/
├── sql/
├── typescript/
├── c/
├── go/
├── kotlin/
├── rust/
└── README.md
```

Each project resides in its own subfolder, e.g. `python/03-todo-cli/`, with its own README where applicable.

## ✅ Progress Tracker

### 🐍 Python
- [ ] 01. Number guessing game
- [ ] 02. Unit converter (temp, currency, length)
- [ ] 03. To-do list CLI app
- [ ] 04. Password strength checker
- [ ] 05. File organizer script
- [ ] 06. Calculator with GUI (tkinter)
- [ ] 07. Web scraper (headlines)
- [ ] 08. CSV data cleaner/analyzer
- [ ] 09. Random password generator with rules
- [ ] 10. Rule-based chatbot
- [ ] 11. IP address validator/subnet calculator
- [ ] 12. Port scanner (socket)
- [ ] 13. REST API (Flask/FastAPI) — notes app
- [ ] 14. Network device inventory (ping sweep)
- [ ] 15. Log file analyzer
- [ ] 16. Packet sniffer (scapy)
- [ ] 17. Hash cracker (dictionary attack)
- [ ] 18. Keylogger detector (process monitor)
- [ ] 19. Vulnerability report generator (nmap XML)
- [ ] 20. Mini SIEM (log aggregation + alerts)

<details>
<summary>🔧 Bash</summary>

- [ ] 01. Hello world + variables
- [ ] 02. File backup script
- [ ] 03. Disk usage report
- [ ] 04. Bulk file renamer
- [ ] 05. System info dashboard
- [ ] 06. Auto-mount script
- [ ] 07. Cron-based reminder
- [ ] 08. Log rotation script
- [ ] 09. User account automation
- [ ] 10. Firewall rule manager (iptables)
- [ ] 11. Network connectivity checker
- [ ] 12. SSH key deployment script
- [ ] 13. Package update/audit script
- [ ] 14. Website uptime monitor
- [ ] 15. Backup-to-remote (rsync)
- [ ] 16. Failed login monitor (auth.log)
- [ ] 17. Auto-deploy script
- [ ] 18. System hardening checklist
- [ ] 19. Intrusion detection lite
- [ ] 20. Full server setup automation
</details>

<details>
<summary>🗄️ SQL</summary>

- [ ] 01. Basic tables + INSERT/SELECT
- [ ] 02. WHERE, ORDER BY, LIMIT
- [ ] 03. Expense tracker schema
- [ ] 04. JOIN practice
- [ ] 05. Aggregate functions — sales report
- [ ] 06. GROUP BY + HAVING
- [ ] 07. Subqueries
- [ ] 08. Views
- [ ] 09. Indexes / query optimization
- [ ] 10. Foreign keys — library system
- [ ] 11. Transactions — bank transfer sim
- [ ] 12. Stored procedures
- [ ] 13. Triggers
- [ ] 14. Normalize messy dataset (1NF→3NF)
- [ ] 15. Inventory management schema
- [ ] 16. User auth schema (hashed passwords, roles)
- [ ] 17. Audit log table (triggers)
- [ ] 18. Recursive queries (CTE) — org chart
- [ ] 19. Performance tuning (EXPLAIN ANALYZE)
- [ ] 20. Full backend schema (real project)
</details>

<details>
<summary>🔷 TypeScript</summary>

- [ ] 01. Convert JS file to TS
- [ ] 02. Typed to-do list app
- [ ] 03. Interfaces + type unions
- [ ] 04. Typed form validator
- [ ] 05. Generics practice
- [ ] 06. Weather app (typed API)
- [ ] 07. Typed fetch wrapper
- [ ] 08. React + TS component library
- [ ] 09. Typed state management
- [ ] 10. Enum-based permission system
- [ ] 11. Typed REST client (GitHub API)
- [ ] 12. Type guards + discriminated unions
- [ ] 13. Typed Node.js CLI tool
- [ ] 14. Full typed Express API
- [ ] 15. Typed WebSocket chat app
- [ ] 16. Monorepo with shared types
- [ ] 17. Typed dynamic form builder
- [ ] 18. Decorators practice
- [ ] 19. Full typed e-commerce cart
- [ ] 20. Type-safe full-stack app (tRPC)
</details>

<details>
<summary>⚙️ C</summary>

- [ ] 01. Hello world + I/O
- [ ] 02. Simple calculator
- [ ] 03. Sorting algorithms
- [ ] 04. Custom string library
- [ ] 05. Linked list
- [ ] 06. Stack/Queue implementation
- [ ] 07. File I/O
- [ ] 08. Memory management practice
- [ ] 09. Binary search tree
- [ ] 10. Hash table implementation
- [ ] 11. TCP echo server (sockets)
- [ ] 12. TCP chat client-server
- [ ] 13. Simple HTTP server
- [ ] 14. Multi-threaded worker pool (pthreads)
- [ ] 15. Packet crafting (raw sockets)
- [ ] 16. Caesar/XOR cipher
- [ ] 17. Buffer overflow demo (educational)
- [ ] 18. Mini shell implementation
- [ ] 19. Port scanner (raw sockets)
- [ ] 20. Packet filter (libpcap)
</details>

<details>
<summary>🐹 Go</summary>

- [ ] 01. Hello world + syntax
- [ ] 02. CLI to-do list
- [ ] 03. REST API (net/http)
- [ ] 04. Goroutines worker pool
- [ ] 05. File watcher utility
- [ ] 06. JSON parser/formatter CLI
- [ ] 07. URL shortener
- [ ] 08. Web scraper (goquery)
- [ ] 09. Rate limiter middleware
- [ ] 10. Chat server (TCP + goroutines)
- [ ] 11. Concurrent port scanner
- [ ] 12. Reverse proxy
- [ ] 13. REST API + DB + auth
- [ ] 14. Basic load balancer
- [ ] 15. Packet sniffer (gopacket)
- [ ] 16. Microservice with gRPC
- [ ] 17. DNS resolver tool
- [ ] 18. Process isolation demo (namespaces)
- [ ] 19. Distributed key-value store
- [ ] 20. Security scanning tool (subdomain enum + port scan)
</details>

<details>
<summary>📱 Kotlin</summary>

- [ ] 01. Hello world + syntax
- [ ] 02. Calculator app
- [ ] 03. To-do app (Room DB)
- [ ] 04. Unit converter app
- [ ] 05. Weather app (API)
- [ ] 06. Notes app (local storage)
- [ ] 07. Quiz app with scoring
- [ ] 08. Login/signup UI + validation
- [ ] 09. RecyclerView contacts list
- [ ] 10. Camera integration app
- [ ] 11. Location-based app (maps)
- [ ] 12. Local chat UI
- [ ] 13. Expense tracker w/ charts
- [ ] 14. REST API integration (Retrofit)
- [ ] 15. Local + cloud sync (Firebase)
- [ ] 16. Multi-screen nav app
- [ ] 17. Encrypted password manager app
- [ ] 18. WiFi network scanner app
- [ ] 19. Background services app
- [ ] 20. 2FA authenticator app clone
</details>

<details>
<summary>🦀 Rust</summary>

- [ ] 01. Hello world + ownership basics
- [ ] 02. CLI calculator
- [ ] 03. Guessing game
- [ ] 04. To-do CLI (file persistence)
- [ ] 05. Custom string utilities
- [ ] 06. File organizer CLI
- [ ] 07. JSON parser (serde)
- [ ] 08. Password generator CLI
- [ ] 09. In-memory key-value store
- [ ] 10. Multi-threaded task runner
- [ ] 11. TCP echo server (tokio)
- [ ] 12. Async port scanner
- [ ] 13. HTTP server (axum/actix-web)
- [ ] 14. File encryption tool (AES)
- [ ] 15. Parallel hash cracker (rayon)
- [ ] 16. Packet sniffer (pnet)
- [ ] 17. REST API + DB integration
- [ ] 18. Reverse proxy/load balancer
- [ ] 19. WebAssembly module
- [ ] 20. Nmap-lite security scanner
</details>

## 🛠️ Tech Stack per Language

| Language | Key Tools/Libraries |
|----------|---------------------|
| Python | `scapy`, `flask`/`fastapi`, `tkinter`, `beautifulsoup4` |
| Bash | `iptables`, `rsync`, `cron`, `systemd` |
| SQL | PostgreSQL / MySQL, `EXPLAIN ANALYZE` |
| TypeScript | React, Node.js, Express, tRPC, Zustand |
| C | `pthreads`, `libpcap`, raw sockets |
| Go | `net/http`, `gopacket`, `gRPC`, `goroutines` |
| Kotlin | Room, Retrofit, Firebase, Jetpack Navigation |
| Rust | `tokio`, `serde`, `rayon`, `axum`, `pnet` |

## 🎯 Goal

Develop end-to-end capability to build networking and security tools — from an initial script to a fully custom scanner — while accumulating skills across multiple paradigms: scripting, OOP, systems programming, memory-safe development, mobile development, and databases.

---

<div align="center">

Part of a broader development journey — see also [365-days-of-coding](https://github.com/CharmanderTheGreat/365-days-of-coding)

</div>
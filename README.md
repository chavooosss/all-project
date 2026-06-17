# Veli Ercan — Developer Portfolio

**High school student · Distributed Systems · Cybersecurity · Rust · Python**  
📍 Ankara, Turkey · 🔗 [GitHub](https://github.com/chavooosss) · HackerOne: active

> I have been writing code since I was 10 years old — self-taught, no courses, learning by building.  
> My focus for the last 2 years: distributed systems and cybersecurity.

---

## 🏆 Signature Project

### [Zenith Grid OS](https://github.com/chavooosss/zenith) — Distributed Computing Platform
*Rust · Raft Consensus · Reed-Solomon Erasure Coding · mTLS · Docker*

Zenith merges the CPU, RAM, and storage of multiple devices into a single unified grid — like turning three weak computers into one powerful machine.

**What makes it real:**
- Written entirely in **Rust** for memory safety and C-level performance
- **Raft consensus algorithm** — if one node crashes, the others elect a new leader automatically
- **Reed-Solomon erasure coding** — data is split into 9 chunks; even if 4 are lost, the full data is recoverable
- **3-node Docker cluster** tested and verified: nodes discover each other, elect a leader, and replicate key-value data across all nodes in under 3 seconds
- 305 passing tests · 11 crates · ~33,000 lines of Rust · CI pipeline (Linux + Windows + ARM64 + Docker)
- Enterprise features: JWT auth, RBAC, audit logging, WASM plugin sandbox, dashboard (TR/EN)

This project started as a Python prototype. After hitting the limits of Python for cross-platform distributed systems, I rewrote it from scratch in Rust. The rewrite took over a year of solo work.

---

## 🔒 Cybersecurity

### SpecterAI — Autonomous Bug Bounty Agent
*Python · LangGraph · FastAPI · React · HackerOne API*

An AI agent that autonomously performs reconnaissance, scans targets, and generates structured vulnerability reports. Integrates with HackerOne and Intigriti platforms.

- Agent architecture with reasoning loop (LangGraph state machine)
- Tools: nmap, subfinder, httpx, nuclei, dirsearch, custom HTTP
- Scope validator prevents out-of-scope testing
- React + Tailwind GUI with live terminal output
- SQLite persistence for findings and sessions

### SmartCUPP — Intelligent Wordlist Generator
*Python · BloomFilter · Multiprocessing · Hashcat*

An upgraded version of the CUPP wordlist generator used in penetration testing.

- BloomFilter-based deduplication (zero duplicate entries at scale)
- Multiprocessing for parallel generation
- Priority-ordered output (most likely passwords first)
- Hashcat Strategy Engine integration

### Real-World Bug Bounty — QinetiQ (HackerOne Report #3723675)
*Reconnaissance · Shodan · nmap · Responsible Disclosure*

Found an unprotected Hikvision NVR camera management panel exposed on the network of **QinetiQ** — one of the UK's largest defense technology companies. Reported responsibly through HackerOne's VDP program.

Methodology: fully terminal-based — amass, nmap, Shodan, curl. No GUI tools.

---

## 🖥️ Systems & Infrastructure

### CoreControl — Enterprise Smartboard Management System
*Python · FastAPI · JWT · SQLite · Master/Worker Architecture*

A centralized management server for controlling multiple smartboards across a network. Built for real use in a school environment.

- Master server with JWT authentication and role-based access
- Worker agents that register, receive commands, and report status
- FastAPI REST API with full CORS support
- SQLite persistence for device registry and session management

### YARDIMCI ASİSTAN (Linux) — Voice Assistant
*Python · Modular Architecture · Service-Oriented Design*

A fully local voice assistant for Linux with a layered service architecture.

- Services: audio, browser control, file manager, reminders, media, system monitor
- Session and skill management
- Runs entirely offline — no cloud APIs

---

## 📊 Data & Finance

### BIST Trading Analysis Toolkit
*Python · Pandas · Technical Analysis*

A comprehensive toolkit for analyzing stocks on Borsa İstanbul (Turkish stock exchange).

- Channel scanning (trend detection across multiple timeframes)
- Pattern recognition: Bull flags, Head & Shoulders, OBO/TOBO formations
- Indicators: EMA, LSMA, moving bands
- Individual stock deep-scan and correlation analysis
- Used for real investment research

### Spotify Analyzer
*TypeScript · React · Node.js · Spotify API*

A full-stack web application that analyzes Spotify listening history and generates personality insights.

- React frontend with Recharts visualizations
- Components: Music DNA, Mood Scatter Plot, Artist Network, Pattern Heatmap, BPM Chart
- Node.js + TypeScript backend with Spotify OAuth
- AI Personality card based on listening patterns

---

## 🎮 Games & Creative

### SpaceShooter3D
*C++ · Raylib · 3D Graphics · Object Pooling · Spatial Hashing*

A 3D space shooter game built from scratch in C++.

- Custom 3D model rendering
- Object pooling for performance
- Spatial hash grid for collision detection
- Audio manager, highscore system, pause menu

### KernelSurvivor
*C++ · Game Engine Architecture*

A survival game where the player navigates a system under attack — themed around OS internals.

- Custom game engine components: SystemMonitor, Player, Enemy, Projectile
- Debug tooling and changelog tracking

---

## 🔐 Security Research & Low-Level

### SecureVault
*C++ · AES Encryption · Custom Implementation*

A file encryption vault implemented in C++ from scratch. Custom AES implementation with key management.

### NexusERP — Stock Management System
*Python · Flask/FastAPI · SQLite · Modular Architecture*

A small business ERP system for inventory and stock tracking.

- Module system: backup manager, database engine, security utilities
- Clean architecture with separated concerns

---

## 🛠️ Skills & Tools

**Languages:** Rust · Python · C++ · TypeScript  
**Distributed Systems:** Raft consensus · Reed-Solomon erasure coding · Gossip protocol · mTLS · NAT traversal  
**Security:** Penetration testing · Bug bounty (HackerOne) · Network reconnaissance · Responsible disclosure  
**Infrastructure:** Docker · Linux · CI/CD · SQLite · JWT/RBAC  
**Tools:** nmap · amass · Shodan · dirsearch · Wireshark · Burp Suite

---

## 📌 About

I started programming at age 10 — not through courses or bootcamps, but by building things, breaking them, and figuring out why. Every project here was built solo or in very small teams.

My long-term goal is to work at a major global technology company or a prominent defense technology firm. I am currently a high school student in Ankara, Turkey.

I am open to collaboration, mentorship, and community events.

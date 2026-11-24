<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,6,11&height=220&section=header&text=Hi%2C%20I'm%20Blckros%C3%A9%20%E2%9C%A8&fontSize=42&fontAlignY=35&desc=Principal%20Systems%20Architect%20%E2%80%A2%20Database%20Engineer%20%E2%80%A2%20Rust%20Specialist&descAlignY=58&descAlign=50&animation=fadeIn" width="100%"/>
</p>

<p align="center">
  <a href="https://github.com/Blckrose08/theresavdb"><img src="https://img.shields.io/badge/RDBMS-TheresavDB-00f2fe?style=for-the-badge&logo=rust&logoColor=white" alt="TheresavDB"></a>
  <a href="https://github.com/Blckrose08/watcher"><img src="https://img.shields.io/badge/Engine-Theresav_Watcher-ff6b6b?style=for-the-badge&logo=rust&logoColor=white" alt="Theresav Watcher"></a>
  <a href="https://github.com/Blckrose08/rosedb"><img src="https://img.shields.io/badge/KV_Store-RoseDB-a855f7?style=for-the-badge&logo=rust&logoColor=white" alt="RoseDB"></a>
  <a href="https://crates.io/crates/theresavdb-client"><img src="https://img.shields.io/badge/crates.io-0.1.1-orange?style=for-the-badge&logo=rust" alt="crates.io"></a>
  <a href="https://pypi.org/project/theresavdb/"><img src="https://img.shields.io/badge/PyPI-0.1.1-blue?style=for-the-badge&logo=pypi" alt="PyPI"></a>
  <a href="https://www.npmjs.com/package/@theresav/db"><img src="https://img.shields.io/badge/npm-0.1.1-red?style=for-the-badge&logo=npm" alt="npm"></a>
  <a href="https://hub.docker.com/r/blckrose08/theresavdb"><img src="https://img.shields.io/badge/Docker_Hub-latest-2496ED?style=for-the-badge&logo=docker" alt="Docker"></a>
</p>

---

### 🚀 About Me

```rust
struct Developer {
    name: &'static str,
    role: &'static str,
    focus: Vec<&'static str>,
    flagship_systems: Vec<&'static str>,
    motto: &'static str,
}

impl Developer {
    fn new() -> Self {
        Self {
            name: "Blckrosé (Blckrose08)",
            role: "Systems Architect & Database Engineer",
            focus: vec![
                "Database Engine Internals (Storage, MVCC, WAL, ARIES)",
                "Cross-Platform Filesystem Watchers & Event Loops",
                "High-Concurrency Distributed Systems",
                "High-Performance Asynchronous Rust (Tokio)",
                "Low-Latency Binary Wire Protocols",
            ],
            flagship_systems: vec![
                "TheresavDB (Independent Relational Database Management System)",
                "Theresav Watcher (High-Performance Filesystem Watching Engine)",
                "RoseDB (Embedded Key-Value & Document Database)",
            ],
            motto: "Building zero-compromise, memory-safe, ultra-fast data systems.",
        }
    }
}
```

---

### 🌟 Flagship Systems & Repositories

| System / Repository | Language | Description & Architecture | Badges & Links |
|---|---|---|---|
| **[TheresavDB](https://github.com/Blckrose08/theresavdb)** | **Rust** | Independent, high-performance RDBMS from scratch. 16 KiB Slotted Page, B-Tree index, MVCC Snapshot Isolation, ARIES WAL recovery, and dual-mode (Embedded & Tokio TCP Server). | [![crates.io](https://img.shields.io/crates/v/theresavdb-client.svg?style=flat-square&color=blue)](https://crates.io/crates/theresavdb-client) [![PyPI](https://img.shields.io/pypi/v/theresavdb.svg?style=flat-square&color=blue)](https://pypi.org/project/theresavdb/) [![npm](https://img.shields.io/npm/v/@theresav/db.svg?style=flat-square&color=blue)](https://www.npmjs.com/package/@theresav/db) [![Docker](https://img.shields.io/badge/docker-hub-blue.svg?style=flat-square&logo=docker)](https://hub.docker.com/r/blckrose08/theresavdb) |
| **[Theresav Watcher](https://github.com/Blckrose08/watcher)** | **Rust** | Independent, high-performance, cross-platform filesystem watching engine in Rust. Real-time file system notification abstraction for high-throughput reactive pipelines. | [![Repo](https://img.shields.io/badge/GitHub-watcher-ff6b6b?style=flat-square&logo=github)](https://github.com/Blckrose08/watcher) [![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)](https://github.com/Blckrose08/watcher/blob/master/LICENSE) |
| **[RoseDB](https://github.com/Blckrose08/rosedb)** | **Rust** | High-performance embedded Key-Value & Document database engine written in Rust with official bindings for Bun, Node.js, Go, and Python. | [![Repo](https://img.shields.io/badge/GitHub-rosedb-a855f7?style=flat-square&logo=github)](https://github.com/Blckrose08/rosedb) [![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)](https://github.com/Blckrose08/rosedb/blob/master/LICENSE) |

---

### ⚡ TheresavDB Showcase

<p align="center">
  <a href="https://github.com/Blckrose08/theresavdb">
    <img src="https://raw.githubusercontent.com/Blckrose08/theresavdb/master/assets/theresavdb-banner.png" alt="TheresavDB Banner" width="95%"/>
  </a>
</p>

- **Core Storage:** 16 KiB slotted binary page with in-place compaction (`1,308,000+ ops/sec`).
- **Index Engine:** Custom B-Tree with sub-microsecond point lookups (`0.107 µs / op`).
- **Durability:** ARIES crash recovery engine with 34-byte record CRC32C WAL logging (`121+ MB/s`).
- **Zero-Dependency Clients:** Native drivers in **Rust** (`theresavdb-client`), **Python** (`theresavdb`), and **Node.js/Bun** (`@theresav/db`).

👉 **[View TheresavDB Source Code →](https://github.com/Blckrose08/theresavdb)**

---

### 🛠️ Tech Stack & Tooling

<p align="center">
  <img src="https://skillicons.dev/icons?i=rust,tokio,c,cpp,linux,docker,bash,git,github,postgres,mysql,py,ts,nodejs,bun&theme=dark" alt="Tech Stack Icons"/>
</p>

| Category | Technologies & Tools |
|---|---|
| **Core Systems & Backend** | `Rust`, `Tokio`, `C/C++`, `Python`, `TypeScript`, `Node.js`, `Bun` |
| **Databases & Storage** | `TheresavDB`, `RoseDB`, `PostgreSQL`, `MySQL / InnoDB`, `SQLite`, `Redis` |
| **Infrastructure & DevOps** | `Linux (Ubuntu / Debian)`, `Docker`, `GitHub Actions CI/CD`, `Git` |
| **Architecture Specialties** | `Slotted Pages`, `B-Tree`, `MVCC`, `ARIES WAL`, `Filesystem Watchers`, `Binary Wire Protocols`, `2PL Concurrency` |

---

### 📊 GitHub Activity & Streak

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Blckrose08&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Blckrose08 GitHub Stats" width="48%"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Blckrose08&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" width="48%"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Blckrose08&theme=tokyonight&hide_border=true" alt="GitHub Streak" width="96%"/>
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,6,11&height=100&section=footer" width="100%"/>
</p>

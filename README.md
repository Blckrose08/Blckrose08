<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,6,11&height=220&section=header&text=Hi%2C%20I'm%20Blckros%C3%A9%20%E2%9C%A8&fontSize=42&fontAlignY=35&desc=Principal%20Systems%20Architect%20%E2%80%A2%20Database%20Engineer%20%E2%80%A2%20Rust%20Specialist&descAlignY=58&descAlign=50&animation=fadeIn" width="100%"/>
</p>

<p align="center">
  <a href="https://github.com/Blckrose08/theresavdb"><img src="https://img.shields.io/badge/Featured_Project-TheresavDB-00f2fe?style=for-the-badge&logo=rust&logoColor=white" alt="TheresavDB"></a>
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
    flagship_project: &'static str,
    motto: &'static str,
}

impl Developer {
    fn new() -> Self {
        Self {
            name: "Blckrosé (Blckrose08)",
            role: "Systems Architect & Database Engineer",
            focus: vec![
                "Database Engine Internals (Storage, MVCC, WAL, ARIES)",
                "High-Concurrency Distributed Systems",
                "High-Performance Asynchronous Rust (Tokio)",
                "Low-Latency Binary Wire Protocols",
            ],
            flagship_project: "TheresavDB (Independent Relational Database)",
            motto: "Building zero-compromise, memory-safe, ultra-fast data systems.",
        }
    }
}
```

---

### 🌟 Flagship Project: TheresavDB

<p align="center">
  <a href="https://github.com/Blckrose08/theresavdb">
    <img src="https://raw.githubusercontent.com/Blckrose08/theresavdb/master/assets/theresavdb-banner.png" alt="TheresavDB Banner" width="95%"/>
  </a>
</p>

An independent, high-performance **Relational Database Management System (RDBMS)** built entirely from scratch in Rust (not a fork or wrapper of PostgreSQL or SQLite).

- **Core Storage Engine:** 16 KiB slotted binary page with in-place defragmentation (`1.3M+ ops/sec`).
- **Index Engine:** Custom B-Tree with sub-microsecond point lookups (`0.107 µs / lookup`).
- **Durability & Logging:** ARIES crash recovery engine with 34-byte record CRC32C WAL logging (`121+ MB/s`).
- **Concurrency & MVCC:** Multiversion Concurrency Control (MVCC) with Snapshot Isolation & 2PL Deadlock DFS detection.
- **Ecosystem:** Dual-mode (Embedded in-process & TCP daemon) with official drivers in **Rust** ([crates.io](https://crates.io/crates/theresavdb-client)), **Python** ([PyPI](https://pypi.org/project/theresavdb/)), **Node.js/Bun** ([npm](https://www.npmjs.com/package/@theresav/db)), and **Docker** ([Docker Hub](https://hub.docker.com/r/blckrose08/theresavdb)).

👉 **[Explore TheresavDB on GitHub →](https://github.com/Blckrose08/theresavdb)**

---

### 🛠️ Tech Stack & Tooling

<p align="center">
  <img src="https://skillicons.dev/icons?i=rust,tokio,c,cpp,linux,docker,bash,git,github,postgres,mysql,py,ts,nodejs,bun&theme=dark" alt="Tech Stack Icons"/>
</p>

| Category | Technologies & Tools |
|---|---|
| **Core Systems & Backend** | `Rust`, `Tokio`, `C/C++`, `Python`, `TypeScript`, `Node.js`, `Bun` |
| **Databases & Storage** | `TheresavDB`, `PostgreSQL`, `MySQL / InnoDB`, `SQLite`, `Redis` |
| **Infrastructure & DevOps** | `Linux (Ubuntu / Debian)`, `Docker`, `GitHub Actions CI/CD`, `Git` |
| **Architecture Specialties** | `Slotted Pages`, `B-Tree`, `MVCC`, `ARIES WAL`, `Binary Wire Protocols`, `2PL Concurrency` |

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

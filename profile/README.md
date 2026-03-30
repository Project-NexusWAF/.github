<p align="center">
  <img alt="Project NexusWAF" src="https://raw.githubusercontent.com/Project-NexusWAF/.github/main/assets/nexuswaf-logo-light.svg" width="380">
</p>

<p align="center">
  <b>An Intelligent, Multi-Layer Zero-Trust Web Application Firewall</b>
</p>

<p align="center">
  <a href="https://github.com/Project-NexusWAF/nexus-core/releases">
    <img src="https://img.shields.io/github/v/release/Project-NexusWAF/nexus-core?style=flat-square&color=blue&label=release" />
  </a>
  <a href="https://github.com/Project-NexusWAF/.github/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/Project-NexusWAF/nexus-core?style=flat-square" />
  </a>
  <a href="https://github.com/Project-NexusWAF/nexus-core">
    <img src="https://img.shields.io/github/stars/Project-NexusWAF/nexus-core?style=flat-square&color=yellow" />
  </a>
</p>

<p align="center">
  <a href="#architecture">Architecture</a> •
  <a href="#repositories">Repositories</a> •
  <a href="#features">Features</a> •
  <a href="#roadmap">Roadmap</a> •
  <a href="#contributing">Contributing</a>
</p>

---

# About Project NexusWAF

**Project NexusWAF** is a structured, intelligent Web Application Firewall designed for modern distributed environments.

Built with a strict separation between **data plane and control plane**, NexusWAF integrates deterministic rule enforcement, formal grammar-based request parsing, and machine learning inference into a cohesive zero-trust security platform.

The system is engineered for:

- High performance
- Structured traffic analysis
- Hot policy reload
- Modular microservice deployment
- Enterprise-grade extensibility

---

# Core Philosophy

- 🔐 Zero-Trust Request Validation
- 🧠 Deterministic + Intelligent Hybrid Detection
- 🌳 Grammar-Aware Traffic Parsing
- ⚙️ Modular Microservice Architecture
- 🔄 Dynamic Policy Management
- 📊 Observability-First Design

---

# 🛠️ Technology Stack

| Layer | Technology | Purpose |
|-------|------------|---------|
| Language | Rust | Data plane & control plane |
| Runtime | Tokio | Async I/O |
| Protocol | gRPC | Inter-service communication |
| ML Runtime | ONNX | Model inference |
| Database | PostgreSQL | Rules & audit storage |
| Frontend | Next.js | Admin interface |
| Observability | Prometheus | Metrics |

---
# 🤝 Contributing

We welcome contributions from developers, researchers, and security engineers.

Ways to contribute:

- Report issues
- Improve documentation
- Suggest new detection strategies
- Optimize parsing performance
- Expand ML classification models

Development setup instructions are available in individual repository READMEs.

---

# 📜 License

Project NexusWAF is released under the MIT License.

---

<p align="center">
  <sub>Engineered with precision for structured, intelligent application security.</sub>
</p>

<p align="center">
  ⭐ Star the project if you find it valuable.
</p>

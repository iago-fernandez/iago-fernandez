# Iago Fernández

**BSc in Mathematics** and **BSc in Computer Engineering**  
Santiago de Compostela / Vigo, Spain  

[Website](https://iagofernandez.dev) · [LinkedIn](https://linkedin.com/in/iago-fernandez-perlo/) · [Curriculum Vitae](assets/%5BEN%5D%20CV_Iago_Fernandez.pdf) · [Contact](https://iagofernandez.dev/contact)

---

### Overview

Software engineer and researcher working in systems programming and applied mathematics. My work centers on high-performance computing, numerical optimization, and low-level software design in C and C++, where latency, memory hierarchy, and algorithmic efficiency are primary constraints.

Currently working as a Software Engineering Intern and Researcher at [RAPOSa](https://raposa.cesga.es) (CITMAga), focusing on solver integrations, algebraic reformulations, and high-performance software for polynomial global optimization. In parallel, I am completing my bachelor's theses in Mathematics and Computer Engineering at Universidade de Santiago de Compostela, while deepening my understanding of computer systems architecture and hardware-level performance.

My focus is on domains requiring mathematical rigor and systems efficiency, including High-Frequency Trading (HFT), high-performance computing (HPC), and low-level infrastructure.

---

### Technical Competencies

* **Primary Languages:** C, C++ (C++17/C++20). Supporting languages: Rust, Python.
* **Low-Level and Systems:** Linux system calls, POSIX concurrency, `epoll` event loops, non-blocking I/O, cache hierarchy optimization (L1/L2 locality and contiguous layout), atomics, lock-free data structures, zero-copy memory buffers.
* **Mathematical Foundations:**
  * *Optimization and Solvers:* Linear Programming (LP / Simplex), Convex Optimization, Non-linear Programming (NLP), Second-Order Cone Programming (SOCP), Semidefinite Programming (SDP), Reformulation-Linearization Technique (RLT), mixed-integer non-linear programming (MINLP), branch-and-bound search trees.
  * *Pure and Applied Mathematics:* Numerical linear algebra, abstract algebra, differential equations, topology, complex analysis, probability and statistics, discrete mathematics.
* **Infrastructure and Tooling:** Linux (bare-metal Arch / Debian), CMake, Make, Ninja, Cargo, Docker, WireGuard, Git, GitLab CI/CD, GDB, Valgrind, Pyomo.
* **Languages:** English (Full professional proficiency / C1 fluent), Spanish (Native), Galician (Native).

---

### Selected Projects

| Project | Stack | Key Engineering Highlights |
| :--- | :--- | :--- |
| **[async-network-engine](https://github.com/iago-fernandez/async-network-engine)** | C, Linux Kernel, epoll | Asynchronous TCP network engine built directly on Linux `epoll` with edge-triggered event notifications. Implements non-blocking sockets, zero-copy lock-free ring buffers, and disabled Nagle's algorithm (`TCP_NODELAY`) for predictable microsecond-level tail latency. |
| **[pyomo-conic](https://github.com/iago-fernandez/pyomo-conic)** | Python, Optimization, PyPI | Conic optimization extension published on [PyPI](https://pypi.org/project/pyomo-conic/). Bridges `pyomo.environ` with native Second-Order Cone and Semidefinite solvers (Clarabel, Mosek), exporting mathematical formulations to CBF and AMPL for AC Optimal Power Flow (AC-OPF) research. |
| **[3d-game-of-life](https://github.com/iago-fernandez/3d-game-of-life)** | C++17, OpenGL 3.3 | Cellular automata simulation on a 3D toroidal manifold ($T^2$). Parallelized state updates across CPU threads with a contiguous, cache-aligned memory layout to maximize L1/L2 cache line utilization and eliminate cache thrashing. |
| **[home-library-api](https://github.com/iago-fernandez/home-library-api)** | Rust, Axum, PostgreSQL | Production-grade backend engineered around compile-time type safety and concurrency. Uses SQLx for compile-time verified database queries, connection pooling, and structured domain-driven error handling. |
| **[dfa-visualizer](https://github.com/iago-fernandez/dfa-visualizer)** | Algorithms, Graphviz | Formal automata compiler and graph layout engine mapping regular grammars to Deterministic Finite Automata with runtime state validation. |
| **[homelab](https://github.com/iago-fernandez/homelab)** | Linux, Docker, WireGuard | Self-hosted bare-metal infrastructure operating 24/7. Configured with a Zero-Trust WireGuard tunnel, reverse-proxy network isolation, and declarative container management. |

---

### Experience

* **Software Engineering Intern / Researcher** at [RAPOSa](https://raposa.cesga.es) (CITMAga) (Oct 2025 - Present)  
  Transitioned solver communication (IPOPT, KNITRO) from file-based I/O to direct in-memory C++ APIs to eliminate disk bottlenecks. Integrated the Clarabel solver via its native C/C++ API for second-order cone (SOCP) and semidefinite (SDP) relaxations. Implemented RLT reformulations and multi-core C++ parallelization of the branch-and-bound tree on the CESGA supercomputer.
* **Software Engineering Intern** at Technica Engineering Spain (Jun 2026 - Sep 2026)  
  Engineered a Python Model Context Protocol (MCP) server with HTTP streaming and token authentication, modeled automotive network protocols (SOME/IP, TCP/IP, TLS), and integrated CI/CD security scanning.

---

### Education

* **BSc in Mathematics and BSc in Computer Engineering (Dual Degree)** at Universidade de Santiago de Compostela (2020 - 2027 expected)  
  Undergraduate theses: *Polynomial Optimization with Semidefinite Constraints* (Mathematics) and *Software Architectures for Global Solvers* (Computer Science).
* **Erasmus+ Exchange Program** at Uniwersytet Łódzki, Poland (2025 - 2026)  
  Academic focus on information security, artificial intelligence, and advanced analysis.

---

### Focus and Next Steps

Currently focused on core solver engineering at RAPOSa and completing undergraduate theses at USC.

Preparing for engineering and research opportunities starting in 2027 upon graduation, with a focus on High-Frequency Trading (HFT), quantitative engineering, high-performance computing, and systems infrastructure.

<div align="center">

# Hi there 👋, I'm Ayush Sharma

### Software Engineer • Cybersecurity Researcher • Systems Programmer

🎓 **B.Tech in Computer Science and Engineering @ IIT Guwahati**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white)](https://linkedin.com/in/ayush-sharma-9993942a6)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:ayush.sharma@iitg.ac.in)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AYUSHSHARMA9817)

</div>

---

# 👨‍💻 About Me

- 🎓 B.Tech in **Computer Science & Engineering** at **IIT Guwahati** (CGPA: 8.20)
- 🥉 Ranked **3rd (Bronze Medal) among 23 IITs** at **Inter IIT Tech Meet 14.0 (Cybersecurity Challenge)**
- 🏆 **JEE Advanced 2023** AIR 907 | **JEE Mains 2023** AIR 762
- 💻 **Competitive Programming:** Codeforces Specialist (Max Rating: 1562)
- 🔐 Passionate about **Systems Programming, Core Cybersecurity, Compiler Design, and Protocol Development**
- 🌱 Currently learning **Deep Learning for Computer Vision, Speech Processing, and Software Analysis**

---

# 💼 Experience

### Cybersecurity Research Intern (Human Factors)
**Zeron** *(Dec 2025)*

- Architected the core analysis engine for the **Human Security Exploitability System (HSES)** using Python and FastAPI, calculating real-time cyber-risk scores based on live user inputs.
- Formulated rule-based algorithms integrating CVE data, CWE frameworks, and custom scoring weights to map behavioral signals to cognitive states (Stress, Fatigue) and predict exploit susceptibility.
- Engineered synthetic telemetry pipelines and contextual modifiers to automate the validation of exploitability conditions without live enterprise data.

---

# 🚀 Featured Projects

---

## 🛡️ PacketGuard – Deep Packet Inspection (DPI) Analyzer
**C++ • Linux Raw Sockets • Qt6 • CMake • Multithreading**

Engineered a custom Deep Packet Inspection (DPI) engine in C++ utilizing Linux raw sockets (AF_PACKET) to detect TCP anomalies and Layer 7 exploits (SQLi, XSS).

### Highlights
- 🔹 Payload analysis algorithm calculating Shannon Entropy to identify encrypted malware data exfiltration.
- 🔹 Thread-safe producer-consumer architecture using `std::mutex` and `poll()` for non-blocking capture.
- 🔹 Automated deployment via CMake and CPack for sudo-less execution (cap_net_raw).
- 🔹 Custom GUI built with Qt6.

---

## 🔐 PQC-DTLS 1.3 for Bare-Metal RISC-V IoT Devices (QTrino)
**C • RISC-V • DTLS 1.3 • wolfCrypt • LiteX • Verilator**

> 🥉 **Ranked 3rd among all IITs at Inter IIT Tech Meet 14.0 (Cybersecurity)**

Designed a post-quantum secure DTLS 1.3 channel on a 1MHz RISC-V client integrating ML-KEM-512 and ML-DSA-44 primitives via wolfCrypt.

### Highlights
- 🔹 Post-Quantum Cryptography Integration
- 🔹 Session Resumption via Pre-Shared Keys (PSK), reducing latency by 3.5x.
- 🔹 Simulated hardware-software co-design using LiteX and Verilator.
- 🔹 71% reduction in CPU cycles during reconnection.

---

## ⚙️ CxxCover – Clang/LLVM Static Analyzer & Instrumenter
**C++ • LLVM • Clang AST**

Built a Clang-based C++ coverage instrumenter leveraging AST traversal and `clang::Rewriter` to inject execution-tracking probes at the source-expression level.

### Features
- ✅ Expression-level AST traversal
- ✅ 100% detection of 340 expected logical conditions across a 50-program corpus
- ✅ Custom runtime utilizing `std::vector` for execution tracking
- ✅ Source-level condition mapping validation against gcov CFGs

---

## 🔍 SolSentry – Solidity Program Analysis Framework
**Python • Solidity • AST Parsing • Gemini AI**

Built a static analysis pipeline extracting solc ASTs, achieving a 0.93 F1 score for Unchecked Calls and 0.77 F1 (100% recall) for Reentrancy on the SmartBugs dataset.

### Features
- ✅ Interactive AI Verification module using Gemini to prune Control Flow Graphs (CFGs)
- ✅ Semantically filters false positives
- ✅ Operation-level IRs for rigorous cross-call Checks-Effects-Interactions validations without live EVM execution

---

## 🌐 SpeedRunEthereum – Advanced EVM Concepts
**Solidity • Scaffold-ETH 2 • DeFi**

Engineered stateful protocol logic across multiple Solidity builds, implementing core DeFi primitives.

### Topics Covered
- Decentralized Exchanges (DEXs)
- Lending Platforms & Stablecoins
- Complex ERC20 allowance flows
- Zero-Knowledge (ZK) privacy-preserving voting flows

---

# 🛠️ Tech Stack

### 💻 Programming Languages

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

---

### ⚙️ Frameworks, Tools & OS

![LLVM](https://img.shields.io/badge/LLVM-000000?style=for-the-badge&logo=llvm&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Qt](https://img.shields.io/badge/Qt-41CD52?style=for-the-badge&logo=qt&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

### 🔐 Systems & Security

![Static Analysis](https://img.shields.io/badge/Static_Analysis-2E8B57?style=for-the-badge)
![Clang AST](https://img.shields.io/badge/Clang_AST-663399?style=for-the-badge)
![DTLS 1.3](https://img.shields.io/badge/DTLS_1.3-4B0082?style=for-the-badge)
![wolfSSL](https://img.shields.io/badge/wolfSSL-00599C?style=for-the-badge)
![RISC-V](https://img.shields.io/badge/RISC--V-283272?style=for-the-badge)
![Verilator](https://img.shields.io/badge/Verilator-0F4C81?style=for-the-badge)

---

# 📊 GitHub Analytics

<div align="center">

</div>

<div align="center">

<img src="https://streak-stats.demolab.com?user=AYUSHSHARMA9817&theme=github-dark&hide_border=true"/>

</div>

---

# 🏆 Achievements

🥉 **Inter IIT Tech Meet 14.0 (Cybersecurity)** — Rank **3rd (Bronze Medal)** among 23 IITs (2025)

💻 **Competitive Programming** — Codeforces Specialist (Max Rating: 1562)

🏅 **JEE Advanced 2023** — AIR **907** (Among 0.2 million students)

🏅 **JEE Mains 2023** — AIR **762** (Among 1.2 million students)

🎓 **CBSE Board** — 96.0% in Senior Secondary (2023) | 97.8% in Secondary (2021)

---

# 🌱 Currently Learning

- Deep Learning for Computer Vision
- Speech Processing
- Software Analysis
- Systems Architecture & Optimization
- Advanced Cryptography

---

# 📫 Connect With Me

<div align="center">

<a href="https://linkedin.com/in/ayush-sharma-9993942a6">
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="mailto:ayush.sharma@iitg.ac.in">
<img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="https://github.com/AYUSHSHARMA9817">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github"/>
</a>

</div>

---

<div align="center">

### 💡 Favorite Quote

> *"Programs must be written for people to read, and only incidentally for machines to execute."*

**— Harold Abelson**

---

⭐ **If you find any of my projects useful, consider giving them a star!**

</div>

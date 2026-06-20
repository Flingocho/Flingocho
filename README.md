<div align=center>
<img src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExMTNteGYyMnpseGtmeW4xaWU4a2JteDVqcmk2NGFrNTN4cXA3bzFscyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/Wo0Yw7qwzgQak/giphy.gif" width="500px">

## 👋 Yeah, it's Flingocho
</div>

## 🚀 About Me (The Pitch & The Pivot)

Software Developer with one foot in data engineering, another in Web3, and both eyes on system architecture. Currently finishing the **"Expert in IT Architecture"** Master's program at [**42 Madrid**](https://www.42madrid.com/), specializing in Algorithms, AI, Web, and Databases.

**🎵 Lead Developer @ [Music Stocks](https://musicstocks.io)** — A Web3 platform for trading music royalty participation rights, built on blockchain and smart contracts. I drive the technical stack end to end: TypeScript, native mobile (Swift/Kotlin migrating to React Native), CI/CD pipelines, and AWS deployment. 
> ⚠️ **VC & Compliance Update:** Transitioning to **100% Full-Time dedication** next month to eliminate operational risk, ensure 24/7 infrastructure availability, and lead our pre-launch scaling phase.

**📊 Data Science Engineer @ Telefónica Tech** *(Tenure ending next month to focus entirely on Music Stocks)* — Building and maintaining BI reporting pipelines across the Microsoft 365 / Power BI / Power Query stack, with SQL on Snowflake and Salesforce Analytics. Moving on from turning messy sales data into actionable corporate insights to scale financial infrastructure full-time.

Outside of that, I spend a suspicious amount of free time on 42's systems-level rabbit holes — questioning my life choices somewhere around the third all-nighter, but coming out the other side with something that actually works. 🙄

---

## 🛡️ Engineering, Security & Compliance Posture
*How I bridge the gap between "Move Fast" and "Don't Get Exploited" for Music Stocks:*
*   **Secure-by-Design Smart Contracts:** Designing tokenomics and royalty transactional ledgers with a zero-trust approach to mitigate smart contract vulnerabilities.
*   **Operational Resilience (DORA-Ready):** Leveraging my IT Architecture background to design fault-tolerant microservices, immutable logging, and automated failure recovery on AWS.
*   **Data Governance & Privacy:** Applying enterprise-grade data management principles (learned at Telefónica Tech) to ensure full **GDPR** compliance regarding user ledger transactions and off-chain data.

---

<details open>
<summary>🧠 Highlight Project — Gomoku AI</summary>

<div align="center">
  <img src="https://raw.githubusercontent.com/Flingocho/gomoku/main/imgs/main_menu.png" width="350px">
  <img src="https://raw.githubusercontent.com/Flingocho/gomoku/main/imgs/game.png" width="350px">
</div>

[`gomoku`](https://github.com/Flingocho/gomoku) — A full-featured **Gomoku (Five-in-a-Row)** game on a 19×19 board, with a serious AI engine. This one's actually impressive, I say with zero humility.

**What's under the hood:**
- Dual AI implementations: **C++17** and **Rust** (via FFI), switchable from the main menu -> *Demonstrating secure memory management and cross-language interoperability.*
- **Minimax + Alpha-Beta pruning** with Iterative Deepening and a 64MB Zobrist transposition table
- Adaptive search depth by game phase (opening → 6, midgame → 8, endgame → 10)
- Move ordering: history heuristic, killer moves, geometric/centrality bonuses
- Full rule engine: captures, double free-three prohibition, breakable five-in-a-row
- **SFML GUI** — 1000×800, particle effects, glow, hover indicators, winning line highlight
- Colorblind mode, sound/music system, in-game AI move suggestions
- **148 unit tests** covering both implementations and verifying C++/Rust parity -> *Strict QA standards.*

`C++ · Rust · SFML · Algorithmic Optimization`

</details>

---

<details open>
<summary>🐜 Highlight Project — Lem-in (Ant Colony Pathfinding)</summary>

<div align="center">
  <img src="https://github.com/Flingocho/lem-in/raw/master/images/intricate.png" width="350px">
  <img src="https://github.com/Flingocho/lem-in/raw/master/images/visualizer.png" width="350px">
</div>

[`lem-in`](https://github.com/Flingocho/lem-in) — Pure graph theory: route a colony of ants through a network of rooms and tunnels from start to end in the **minimum number of moves**. No shortest-path-for-one-ant nonsense — this is multi-path flow optimization.

**What's under the hood:**
- **Multi-path BFS** to discover every viable route from start room to end room
- **Greedy flow distribution**: assigns ants across discovered paths to minimize total completion time, not just path length -> *Core logic directly applicable to transactional transaction routing / order matching.*
- **Collision-aware simulation**: step-by-step movement with room-occupancy checks, so no two ants ever overlap
- Robust graph parsing with duplicate-room and invalid-connection detection
- **Python visualizer** (matplotlib) with anti-overlap line rendering for untangling dense, intricate maps
- Scales to 1000+ rooms / 3000+ connections in benchmarks, still resolving in milliseconds

`C · Python · BFS · Graph Theory · Concurrency Logic`

</details>

---

## 🏆 Other Interesting Projects

*A curated selection across the stack — proof-of-work in infrastructure, security, and complex systems.*

- [`jvidal-t-IoT`](https://github.com/Flingocho/jvidal-t-IoT) — **Inception of Things**: Full GitOps/DevOps pipeline from scratch. Vagrant-provisioned VMs running K3s clusters, Ingress routing, K3d for Docker-based orchestration, and Argo CD for continuous deployment — syncing app state from a Git repo to the cluster automatically. The kind of thing people get paid to set up. *(Shows my capability to build secure, immutable production pipelines for FinTech deployment).* `Kubernetes · GitOps · ArgoCD · Infrastructure-as-Code`

- [`ft_transcendence`](https://github.com/Flingocho/transcendence) — Full-stack web browser game: real-time multiplayer Pong, chat, user management, and matchmaking. The final boss of the Common Core, and the closest thing to a production web app the cursus throws at you. *(Real-time duplex communication, crucial for asset-trading tickers).* `TypeScript · WebSockets · State Synchronization`

- [`libasm`](https://github.com/Flingocho/libasm) — Low-level Assembly reimplementation of standard libc functions, with loop unrolling, memory alignment tricks, and hand-optimized x86-64. Actually kind of fun. `Assembly x86-64 · Low-Level Optimization`

- [`learn2slither`](https://github.com/Flingocho/learn2slither) — Reinforcement learning, the hard way: a snake agent learns to survive and eat using a **Q-table** (no neural net shortcuts here). Trained over **300k cycles**, converging around episode 500, the agent reaches a max score of **54**. `Python · Q-Learning · Reinforcement Learning`

- [`Leaffliction`](https://github.com/Flingocho/Leaffliction) — Computer vision pipeline for **plant disease recognition** from leaf images: dataset analysis, augmentation, and image transformation/feature extraction. `Python · Computer Vision · Image Processing`

---

<details open>
<summary>⚛️ Side Quest — Quantum Computing</summary>

[`ftl_quantum`](https://github.com/Flingocho/ftl_quantum) — A personal deep-dive into quantum computing, done in Jupyter notebooks because sometimes you just want to think, not fight a compiler. (Tested on real IBM quantum hardware).

Covers the fundamentals bottom-up:
- **EX00 - EX02**: Superposition, Entanglement (Bell states), and Quantum Noise/decoherence models.
- **EX03 - EX04**: Deutsch-Jozsa and Grover's Algorithm (unstructured search in $O(\sqrt{N})$).

The cat was alive... and angry. 🐈‍⬛

`Python · Qiskit · Jupyter · OpenQASM`

</details>

---

<details open>
<summary>💡 R&D & Cybersec PoCs</summary>

- [`audio_pill_injection`](https://github.com/Flingocho/audio_pill_injection) — **Forensic Audio Watermarking PoC:** Tracks audio leaks by injecting an inaudible ultrasonic "pill" (25kHz square wave) into audio files at unique timestamps. If the file leaks, the spectrogram reveals the source. *(Direct application to asset tracking and IP protection in Music Stocks).* `Python · Digital Signal Processing · Security`

- [`freeze_stalker`](https://github.com/Flingocho/freeze_stalker) — WhatsApp bot that scrapes a website and takes a screenshot. Sandboxed environment, zero production security overhead, exactly as advertised. `JavaScript`

- [`noname_project`](https://github.com/Flingocho/noname_project) — Scripts for a game I'll build someday. If I don't die first.

</details>

---

## 📫 How to Reach Me

- **Email:** [jaimevidalt.24@gmail.com](mailto:jaimevidalt.24@gmail.com) (I might even reply)
- **LinkedIn:** [jaime-vidal-tejada](https://linkedin.com/in/jaime-vidal-tejada-7560b52a6) (no ghostwriters, no "thoughts?" engagement bait, I promise)
- **GitHub Issues:** For any "constructive" feedback on my projects, feel free to open an issue.

Feel free to navigate through the labyrinth of my repositories — a testament to the pain and suffering that is learning to code. You might even find something that works. Or not. Good luck. 🍀

<div align="center">
  Created with ❤️ by <a href="https://github.com/Flingocho">Flingocho</a>
</div>

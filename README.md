<div align=center>
<img src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExMTNteGYyMnpseGtmeW4xaWU4a2JteDVqcmk2NGFrNTN4cXA3bzFscyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/Wo0Yw7qwzgQak/giphy.gif" width="500px">

## 👋 Yeah, it's Flingocho
</div>

## 🚀 About Me (blah, blah, blah...)

Currently a **Software Development Student** at the illustrious [**42 Madrid**](https://www.42madrid.com/). My thrilling coding escapade started in June 2024 with the "Piscine" (think trial by fire, but with more C code), and I officially subjected myself to the Cursus in September 2024.

By day (and often night), I also work as a **Data Science Engineer at Telefónica Tech** and as **Lead Developer at [Music Stocks](https://musicstocks.io)** — a blockchain-based marketplace for music royalty rights. Somehow I'm still standing.

These past few months have been... an experience. Mostly involving staring at a screen, questioning my life choices, and occasionally producing something resembling functional code. The goal is supposedly "elegant, high-performance code" and "thrilling projects." We'll see how that goes. 🙄

I document this questionable journey on GitHub. If you stumble upon my code and have actual, constructive advice (or just want to point and laugh), feel free. 🤷‍♂️

---

<details open>
<summary>🧠 Highlight Project — Gomoku AI</summary>


<div align="center">
  <img src="https://raw.githubusercontent.com/Flingocho/gomoku/main/imgs/main_menu.png" width="350px">
  <img src="https://raw.githubusercontent.com/Flingocho/gomoku/main/imgs/game.png" width="350px">
</div>

[`gomoku`](https://github.com/Flingocho/gomoku) — A full-featured **Gomoku (Five-in-a-Row)** game on a 19×19 board, with a serious AI engine. This one's actually impressive, I say with zero humility.

**What's under the hood:**
- Dual AI implementations: **C++17** and **Rust** (via FFI), switchable from the main menu
- **Minimax + Alpha-Beta pruning** with Iterative Deepening and a 64MB Zobrist transposition table
- Adaptive search depth by game phase (opening → 6, midgame → 8, endgame → 10)
- Move ordering: history heuristic, killer moves, geometric/centrality bonuses
- Full rule engine: captures, double free-three prohibition, breakable five-in-a-row
- **SFML GUI** — 1000×800, particle effects, glow, hover indicators, winning line highlight
- Colorblind mode, sound/music system, in-game AI move suggestions
- **148 unit tests** covering both implementations and verifying C++/Rust parity

Built with [jainavas](https://github.com/jainavas). `C++ · Rust · SFML`

</details>

---

## 🏆 My Projects Portfolio

<details>
<summary>📚 Cursus 42 Common Core</summary>

<details open>
<summary>🎯 Milestone 0️⃣</summary>

- [`libft`](https://github.com/Flingocho/libft) - My foundational C library. The one that started it all.

</details>

<details open>
<summary>🎯 Milestone 1️⃣</summary>

- [`ft_printf`](https://github.com/Flingocho/ft_printf) - A custom implementation of the C `printf` function.
- [`get_next_line`](https://github.com/Flingocho/get_next_line) - Reading lines from file descriptors. Deceptively painful.

</details>

<details open>
<summary>🎯 Milestone 2️⃣</summary>

- [`so_long`](https://github.com/Flingocho/so_long) - A simple 2D game. First contact with graphics. 🎮
- [`minitalk`](https://github.com/Flingocho/minitalk) - Client-server communication via UNIX signals.

</details>

<details open>
<summary>🎯 Milestone 3️⃣</summary>

- [`minishell`](https://github.com/Flingocho/minishell) - Crafting my own shell from scratch. Yes, it was hell. 🐚
- [`philosophers`](https://github.com/Flingocho/philosophers) - The Dining Philosophers problem. Threads, mutexes, starvation. 🤔

</details>

<details open>
<summary>🎯 Milestone 4️⃣</summary>

- [`cub3d`](https://github.com/Flingocho/cub3d) - Wolfenstein 3D-style raycasting engine in C. 🐺

</details>

<details open>
<summary>🎯 Milestone 5️⃣</summary>

- [`ft_irc`](https://github.com/Flingocho/ft_irc) — A fully functional IRC server in C++. Multi-client, channels, operators, the works. 💬

</details>

<details open>
<summary>🎯 Milestone 6️⃣</summary>

- [`ft_transcendence`](https://github.com/Flingocho/transcendence) — Full-stack web browser game. The final boss of the Common Core. 👩‍💻

</details>

</details>

---

<details open>
<summary>📚 42 School Outer Core Projects</summary>

- [`libasm`](https://github.com/Flingocho/libasm) — Low-level Assembly reimplementation of standard libc functions, with loop unrolling, memory alignment tricks, and hand-optimized x86-64. Actually kind of fun.

- [`lem-in`](https://github.com/Flingocho/lem-in) — Graph theory in anger: BFS-based pathfinding for an ant colony simulation. Finding optimal non-colliding paths through a network of rooms, plus a node visualizer to watch the ants crawl. Proper algorithmia. 🐜

- [`jvidal-t-IoT`](https://github.com/Flingocho/jvidal-t-IoT) — **Inception of Things**: full GitOps/DevOps pipeline from scratch. Vagrant-provisioned VMs running K3s clusters, Ingress routing, K3d for Docker-based orchestration, and Argo CD for continuous deployment — syncing app state from a Git repo to the cluster automatically. The kind of thing people get paid to set up. `Kubernetes · Vagrant · Docker · ArgoCD`

</details>

---

<details open>
<summary>⚛️ Side Quest — Quantum Computing</summary>

[`ftl_quantum`](https://github.com/Flingocho/ftl_quantum) — A personal deep-dive into quantum computing, done in Jupyter notebooks because sometimes you just want to think, not fight a compiler. (Also in real IBM quantum hardware)

Covers the fundamentals bottom-up:
- **EX00 — Superposition**: qubits, Hadamard gates, probability amplitudes
- **EX01 — Entanglement**: Bell states, EPR pairs, measuring correlated qubits
- **EX02 — Quantum Noise**: decoherence, error models, why quantum hardware is hard
- **EX03 — Deutsch-Jozsa**: first quantum algorithm that beats classical approaches. Provably.
- **EX04 — Grover's Algorithm**: unstructured search in O(√N). The one that actually matters.

The cat was alive... and angry

`Python · Qiskit · Jupyter · OpenQASM`

</details>

---

<details open>
<summary>💡 My Own Projects</summary>

- [`audio_pill_injection`](https://github.com/Flingocho/audio_pill_injection) — PoC for audio leak tracking. Injects an inaudible ultrasonic "pill" (25kHz square wave) into audio files at unique timestamps. If the file leaks, the spectrogram tells you who did it. `Python`

- [`freeze_stalker`](https://github.com/Flingocho/freeze_stalker) — WhatsApp bot that scrapes a website and takes a screenshot. Hardcoded mode, zero security, exactly as advertised. `JavaScript`

- [`noname_project`](https://github.com/Flingocho/noname_project) — Scripts for a game I'll build someday. If I don't die first.

</details>

---

## 📫 How to Reach Me

- **Email:** [jaimevidalt.24@gmail.com](mailto:jaimevidalt.24@gmail.com) (I might even reply)
- **LinkedIn:** [jaime-vidal-tejada](https://linkedin.com/in/jaime-vidal-tejada-7560b52a6) — still a work in progress, like everything else
- **GitHub Issues:** For any "constructive" feedback on my projects, feel free to open an issue.

Feel free to navigate through the labyrinth of my repositories — a testament to the pain and suffering that is learning to code. You might even find something that works. Or not. Good luck. 🍀

<div align="center">
  Created with ❤️ by <a href="https://github.com/Flingocho">Flingocho</a>
</div>

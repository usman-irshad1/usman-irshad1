# Mohammad Usman Irshad

**Computer Engineering | Systems & Algorithmic Simulation · Digital IC & RISC-V Architecture · Applied Speech & Embedded ML**

[![GitHub Profile](https://img.shields.io/badge/GitHub-usman--irshad1-181717?style=flat-square&logo=github)](https://github.com/usman-irshad1)
[![Email](https://img.shields.io/badge/Email-usmanirshad2006%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:usmanirshad2006@gmail.com)
[![Primary Stack](https://img.shields.io/badge/Core_Stack-C%2B%2B17%20%7C%20C%20%7C%20SystemVerilog%20%7C%20Java%20%7C%20Python-00599C?style=flat-square)]()
[![Focus](https://img.shields.io/badge/Domains-Systems%20Simulation%20%7C%20FPGA%20%26%20RISC--V%20%7C%20TinyML%20%26%20ASR-2ea44f?style=flat-square)]()

I design and build high-performance software simulators, custom hardware accelerators, and embedded machine learning pipelines. My engineering work spans from **cycle-accurate RTL processor and FPGA accelerator design in SystemVerilog** to **real-time physics, traffic, and OS memory simulators in C++/C/Java**, as well as **phoneme-level clinical speech assessment and TinyML inference**.

> **Seeking:** Actively seeking **Systems / Embedded Software Engineering**, **Digital IC / FPGA Design (RTL / RISC-V)**, and **Applied ML Engineering** internships and full-time opportunities. Reach me directly at **[usmanirshad2006@gmail.com](mailto:usmanirshad2006@gmail.com)**.

---

## Featured Engineering Portfolio

### 1. Systems & Algorithmic Simulation (C++ / C / Java)

| Project | Tech Stack | Architectural Highlights |
| :--- | :--- | :--- |
| **[simpec — 3D Urban Traffic & Signal Optimization Engine](https://github.com/usman-irshad1/simpec)** | `C++17` · `C` · `Raylib 3D` · `PyTorch` · `CMake` | Microscopic multi-class traffic engine (IDM car-following, MOBIL lane-changing) with real-world OpenStreetMap (`.osm`) geodetic projection, A\*/Dijkstra dynamic rerouting, and Q-Learning Max-Pressure + Genetic Algorithm signal optimization. |
| **[Autonomous Drone Swarm Simulator](https://github.com/usman-irshad1/Autonomous-Drone-Swarm-Simulator)** | `Java` · `JavaFX 3D` · `Multithreading` | Physics-based 3D multi-UAV swarm simulator for precision agriculture featuring consensus-based formation control, distributed collision avoidance, stochastic packet-loss modeling, and real-time telemetry visualization. |
| **[Adaptive Highway Traffic Simulator (ITS)](https://github.com/usman-irshad1/Adaptive-Traffic-Simulator-with-Dynamic-Rerouting-Signal-Control)** | `C++` · `Graph Algorithms` · `Doxygen` | Intelligent Transportation System modeling traffic flow across the Pakistan National Highway network using dynamic Dijkstra rerouting, non-linear BPR congestion functions, and adaptive signal control ([Live Docs](https://usman-irshad1.github.io/Adaptive-Traffic-Simulator-with-Dynamic-Rerouting-Signal-Control/)). |
| **[Virtual Memory & MMU Simulator System](https://github.com/usman-irshad1/Memory-Simulator-System)** | `C++` · `OS Architecture` · `Doxygen` | Full MMU hardware pipeline simulator modeling TLB caching, multi-level page table translation, FIFO/LRU/Optimal page replacement policies, and Effective Access Time (EAT) latency analysis ([Live Docs](https://usman-irshad1.github.io/Memory-Simulator-System/)). |
| **[Asynchronous Multithreaded Audio Engine](https://github.com/usman-irshad1/C-SFML-Asynchronous-Music-Manager)** | `C++` · `SFML` · `Concurrency` | Thread-safe audio playback engine backed by a custom $O(1)$ Doubly Linked List track navigator, background worker thread transitions, and persistent playlist serialization ([Live Docs](https://usman-irshad1.github.io/C-SFML-Asynchronous-Music-Manager/)). |
| **[Huffman Lossless File Compressor](https://github.com/usman-irshad1/Huffman-File-Compressor)** | `C++` · `Bitwise I/O` · `Trees` | Lossless character-frequency compression and decompression engine featuring canonical Huffman tree serialization and persistent key-based reconstruction ([Live Docs](https://usman-irshad1.github.io/Huffman-File-Compressor/)). |

---

### 2. Digital IC Design, FPGA Accelerators & Computer Architecture (SystemVerilog / Verilog)

| Project | Tech Stack | Architectural Highlights |
| :--- | :--- | :--- |
| **[FPGA 3D CNN Hardware Accelerator](https://github.com/usman-irshad1/CNN-accelerator)** | `SystemVerilog` · `Xilinx Vivado` · `FPGA` | Parameterized 3D Convolutional Neural Network hardware engine featuring 3 parallel 27-bit DSP Multiply-Accumulate (MAC) cores, a 3D Address Generation Unit (AGU), dual-port Block RAM tensor streaming, and hardware ReLU activation. |
| **[RISC-V Processor Architecture & Digital Design Progression (RV32I / RV32IM)](https://github.com/usman-irshad1/risc-v-multicycle-processor)** | `SystemVerilog` · `Verilog` · `RISC-V RV32I/M` | Complete 5-stage hardware progression from foundational digital logic gates, multiplexers, and counters to 32-bit ALU/Register File/Control subsystems, a **Single-Cycle RV32I Core**, and a **Flagship FSM-Controlled Multi-Cycle RV32IM Processor** with unified memory and hardware multiply/divide/remainder execution. |

---

### 3. Applied AI, Speech Processing & Embedded TinyML (Python / PyTorch)

| Project | Tech Stack | Architectural Highlights |
| :--- | :--- | :--- |
| **[Urdu Child Speech Sound Disorder (SSD) Assessment Pipeline](https://github.com/usman-irshad1/speech-therapy)** | `Python` · `PyTorch` · `Wav2Vec2 / XLS-R` | End-to-end clinical speech therapy pipeline achieving **9.47% Test Phoneme Error Rate (PER)** via fine-tuned `IndicWav2Vec-Hindi` CTC phoneme recognition, a canonical 44-phoneme Urdu Grapheme-to-Phoneme (G2P) engine, and logit-based Goodness-of-Pronunciation (`GOP_Margin`) forced alignment. |
| **[TinyML Respiration Spike Detection](https://github.com/usman-irshad1/temperature-sensor-tiny-ml)** | `Python` · `TinyML` · `Embedded C++` | From-scratch Logistic Regression classifier trained and deployed for microcontroller edge inference (`ESP32`/`Arduino`) to detect real-time respiration spikes from DHT11 temperature and humidity sensor streams. |

---

## Technical Skills

- **Systems & Application Programming:** `C++ (C++17)` · `C` · `Java (JavaFX)` · `Python` · `Multithreading & Concurrency` · `CMake`
- **Computer Architecture & Digital Design:** `SystemVerilog` · `Verilog HDL` · `RISC-V ISA (RV32I/M)` · `RTL Synthesis & Verification` · `Xilinx Vivado` · `GTKWave / ModelSim`
- **Machine Learning & Signal Processing:** `PyTorch` · `Self-Supervised ASR (Wav2Vec2 / XLS-R)` · `Forced Alignment & GOP Scoring` · `Reinforcement Learning (Q-Learning)` · `TinyML`
- **Graphics, Simulation & Tooling:** `Raylib (2D/3D)` · `SFML` · `JavaFX 3D` · `Git & GitHub Actions` · `Doxygen` · `Linux / Windows`

---

## Contact

- **Email:** [usmanirshad2006@gmail.com](mailto:usmanirshad2006@gmail.com)
- **GitHub:** [github.com/usman-irshad1](https://github.com/usman-irshad1)

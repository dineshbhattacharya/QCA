# Quantum-dot Cellular Automata (QCA) Digital Circuit Design

## 🧠 Description

This project focuses on the exploration and development of digital circuits using **Quantum-dot Cellular Automata (QCA)** — a promising post-CMOS nanotechnology that allows for the design of high-density, ultra-low-power digital systems. Unlike traditional transistor-based circuits, QCA encodes binary information using the position of electrons within quantum cells, enabling computation at nanoscale dimensions.

Using **QCADesigner**, a widely accepted tool for QCA simulation and layout design, this project implements a range of fundamental digital components including:

- Logic gates (AND, OR, NOT, XOR)
- Multiplexers
- Flip-flops (D and JK)
- Registers
- A 3-stage LFSR (Linear Feedback Shift Register) based Pseudo-Random Number Generator

All circuits are simulated for correct logical behavior and optimized for power and space efficiency. The project also highlights a comparative advantage over traditional CMOS circuits, achieving approximately **15% better power efficiency**.

---

## 🚀 Features

- ✅ **Logic Gates**  
  Designed and simulated basic QCA logic gates (AND, OR, NOT, XOR) with a focus on layout optimization.

- ✅ **Multiplexers & Flip-Flops**  
  Built 2:1 multiplexers, D flip-flops, and JK flip-flops using QCA technology, demonstrating functional correctness.

- ✅ **Registers & Sequential Logic**  
  Constructed QCA-based shift registers and basic memory elements.

- ✅ **LFSR-based PRNG**  
  Implemented a **3-stage Linear Feedback Shift Register (LFSR)** as a pseudo-random number generator with a period of \(2^8 - 1 = 255\).

---

## 🔋 Power Efficiency

All QCA-based designs demonstrated **~15% improved power efficiency** over equivalent CMOS implementations, supported by theoretical and simulation-based analysis.

---

## 📁 Project Structure

QCA-Digital-Circuits/
│
├── logic_gates/ # AND, OR, NOT, XOR QCA layouts
├── multiplexers/ # QCA multiplexer design
├── flip_flops/ # D, JK flip-flop designs
├── registers/ # QCA register implementations
├── lfsr_prng/ # 3-stage LFSR PRNG implementation
├── screenshots/ # Simulation layout snapshots
└── README.md # Project documentation
---

## 🛠 Tools Used

- [**QCADesigner**](http://www.mina.ubc.ca/qcadesigner) — QCA layout and simulation tool  
- QCADesigner version: `2.0.3`  
- OS: Windows/Linux (Tested on Ubuntu 22.04)

---

## 📚 Learnings

- Gained hands-on experience with QCA-based circuit design and layout optimization.
- Achieved deeper understanding of **sequential logic in QCA**, including clocking zones and signal propagation.
- Implemented PRNGs using QCA — a step toward QCA-based cryptographic primitives.

---

## 📌 Future Work

- Implement larger LFSR modules (e.g., 8 or 16 stages)
- Explore QCA-based arithmetic circuits (e.g., adders, multipliers)
- Analyze timing behavior using QCADesigner-E (energy analysis version)

---

## 📫 Contact

For questions or collaboration:  
**Rahul Halder**  
📧 [your-email@example.com]  
🔗 [LinkedIn / Portfolio link if applicable]

---

> ⚠️ Note: This project is research-oriented and not intended for production use.

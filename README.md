# 🧩 Automata Theory - Projects
![Language](https://img.shields.io/badge/Language-Python-blue)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)
![License](https://img.shields.io/badge/License-MIT-green.svg)

Implementations of core automata theory models - DFA, NFA, PDA, and Turing Machine - with interactive CLI simulators.

---

## 🚀 Overview

This repository links all my automata theory projects, each focusing on a different computational model and its practical simulation.

| Model | Repository | Concepts Covered | Highlights |
|:------|:------------|:-----------------|:------------|
| **DFA** | [deterministic-finite-automata](https://github.com/06cezar/deterministic-finite-automata) | Regular languages, total transition functions | CLI simulator that checks string acceptance and optionally prints transitions; also a string generator for a given DFA |
| **NFA** | [nondeterministic-finite-automata](https://github.com/06cezar/nondeterministic-finite-automata) | ε-transitions, nondeterminism | Simulates multiple active states and ε-closures; interactive CLI mode |
| **PDA** | [pushdown-automata](https://github.com/06cezar/pushdown-automata) | Context-free languages, stack operations | Stack-based recognition for languages like balanced parentheses; includes small CLI "Escape The Room" game, improved from the DFA version |
| **TM** | [turing-machine](https://github.com/06cezar/turing-machine) | General computation, tape/head | Full tape simulation; supports head movement and step-by-step execution with visual feedback |

---

## 🧠 Why This Repository

From simple finite automata to the universal Turing machine, these projects explore the full hierarchy of computation models.

Each project:
- ✅ Implements a fundamental computational model  
- 🎮 Includes an interactive CLI mode (mini game or test console)  
- 🧾 Contains clear documentation and sample inputs  
- 💡 Makes the transition from formal theory to programming practice  

---

## 🖥️ Tech Stack

- **Language:** Python
- **Interface:** Command Line (interactive)
- **Focus Areas:** Algorithmic design, data structures (stack, queue, hashmap), input parsing, simulation logic
- **Documentation:** Markdown READMEs and inline comments

---

## 🎮 CLI Games and Interactivity

Each automata project includes an interactive CLI mode for experimentation and learning:

| Game Type | Model | Description |
|------------|--------|-------------|
| 🎯 Acceptance Challenge | DFA | Guess strings that the machine accepts and see the result instantly |
| 🌊 Branch Explorer | NFA | Visualize simultaneous nondeterministic paths |
| 🧱 Stack Builder | PDA | Play with push/pop operations - try to balance input symbols |
| 🧾 Tape Puzzle | TM | Step through each move of a Turing Machine |

---

## 🧠 The Chomsky Hierarchy

<p align="center">
  <img src="https://www.taalhammer.com/wp-content/uploads/2024/04/chomsky-hierarchy-1024x669.png" alt="Chomsky Hierarchy" width="600">
</p>

The projects in this repository follow the Chomsky hierarchy,
progressing from simpler to more powerful computational models:


**Regular (DFA/NFA)** → **Context-Free (PDA)** → **Recursively Enumerable (Turing Machine)**.

---

## 📚 Learning Outcomes

- Understand the **Chomsky hierarchy** in practice
- Implement real interpreters for theoretical computation models  
- Build simulations for **state transitions**, **stack-based memory**, and **tape-based computation**  
- Connect formal language theory with programming practice  

---

## 🧭 Repository Map
```
automata-theory-projects/
├── deterministic-finite-automata/
├── nondeterministic-finite-automata/
├── pushdown-automata/
└── turing-machine/
```

*(You can clone each project individually or use this repository as a central index.)*

---

## 🏷️ Topics
`automata` • `theory-of-computation` • `formal-languages` • `dfa` • `nfa` • `pda` • `turing-machine` • `cli-tools`

---

## 📄 License
This repository and linked projects are licensed under the [MIT License](LICENSE).

---

## 💬 Author

👤 **Cezar-Gabriel Ciocîrlan**  
🎓 *Computer Science Student, University of Bucharest*  
🌐 [GitHub Profile](https://github.com/06cezar)



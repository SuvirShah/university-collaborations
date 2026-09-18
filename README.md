# Academic Systems & Algorithms Portfolio

This repository contains a collection of collaborative academic projects focusing on network infrastructure, artificial intelligence, and formal automata theory. Each system was engineered in a 3-person team, emphasizing task delegation, peer code review, and collaborative debugging.

## 1. Reliable UDP Message Delivery System
An application-layer protocol built in Python that guarantees reliable data transfer over an unreliable UDP network[cite: 1].
* **Core Concepts:** Implements the Stop-and-Wait Automatic Repeat reQuest (ARQ) protocol to ensure correct and ordered message delivery[cite: 1].
* **Features:** Utilizes sequence numbers and acknowledgments to maintain packet order and detect duplicates, alongside a timeout-based retransmission mechanism to handle simulated packet and acknowledgment loss[cite: 1].
* **Stack:** Python (Socket Programming)[cite: 1].

## 2. AI-Based Extended Sudoku Solver
An artificial intelligence solver that models an extended Sudoku puzzle as a Constraint Satisfaction Problem (CSP)[cite: 2].
* **Core Concepts:** Utilizes state-space search, constraint propagation, inference, and backtracking algorithms to systematically evaluate candidate digits and reduce the search space[cite: 2].
* **Features:** Solves standard $9\times9$ grids while supporting complex extended rules, including main/anti-diagonal and chess-style knight-move dependencies[cite: 2].
* **Stack:** Python[cite: 2].

## 3. Pushdown Automaton (PDA) Simulator
A C-based simulator that evaluates strings against the context-free language $L=\{w~C~w^R\}$[cite: 3].
* **Core Concepts:** Translates theoretical pushdown automata state transitions into practical array-based stack memory management[cite: 3].
* **Features:** Parses binary strings by pushing prefix symbols onto a stack and popping them post-separator to guarantee exact symmetric matching, strictly rejecting malformed inputs or misplaced separators[cite: 3].
* **Stack:** C[cite: 3].

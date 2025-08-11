# Ultimate Tic Tac Toe AI

This project implements a competitive AI agent for **Ultimate Tic Tac Toe**, designed to play strategically and efficiently against strong opponents.  
It uses a combination of **search algorithms**, **heuristics**, and **machine learning** to make optimal moves within strict time limits.

---

## Game Overview

Ultimate Tic Tac Toe is played on a 3×3 grid of smaller 3×3 Tic Tac Toe boards.  
Players take turns playing in the small boards, but the location of each move determines which small board the next player must play in.  
The goal is to win three small boards in a row.

---

## Features

- **Iterative Deepening Minimax** with **Alpha–Beta Pruning**  
  Efficiently searches the game tree to find the best move within time limits.

- **Quiescence Search**  
  Extends search in volatile positions to reduce horizon effects.

- **Zobrist Hashing**  
  Generates unique board hashes for fast **transposition table** lookups.

- **Advanced Heuristics**  
  - Positional weights for local and global boards  
  - Threat detection and fork creation  
  - Center control bias  
  - Penalties for moves that lead to losing boards

- **Machine Learning Assisted Endgame Evaluation**  
  Lightweight neural network to improve late-game decision-making.

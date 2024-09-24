# FroggerProcess 🐸🚗

[![License](https://img.shields.io/github/license/Gabrielebandino/FroggerProcess)](LICENSE)
[![Contributors](https://img.shields.io/github/contributors/Gabrielebandino/FroggerProcess)](https://github.com/Gabrielebandino/FroggerProcess/graphs/contributors)
[![Issues](https://img.shields.io/github/issues/Gabrielebandino/FroggerProcess)](https://github.com/Gabrielebandino/FroggerProcess/issues)

Welcome to **FroggerProcess**, a terminal-based implementation of *Frogger* built in C using the **ncurses** library. This project simulates a multi-agent system where each entity (logs, enemies, projectiles, etc.) is represented as a separate thread, providing an introduction to concurrent programming via thread management.

## 🚀 Features

- **Thread-based Simulation**: Each game element (frog, logs, cars, projectiles) runs as an independent thread.
- **Graphics via ncurses**: Uses the ncurses library to render game elements in the terminal.
- **Real-time Interaction**: Control the frog and navigate through dynamically moving obstacles.
- **Thread Synchronization**: Coordinates multiple threads efficiently to ensure smooth gameplay.

## 🛠️ Technologies

- **Programming Language**: C
- **Graphics**: ncurses for rendering game elements.
- **Thread Management**: POSIX threads (pthread library) for managing game elements as separate threads.

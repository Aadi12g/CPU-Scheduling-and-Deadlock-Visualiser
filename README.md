# Operating System Resource Management and Process Scheduling Simulator

Demonstrates concepts related to resource management, process scheduling, and deadlock handling. It includes implementations for various CPU scheduling algorithms, the Banker's algorithm, deadlock detection using Wait-For Graphs, and more.

## Features

### 1. **CPU Scheduling**
- Allows simulation of various CPU scheduling algorithms.
- Options for tracing execution or viewing statistics.
- Supported algorithms include:
  - **First Come First Serve (FCFS)**
  - **Shortest Process Next (SPN)**
  - **Round Robin (RR)**
  - **Shortest Remaining Time (SRT)**

### 2. **Banker's Algorithm**
- Simulates the Banker's Algorithm for deadlock avoidance.
- Includes:
  - Matrix management.
  - Safety checks.
  - Resource allocation and release.

### 3. **Single Instance Deadlock Detection**
- Handles deadlock detection using:
  - **Wait-For Graphs (WFG).**
  - **Resource Allocation Graphs (RAG).**
- Features graphical representation using **Graphviz**.

---

## Usage

1. **Compile and run the program** in a C++ environment.
2. Follow the main menu to navigate through features:
   - Select **CPU Scheduling** for scheduling simulations.
   - Select **Banker's Algorithm** for deadlock avoidance checks.
   - Select **Single Instance Deadlock Detection** for WFG-based deadlock detection.

---

## Requirements

1. **Graphviz** installed for graphical outputs.
2. **C++ compiler** supporting standard libraries like `<iostream>`, `<vector>`, and Windows-specific headers.

---

**Note:**  
This simulator is designed for educational purposes to demonstrate operating system concepts like resource allocation, scheduling, and deadlock detection. The program is intended for **Windows** and may require modification for other platforms.


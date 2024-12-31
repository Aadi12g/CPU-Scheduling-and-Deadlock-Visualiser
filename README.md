# Operating System Resource Management and Process Scheduling Simulator

Demonstrates concepts related to resource management, process scheduling, and deadlock handling. It includes implementations for various CPU scheduling algorithms, the Banker's algorithm, deadlock detection using Wait-For Graphs, and more.

# Features:

**CPU Scheduling**

-Allows simulation of various CPU scheduling algorithms.
-Options for tracing execution or viewing statistics.
-Algorithms supported include First Come First Serve (FCFS), Shortest Process Next (SPN),Round Robin(RR) and Shortest Remaining Time(SRT).

**Banker's Algorithm**

-Simulates the Banker's Algorithm for deadlock avoidance.
-Includes matrix management, safety checks, and resource allocation/release.

**Single Instance Deadlock Detection**

-Handles deadlock detection using Wait-For Graphs (WFG) and Resource Allocation Graphs(RAG).
-Features graphical representation using Graphviz.

# Usage:
-Compile and run the program in a C++ environment.
-Follow the main menu to navigate through features:
-Select CPU Scheduling for scheduling simulations.
-Select Banker's Algorithm for deadlock avoidance checks.
-Select Single Instance Deadlock Detection for WFG-based deadlock detection.

# Requirements:

1.Graphviz installed for graphical outputs.
2.C++ compiler supporting standard libraries like iostream, vector, and Windows-specific headers.

Note: This simulator is designed for educational purposes to demonstrate operating system concepts like resource allocation, scheduling, and deadlock detection.
      The program is for Windows and may require modification for other platforms

# Operating System Scheduler & Memory Simulator

## Project Overview

This project is a command-line based Operating System Scheduler and Memory Management Simulator developed as part of the **B206 Operating Systems** module at **Gisma University of Applied Sciences**.

The simulator demonstrates core operating system concepts by modelling CPU scheduling algorithms and dynamic memory allocation strategies while measuring key system performance metrics. Users interact with the system via a terminal interface, allowing custom process definitions and algorithm selection.

---

## Implemented Operating System Concepts

### CPU Scheduling Algorithms
- **First Come First Served (FCFS)**
- **Shortest Job First (SJF)** (non-preemptive)
- **Round Robin (RR)** with user-defined time quantum

### Memory Allocation Strategies
- **First-Fit**
- **Best-Fit**

### Performance Metrics
- Waiting Time
- Turnaround Time
- Average Waiting Time
- Average Turnaround Time
- CPU Utilisation
- Memory Utilisation

---

## System Features

- Interactive command-line interface (CLI)
- User-defined total system memory and process data
- Real-time memory allocation validation
- Automatic rejection of processes when memory is insufficient
- Multiple simulation runs without restarting the program
- Clean program exit option
- Clearly formatted execution results

---

## Project Structure

os-scheduler-simulator/

 - main.py 

 - scheduler.py # CPU scheduling algorithms

 - memory.py # Memory allocation logic

 - process.py # Process data structure

 - metrics.py # Performance calculations

 - README.md # Project documentation



---

## How to Run the Program

### Prerequisites
- Python **3.10 or later**

Navigate to the project directory:
  ```bash
  cd os-scheduler-simulator
  ```
Run the simulator:
```bash
  python main.py
```

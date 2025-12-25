# 🧠 Interactive Memory Allocation Simulator

A desktop-based simulator built using **C++** and **Qt 6** that visualizes core **Operating System memory management algorithms** in real time.

<img width="1366" height="726" alt="image" src="https://github.com/user-attachments/assets/faea9098-a75e-46f7-ac3f-a70b375d5077" />
---

## 🚀 Project Overview

Operating System concepts such as **memory allocation**, **external fragmentation**, and **free memory holes** are often difficult to understand through theory alone.

This project transforms those abstract ideas into a **visual and interactive simulation**, allowing users to observe how different allocation strategies affect RAM utilization and fragmentation in real time.

---

## 🛠️ Tech Stack

- **Language:** C++ (C++17)
- **GUI Framework:** Qt 6 (Widgets)
- **Build System:** CMake
- **IDE:** VS Code / Qt Creator
- **Architecture:** MVC (Model–View–Controller)

---

## ✨ Key Features

- **Visual Memory Map**  
  Custom-drawn memory bar showing allocated processes and free holes using color coding.

- **Memory Allocation Algorithms**
  - First Fit  
  - Best Fit  
  - Worst Fit  
  - Next Fit  

- **Live Statistics Dashboard**
  - Memory Utilization (%)
  - Free Memory
  - Fragmentation Count

- **Dynamic Process Handling**
  - Create processes with custom IDs and sizes
  - Deallocate processes at runtime

- **Event Logging**
  - Timestamped logs for every allocation and deallocation action

- **Automatic Coalescing**
  - Adjacent free blocks are merged automatically to reduce fragmentation

---

## 📸 How the Simulator Works

1. Select a memory allocation algorithm from the dropdown menu.
2. Enter a **Process ID** and **Memory Size**.
3. Allocate the process and observe how memory is assigned visually.
4. Deallocate processes to see fragmentation and coalescing effects.
5. Compare how different algorithms impact memory usage.
   

---

## 🔧 Build & Run Instructions
in vs code after downloading the project set qt and then build the project after that press ctrl +shift+c and write build\MemorySimulator.exe 
### Prerequisites
- Qt 6 SDK
- C++ Compiler (MinGW or MSVC)
- CMake

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/Memory-Allocation-Simulator.git

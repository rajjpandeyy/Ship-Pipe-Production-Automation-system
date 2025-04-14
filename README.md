# 🚢 Ship Pipe Production Automation System

![Production](https://img.shields.io/badge/Optimization-Evolutionary-blue) ![SimPy](https://img.shields.io/badge/SimPy-Discrete--Event--Simulation-green) ![Status](https://img.shields.io/badge/Status-Active-brightgreen)

> **Optimized Scheduling and Simulation System for Ship Pipe Production** using multi-objective evolutionary algorithms and discrete-event simulation. Built with Python, SFL-DEA, and SimPy.

---

## 📌 Project Overview

This project simulates and optimizes a real-world **ship pipe manufacturing process** using a powerful evolutionary approach based on the **Shuffled Frog Leaping Differential Evolution Algorithm (SFL-DEA)**. It incorporates:

- ⏳ **Minimization of Makespan**
- ⚡ **Energy-Efficient Scheduling**
- 🏭 **Factory Assignment & Workflow Optimization**
- 📊 **Gantt Chart Visualization**
- ⚙️ **SimPy-based Production Simulation**

---

## 🚀 Features

- ✅ **Multi-Objective Optimization**: Simultaneously minimizes total production time and energy usage.
- 🧠 **Intelligent Scheduling**: Evolves 100 candidate schedules over 400 generations.
- 📦 **Factory Load Balancing**: Automatically distributes jobs across multiple factories.
- 📈 **Visual Dashboard**: Gantt chart of job timelines and operations.
- 🔄 **Event-Based Simulation**: Realistic modeling of job flow and machine utilization using `SimPy`.

---

## 🛠️ Technologies Used

| Tool            | Description                                 |
|-----------------|---------------------------------------------|
| 🐍 Python        | Core programming language                   |
| 📘 SimPy         | Event-driven simulation engine              |
| 📉 Matplotlib    | Gantt chart generation & visualization      |
| 🧬 NumPy         | Data structures & random initialization     |
| 💡 SFL-DEA       | Custom evolutionary optimization logic      |

---

## 🧪 How It Works

1. **Initialize Population**: 100 randomized schedules and factory assignments.
2. **Evolve with SFL-DEA**: Mutation, crossover, and local search improve candidates across 400 generations.
3. **Evaluate Objectives**: Calculates makespan and energy consumption.
4. **Simulate in Real-Time**: SimPy models each job's movement through factories and machines.
5. **Visualize**: Gantt chart shows job timelines, colored by operation.

---

## 📸 Sample Gantt Chart Output

> *(Will appear after you run the simulation)*

![Gantt Chart](https://user-images.githubusercontent.com/your-image-path-here.png)

---

## 🧰 Setup Instructions

1. **Clone the repository**  
   ```bash
   git clone https://github.com/PSW9102004/Ship-Pipe-Production-Automation-System.git
   cd Ship-Pipe-Production-Automation-System
2. **Install Required Packages**
   ```bash
   pip install numpy simpy matplotlib
3. **Run the Simulation**
   ``` bash
   python Ship_pipe.py

##  📂 File Structure 
```bash
├── main.py               # Full optimization + simulation code
├── README.md             # You're reading it!
├── requirements.txt      # (optional) Python dependencies
```
## Author
👤 Raj Pandey
Third-Year B.Tech Student – IIITDM Jabalpur




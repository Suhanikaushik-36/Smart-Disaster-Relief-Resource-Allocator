# 🚑 Smart Disaster Relief Resource Allocator

**Smart Disaster Relief Resource Allocator** is a Python-based GUI application designed to help disaster management teams plan and allocate resources efficiently during emergencies. The app allows users to input affected areas, severity levels, and the road network connecting these areas, then simulates the relief allocation process and visualizes it on a graph.

---

## Features

- **Add Affected Areas**: Input area names along with severity levels (1–10).  
- **Add Roads**: Define roads connecting areas with distances (in km).  
- **Save Input**: Save all areas and roads into `input.txt` for backend processing.  
- **Run Simulation**: Allocate relief resources based on severity and show the order of priority.  
- **Graph Visualization**: View the affected areas and road network on a visual graph using `networkx` and `matplotlib`.  
- **Error Handling**: Ensures proper input validation, case-insensitive area matching, and informative messages.

---



---

## Installation

1. Clone this repository:

```bash
git clone https://github.com/suhanikaushik-36/smart-disaster-relief.git


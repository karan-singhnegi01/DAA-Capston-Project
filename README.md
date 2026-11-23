# Mini-Courier Planner

## Project Overview
The Mini-Courier Planner is a Python-based application that simulates a courier delivery planning system. It prioritizes parcels, optimizes parcel selection based on van capacity, calculates shortest paths and generates a delivery route.

## Algorithms Used
1. **Merge Sort:** Sorts parcels based on delivery deadlines.
2. **0/1 Knapsack (Dynamic Programming):** Selects parcels to maximize total value within the van capacity.
3. **Dijkstra's Algorithm:** Calculates shortest distances between delivery locations.
4. **Nearest Neighbor (TSP Approximation):** Generates an approximate delivery route.

## Technologies
- Python
- Matplotlib
- Heapq
- Time module

## How to Run
1. Install Python.
2. Install Matplotlib using:
   `pip install matplotlib`
3. Open the project folder in VS Code.
4. Run:
   `python main.py`

## Project Files
- `main.py` - Source code
- `performance_chart.png` - Runtime chart
- `screenshots/` - Execution evidence
- `report.docx` - Project report

## Performance Testing
The algorithms are tested on different input sizes. Their execution times are measured and visualized using a chart.

## Conclusion
The project combines sorting, dynamic programming, graph algorithms and approximation techniques to simulate a courier planning system.
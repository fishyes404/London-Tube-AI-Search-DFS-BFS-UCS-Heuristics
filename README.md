# 🚇 London Tube AI Search – DFS, BFS, UCS, Heuristics

This project applies search algorithms to the London Underground map to find optimal routes based on time and zone.

## 🔍 Features

- Implements DFS, BFS, UCS, and Zone-Based Heuristic Search
- Graph state representation with cost and zone metadata
- Extended cost model for line changes
- Compares performance and optimality

## 📂 Files

- `undirected_map_final_vickshan_vicknakumaran.ipynb` – Main implementation notebook
- `tubedata.csv` – Tube map with station-to-station data

## 📊 Sample Result

**Route: New Cross Gate → Stepney Green**
| Algorithm | Time (min) | Nodes Explored |
|-----------|------------|----------------|
| DFS       | 27         | 35             |
| BFS       | 12         | 8              |
| UCS       | 14         | 19             |

## 🏫 Module Info

- Year: 2024  
- University: Queen Mary University of London  
- Author: Vickshan Vicknakumaran

## 🧠 How to Run

Open the notebook in Jupyter, ensure `tubedata.csv` is in the same directory, and run cells in order.

## 📜 License

For academic and research use only.

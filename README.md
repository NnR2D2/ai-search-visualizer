<!-- PROJECT TITLE -->
<h1 align="center">🧠 AI Search Visualizer</h1>

<p align="center">
  An interactive web-based tool to visualize classic AI search algorithms in action.
</p>

<p align="center">
  <img alt="Stars" src="https://img.shields.io/github/stars/NnR2D2/ai-search-visualizer?style=for-the-badge" />
  
  <img alt="Forks" src="https://img.shields.io/github/forks/NnR2D2/ai-search-visualizer?style=for-the-badge" />
  
  <img alt="License" src="https://img.shields.io/github/license/NnR2D2/ai-search-visualizer?style=for-the-badge" />
  
  <img alt="AI Project" src="https://img.shields.io/badge/AI-Search%20Visualizer-purple?style=for-the-badge" />
</p>



## 🚀 Overview

**AI Search Visualizer** is a modern, interactive platform designed to help you understand how different Artificial Intelligence search algorithms work.

It visually demonstrates how algorithms explore a grid, evaluate nodes, and find optimal (or non-optimal) paths.



## ✨ Features

✔️ Interactive Grid System  
✔️ Real-time Pathfinding Animation  
✔️ Multiple Algorithm Support  
✔️ Heuristic Visualization (Manhattan & Euclidean)  
✔️ Drag & Drop Start / Goal Nodes  
✔️ Obstacle Drawing (Click & Drag)  
✔️ Clear Path & Reset Board Controls  



## 🧠 Algorithms Implemented

### 🔹 Uninformed Search

| Algorithm | Description |
|----------|------------|
| BFS | Level-by-level traversal (guarantees shortest path) |
| DFS | Deep traversal before backtracking |
| UCS | Expands nodes by lowest cost |



### 🔹 Informed Search

| Algorithm | Description |
|----------|------------|
| Greedy Best-First Search | Chooses node closest to goal |
| A* | Combines path cost + heuristic |

A* Formula:
f(n) = g(n) + h(n)


## 🛠️ Tech Stack

Frontend: HTML5, CSS3, JavaScript  
Backend/Logic: Python (Flask/Brython) or JavaScript  
Visualization: HTML5 Canvas / SVG  


## 📦 Installation


```bash
git clone https://github.com/NnR2D2/ai-search-visualizer.git
cd ai-search-visualizer
```
---

## ▶️ Run

Option 1: 
```bash
index.html  
```

Option 2:
```bash
python -m http.server
```

Visit 
```bash
http://localhost:8000
```



## 🎯 Usage

1. Select algorithm  
2. Draw obstacles  
3. Set Start (S)  
4. Set Goal (G)  
5. Click Start  



## 📂 Structure

```bash
ai-search-visualizer/
│── index.html
│── style.css
│── script.js
│── assets/
│── README.md

```


## 🔮 Future Improvements

- 📊 Performance comparison
- 🎚️ Speed control
- 🌐 React version
- 🧠 More algorithms (Dijkstra, IDA*, Bidirectional)
- 💾 Save/load states






## 🤝 Contributing

Fork → Branch → Commit → Push → Pull Request


## 📄 License

MIT License. See [LICENSE](LICENSE).



## 👨‍💻 Author

**NnR2D2**  
https://github.com/NnR2D2



## ⭐ Support

🌟 Star the repo  
🍴 Fork it  
📢 Share it  


<p align="center">
  Made with ❤️ for learning AI visually
</p>

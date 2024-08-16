# MazeRunner-AI: CS50AI Maze Solving Algorithms

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![CS50AI](https://img.shields.io/badge/Course-CS50AI%202024-red)
![License](https://img.shields.io/badge/License-MIT-green)

## 🧠 Introduction

Welcome to MazeRunner-AI, a project developed as part of the CS50AI 2024 course from Harvard University. This repository showcases the implementation and analysis of two fundamental graph traversal algorithms: Depth-First Search (DFS) and Breadth-First Search (BFS) in the context of maze solving.

Through this project, we dive deep into the world of artificial intelligence and algorithmic problem-solving, demonstrating how these classic algorithms can be applied to navigate and solve mazes of varying complexity.

## 🌟 Features

- **Dual Algorithm Implementation**: Side-by-side implementation of both DFS and BFS algorithms for maze solving.
- **Dynamic Maze Input**: Ability to solve mazes of arbitrary sizes, read from text files.
- **Performance Comparison**: Detailed analysis and visualization of algorithm performance metrics.
- **Interactive Jupyter Notebook**: Step-by-step execution and explanation of the algorithms.
- **Visualization**: Graphical representation of maze solutions and algorithm efficiency.

## 📊 Project Structure

The core of this project is contained in the `maze.ipynb` Jupyter notebook. Here's an overview of its contents:

1. **Introduction and Theory**: 
   - Background on DFS and BFS algorithms
   - Their applications in maze solving

2. **Maze Representation**: 
   - Reading maze structures from text files (`maze1.txt`, `maze2.txt`)
   - Internal representation of mazes as 2D arrays

3. **Algorithm Implementations**:
   - Depth-First Search (DFS) implementation
   - Breadth-First Search (BFS) implementation
   - Helper functions for maze traversal and solution tracking

4. **Visualization**:
   - Functions to visualize maze structures
   - Plotting of solution paths for both DFS and BFS

5. **Performance Analysis**:
   - Comparison of steps taken by each algorithm
   - Analysis of the number of states explored
   - Memory efficiency considerations

6. **Interactive Examples**:
   - Solving sample mazes (`maze1.txt`, `maze2.txt`)
   - Step-by-step execution and explanation

## 🚀 Key Findings

Our analysis revealed several interesting insights:

1. **BFS Effectiveness**: Breadth-First Search consistently found the shortest path from start to end in our test mazes.

2. **DFS Exploration**: Depth-First Search often explored more states before finding a solution, especially in more complex mazes.

3. **Memory Trade-offs**: While BFS generally found optimal solutions, it required more memory to store the frontier of unexplored states.

4. **Maze Structure Impact**: The efficiency of each algorithm varied depending on the maze structure, highlighting the importance of choosing the right algorithm for specific problem types.

## 📈 Performance Metrics

For `maze2.txt`, a more complex maze, we observed:

- **BFS**: 
  - Steps to solution: 30
  - States explored: 59

- **DFS**:
  - Steps to solution: 30
  - States explored: 74

This demonstrates that while both algorithms found paths of the same length, BFS was more efficient in terms of the number of states explored.

## 🛠️ Technologies Used

- Python 3.9+
- Jupyter Notebook
- Libraries: matplotlib, numpy

## 🏃‍♂️ How to Run

1. Clone this repository:
   ```
   git clone https://github.com/Tuminha/MazeRunner-AI-CS50AI-Maze-Solving-Algorithms.git
   ```

2. Navigate to the project directory:
   ```
   cd MazeRunner-AI-CS50AI-Maze-Solving-Algorithms
   ```

3. Install required dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook:
   ```
   jupyter notebook
   ```

5. Open `maze.ipynb` and run the cells sequentially.

## 🧪 Testing with Custom Mazes

To test the algorithms with your own mazes:

1. Create a text file with your maze structure (e.g., `custom_maze.txt`).
2. Use `#` for walls and spaces for open paths.
3. Mark the start with `A` and the end with `B`.
4. Update the file path in the notebook to load your custom maze.

Example:
```
#####B#
##### #
####  #
#### ##
     ##
A######
```

## 📚 Learning Outcomes

Through this project, we've gained:
- Deep understanding of DFS and BFS algorithms
- Practical experience in algorithm implementation and optimization
- Skills in data visualization and performance analysis
- Insights into the trade-offs between different search strategies

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check [issues page](https://github.com/Tuminha/MazeRunner-AI-CS50AI-Maze-Solving-Algorithms/issues) if you want to contribute.

## 📜 License

This project is [MIT](https://choosealicense.com/licenses/mit/) licensed.

## 🙏 Acknowledgements

- CS50AI 2024 course staff and instructors at Harvard University
- [Audi Victor Valenzuela's article](https://medium.com/swlh/solving-mazes-with-depth-first-search-e315771317ae) for inspiration on maze-solving visualizations

## 📞 Contact

If you have any questions or want to reach out, please open an issue on this repository or contact me at [cisco@periospot.com](mailto:cisco@periospot.com).

---

Happy Maze Solving! 🎉
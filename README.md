# Sorting Visualizer

A web-based visualizer that demonstrates how different sorting algorithms work step by step.

## Features

- Visualize multiple sorting algorithms such as:
  - Bubble Sort  
  - Selection Sort  
  - Insertion Sort  
  - Merge Sort  
  - Quick Sort  
  - Heap Sort  
- Real-time animation of array operations (comparisons, swaps, merges, etc.)
- Adjustable speed / delay between steps
- Regenerate random array to start fresh
- (Optional) Pause / resume, reset controls
- (Optional) Display pseudocode or algorithm steps alongside the visualization

## Screenshot / Demo

![Demo GIF](assets/demo.gif)

<img width="1919" height="913" alt="image" src="https://github.com/user-attachments/assets/e18e60f5-c7db-4a03-84a4-4838d0a1fa0c" />
*Initial random array generation (10 elements, speed 10x)*

![img2](https://github.com/user-attachments/assets/b9f8e7ae-930d-41a1-a527-f0c254471d8f)
![img3](https://github.com/user-attachments/assets/c7b100a2-fac4-486a-9419-233e26267854)
*Merge Sort visualization during execution*

## Getting Started

### Prerequisites

What you need to run this project locally:

- A modern web browser (if it’s a web app)
- (Or) Node.js / npm (if built with JavaScript frameworks)  
- (Or) Python / local server (if HTML + vanilla JS)

### Installation / Setup

1. Clone this repository:

   ```bash
   git clone https://github.com/AkashShelake/Sorting-Visualizer.git
   ```

2. Navigate into the project directory:

   ```bash
   cd Sorting-Visualizer
   ```

3. If dependencies exist (e.g. in package.json), install them:

   ```bash
   npm install
   ```

4. Serve / run:

   - If it’s pure HTML + JS, open index.html in your browser

   - If there's a server script:

     ```bash
     npm start
     ```

   - If using Python’s simple HTTP server:

     ```bash
     python3 -m http.server
     ```
     # then open http://localhost:8000 in browser

## Usage / Controls

- Generate New Array: creates a new random sequence to sort

- Select Algorithm: choose which sorting method to visualize

- Start / Animate: begin the sorting process

- Speed Control: adjust the animation speed (faster / slower)

- Pause / Resume / Reset: (if implemented) control the animation flow

The algorithm’s operations (comparisons, swaps) are highlighted visually in the bars / elements.

## Algorithms Explained

Here is a quick summary of the algorithms supported:

| Algorithm     | Time Complexity (Average) | Space Complexity | Notes                              |
|---------------|---------------------------|------------------|------------------------------------|
| Bubble Sort   | O(n²)                     | O(1)             | Simple, inefficient for large n    |
| Selection Sort| O(n²)                     | O(1)             | Minimal swaps                      |
| Insertion Sort| O(n²)                     | O(1)             | Good for small / nearly sorted arrays |
| Merge Sort    | O(n log n)                | O(n)             | Divide-and-conquer, stable         |
| Quick Sort    | O(n log n)                | O(log n)         | Efficient in practice, but worst-case O(n²) |
| Heap Sort     | O(n log n)                | O(1)             | Not stable, good worst-case bound  |

You may optionally show pseudocode side-by-side so users can correlate visualization with code.

## Structure (Project Layout)

A possible directory / file structure:

```
Sorting-Visualizer/
├── index.html
├── style.css
├── main.js
├── algorithms/
│   ├── bubble.js
│   ├── selection.js
│   ├── insertion.js
│   ├── merge.js
│   ├── quick.js
│   └── heap.js
└── assets/
    ├── logo.png
    └── demo.gif
```

You can adjust according to your actual file setup.

## Contributing

Contributions are welcome! Some ideas to extend:

- Add more sorting algorithms (e.g. Radix Sort, Shell Sort, Counting Sort)

- Support descending order visualization

- Allow custom user-input arrays

- Add more controls: step-by-step execution, backtracking, speed presets

- Display performance metrics (# comparisons, swaps)

- Improve UI / responsiveness for different screen sizes

If you want to contribute:

1. Fork the repository

2. Create a new branch: git checkout -b feature/your-feature

3. Make changes & commit

4. Push to your fork: git push origin feature/your-feature

5. Create a Pull Request

## Acknowledgements

- This idea is inspired by many sorting visualizers and algorithm teaching tools

- Thanks to open-source community, tutorials, and algorithm references

- (If any external resource or library used, mention here)

*Note: Screenshots are placeholders based on provided images. Replace with actual URLs from your repo or Imgur for better visuals.*

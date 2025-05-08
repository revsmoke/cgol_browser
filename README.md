# Recursive Conway's Game of Life

This project is an interactive, browser-based demonstration of a **Recursive Conway's Game of Life** (CGoL) system, implemented in pure HTML5, CSS, and Vanilla JavaScript. It visually explores the concept of recursion and computation within cellular automata, inspired by John Conway's classic Game of Life.

## Features

- **Prime CGoL Instance**: The main Game of Life grid, fully interactive and configurable.
- **Recursive CGoL Instance**: A secondary grid that is automatically activated and seeded when a special pattern (Recursive Activator Pattern, RAP) is detected and stable in the Prime instance.
- **Pattern Loader**: Easily load classic patterns (Glider, Pulsar, Gosper Glider Gun, RAP Activator, etc.) into the Prime grid.
- **Customizable Controls**: Adjust speed, cell size, and grid size. Step, start/pause, and clear the simulation.
- **Visual Highlighting**: When the RAP is detected and stable, it is visually highlighted and the recursive instance is triggered.
- **No Backend Required**: All logic runs client-side in the browser. No server or backend code is needed.

## How to Run

1. **Clone or Download** this repository.
2. **Open `cgol.html` in any modern web browser** (Chrome, Firefox, Edge, Safari, etc.).
3. No build or installation steps are required.

## Usage

- **Prime Instance Controls**:
  - **Start/Pause**: Begin or pause the simulation.
  - **Step**: Advance the simulation by one generation.
  - **Clear**: Reset the grid to empty.
  - **Load Pattern**: Select and load a predefined pattern.
  - **Speed**: Adjust the simulation speed.
  - **Cell Size**: Change the size of each cell in pixels.
  - **Grid Size**: Change the number of cells in the grid (square).
  - **Click on the grid** (when paused) to toggle individual cells.
- **Recursive Instance**:
  - Becomes active and seeded with a pattern when the RAP is detected and stable in the Prime instance.
  - Shows its own generation and population stats.

## Project Structure

- `cgol.html` — Main HTML file containing all code (HTML, CSS, JavaScript).
- `.history/` — Contains backup/history versions of files (not needed for normal use).
- `.gitignore` — Standard git ignore file.

## Customization

You can modify or add new patterns by editing the `PREDEFINED_PATTERNS` object in `cgol.html`.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

Bryan Rice

## Acknowledgements

- Inspired by John Conway's Game of Life and the concept of Turing completeness in cellular automata. 
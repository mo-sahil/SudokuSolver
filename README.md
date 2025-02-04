# Sudoku Solver

A Java-based Sudoku Solver application that provides a graphical user interface (GUI) for solving Sudoku puzzles. The application allows users to input a Sudoku puzzle, solve it using a backtracking algorithm, and visualize the solving process in real-time.

## Features

- **Interactive GUI**: Input Sudoku puzzles directly into a 9x9 grid.
- **Real-time Solving**: Visualize the solving process step-by-step.
- **Validation**: Checks if the input Sudoku puzzle is valid before solving.
- **Clear Functionality**: Clear the grid to start over with a new puzzle.
- **Preloaded Puzzle**: Comes with a preloaded Sudoku puzzle for quick testing.

## How to Use

1. **Input the Puzzle**:
   - Enter the numbers of the Sudoku puzzle into the grid.
   - Leave cells empty for the solver to fill in.

2. **Solve the Puzzle**:
   - Click the "Solve" button to start the solving process.
   - The solver will fill in the empty cells and display the solution.

3. **Clear the Grid**:
   - Click the "Clear" button to reset the grid and start over.

## Requirements

- Java Development Kit (JDK) 8 or higher.
- A Java IDE (e.g., IntelliJ IDEA, Eclipse) or command-line tools.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sudoku-solver.git
   ```

2. Navigate to the project directory:
   ```bash
   cd sudoku-solver
   ```

3. Compile the Java files:
   ```bash
   javac SudokuSolver.java
   ```

4. Run the application:
   ```bash
   java SudokuSolver
   ```
## Code Structure

- **SudokuSolver.java**: The main class that sets up the GUI and handles the Sudoku solving logic. It includes the following components:
  - A 9x9 grid of `JTextField` for user input.
  - "Solve" and "Clear" buttons for solving and resetting the puzzle.
  - A `SwingWorker` to handle the solving process in the background, ensuring the GUI remains responsive.
  - A backtracking algorithm to solve the Sudoku puzzle.
  - Validation logic to ensure the input puzzle is valid before solving.

- **Backtracking Algorithm**: The core logic for solving the Sudoku puzzle. It recursively tries numbers 1-9 in empty cells and backtracks if a conflict arises.

- **Real-time Updates**: The `updateBoard` method updates the GUI in real-time as the solver progresses, with a slight delay for visualization.

- **Input Validation**: The `isValidSudoku` method ensures the input puzzle adheres to Sudoku rules before solving.

## Contributing

Contributions are welcome! If you'd like to contribute, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Make your changes and test thoroughly.
4. Submit a pull request with a detailed description of your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

- **Mo Sahil**  
- Email: [sahilbmu@gmail.com](mailto:sahilbmu@gmail.com)

## Acknowledgments

- Inspired by classic Sudoku solving algorithms and GUI implementations.
- Special thanks to the Java Swing library for providing the tools to create an interactive and responsive GUI.

---

Enjoy solving Sudoku puzzles with this interactive solver! If you have any questions or feedback, feel free to reach out.

Happy Coding! 🚀
   

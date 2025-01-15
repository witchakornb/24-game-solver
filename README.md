# 24 Game Solver

## Overview
The **24 Game Solver** is a web application that calculates all possible ways to solve the 24 Game. Given four numbers, the application evaluates all permutations of the numbers and combinations of the basic arithmetic operators (`+`, `-`, `*`, `/`) to determine if it's possible to achieve a result of 24. If no solution exists, the app informs the user accordingly.

The application features a clean, user-friendly interface and can be hosted on GitHub Pages for easy access.

## Features
- Accepts four input numbers from the user.
- Evaluates all permutations of the numbers (24 permutations).
- Tests all combinations of operators (`+`, `-`, `*`, `/`) with 3 operators (64 combinations).
- Supports five different parenthesis groupings for calculations.
- Displays all possible solutions that equal 24.
- Notifies users if no solution is found.
- Responsive and visually appealing UI.

## How to Use
1. **Access the application** via GitHub Pages or by opening `index.html` locally.
2. Enter four numbers in the input fields.
3. Click the **"Solve"** button.
4. View the results:
   - Solutions, if any, will be displayed in a list.
   - If no solution exists, a message saying "No solution found" will appear.

## Demo
A hosted version of the 24 Game Solver is available at:
[https://witchakornb.github.io/24-game-solver/](https://witchakornb.github.io/24-game-solver/)

## Development Setup

### Prerequisites
To run the project locally:
- Any modern web browser (e.g., Chrome, Firefox, Edge).
- A text editor (e.g., VS Code) for development.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/witchakornb/24-game-solver.git

   cd 24-game-solver
   ```
2. Navigate to the project folder and open `index.html` in your browser.

### Project Structure
```plaintext
24-game-solver/
│
├── index.html     # Main HTML file containing the UI and JavaScript logic
├── README.md      # Project documentation
```

## How It Works
1. **Input Processing**:
   - Users provide four numbers.
2. **Permutations and Combinations**:
   - All permutations of the four numbers are generated.
   - All possible combinations of three operators are created.
3. **Evaluation**:
   - Each permutation and operator combination is evaluated using five common parenthesis groupings.
   - Results close to 24 (with a small tolerance for floating-point arithmetic) are considered valid solutions.
4. **Output**:
   - Valid solutions are displayed in a list.
   - If no solutions exist, the app displays "No solution found."

## Example
### Input:
```
Numbers: 8, 3, 8, 3
```
### Output:
```
Solution:
((8 / 3) * 8) - 3
```

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute it.

---

Enjoy solving your 24 Game challenges!


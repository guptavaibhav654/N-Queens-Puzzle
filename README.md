# N-Queens Visualiser
Project Link https://guptavaibhav654.github.io/N-Queens-Puzzle/

This project is a web-based visualizer for the classic N-Queens problem. It allows users to see all possible arrangements of N queens on an N x N chessboard such that no two queens threaten each other.

## Features

- Input the number of queens (N) to visualize solutions for the N-Queens problem.
- Visualizes all possible valid arrangements of queens on the board.
- Step-by-step animation showing the backtracking algorithm in action.
- Adjustable speed control for the visualization using a slider.
- Displays the total number of possible arrangements for the given N.
- Interactive and easy-to-use interface.

## Usage

1. Open the `index.html` file in a modern web browser.
2. Enter the number of queens (N) in the input box. Valid values are from 1 to 8.
3. Use the slider to adjust the speed of the visualization.
4. Click the **Play** button to start the visualization.
5. The visualizer will display all possible solutions for the given N, showing the placement of queens on each board.

## Limitations

- The maximum number of queens supported is 8 to ensure performance and usability.
- The visualization may be slow for larger values of N due to the complexity of the problem.

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Font Awesome for icons

## Project Structure

- `index.html` - The main HTML page containing the UI.
- `app.js` - JavaScript file containing the logic for solving and visualizing the N-Queens problem.
- `style.css` - CSS file for styling the visualizer (linked in `index.html`).

## How It Works

The visualizer uses a backtracking algorithm to find all valid solutions for placing N queens on an N x N chessboard. It animates the process by coloring cells and placing queen icons step-by-step, allowing users to follow the algorithm's decision-making and backtracking in real time.

## License

This project is open source and free to use.

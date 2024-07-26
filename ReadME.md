# 🌟 The Game of Life 🌟

Welcome to **The Game of Life**! This project is an implementation of Conway's Game of Life, a cellular automaton devised by the British mathematician John Horton Conway in 1970. It's a zero-player game, meaning that its evolution is determined by its initial state, requiring no further input.

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/game-of-life.git
    cd game-of-life
    ```

2. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Jupyter Notebook:**

    ```bash
    jupyter notebook The\ Game\ of\ Life.ipynb
    ```

## 🎮 How to Play

1. **Open the Jupyter Notebook** and run the cells to initialize the game.
2. **Set the initial configuration** of the grid. You can customize the initial state by modifying the `initial_state` variable.
3. **Run the simulation** to see how the game evolves over time.

## 📜 Rules

The universe of the Game of Life is an infinite, two-dimensional orthogonal grid of square cells, each of which is in one of two possible states, alive or dead. Every cell interacts with its eight neighbors, which are the cells that are horizontally, vertically, or diagonally adjacent.

At each step in time, the following transitions occur:

1. **Underpopulation:** Any live cell with fewer than two live neighbors dies, as if by underpopulation.
2. **Overpopulation:** Any live cell with more than three live neighbors dies, as if by overpopulation.
3. **Reproduction:** Any dead cell with exactly three live neighbors becomes a live cell, as if by reproduction.
4. **Survival:** Any live cell with two or three live neighbors lives on to the next generation.

## 🛠️ Customization

You can customize various aspects of the game, such as:

- **Grid size**
- **Initial configuration**
- **Number of generations**

Feel free to experiment and see how different initial states evolve over time!

## 📈 Examples

Here are some famous patterns you can try:

- **Glider**
- **Lightweight Spaceship**
- **Blinker**
- **Toad**
- **Beacon**

## 🤝 Contributing

Contributions are welcome! If you have any ideas or improvements, feel free to open an issue or submit a pull request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

If you have any questions or feedback, feel free to reach out:

- **Email:** asayesimon123@gmail.com
- **GitHub:** [justsima](https://github.com/justsima)

Enjoy the game! 🎉
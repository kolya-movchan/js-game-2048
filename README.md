# 2048 Game

🎉 Welcome to the 2048 Game! A classic puzzle game where your goal is to slide numbered tiles on a grid, combine them, and aim for the ultimate tile - 2048. This implementation of the game is built using JavaScript and incorporates various technologies to provide a smooth and engaging gaming experience.

🔗 [Play 2048 Game](https://kolya-movchan.github.io/js-game-2048/)

<p align="center">
  <img src="https://github.com/kolya-movchan/js-game-2048/raw/master/src/images/game-2024.png" alt="pets-paw demo page" style="margin-bottom: 20px;">
</p>

## Technologies Used

Here's a closer look at the technologies and tools that power this 2048 Game:

### JavaScript Magic ✨

- **addEventListener**: We utilize the `addEventListener` method to capture user input from the keyboard. This allows us to interpret arrow key presses and use them to move the tiles on the game board, providing an interactive and responsive gaming experience.

- **Logical Operators (&& and ||)**: Logical operators are our best friends when it comes to implementing game logic. We've used them extensively to create branching logic that determines how the game behaves in different situations. For example, we check whether two adjacent tiles can be combined or if the game has been won or lost.

- **Math.floor() and Math.random()**: To ensure the game remains fair and challenging, we employ `Math.floor()` in combination with `Math.random()` to generate random numbers for new tiles. This ensures that we always get whole numbers representing the tiles on the game board.

- **Loops**: Loops are the workhorses of our code. We use them extensively to iterate over the game board and perform various operations on the tiles. Whether it's checking if a tile can move in a specific direction or generating/removing new tiles, loops keep the game running smoothly.

- **classList.add()**: For manipulating the game board's appearance, we turn to `classList.add()`. This handy method allows us to add and remove CSS classes from HTML elements, enabling us to highlight combined tiles and change the color of tiles with different numbers.

- **Recursive Function**: At the heart of our game logic lies a recursive function. This function handles tile combining and movement based on user input. It calls itself repeatedly to move tiles until no more moves are possible, ensuring that the game remains challenging.

- **Functions**: Functions are our building blocks for creating a modular and comprehensible codebase. We've employed functions to encapsulate various logic, making it easier to move tiles in different directions, combine adjacent tiles, and check for victory or defeat.

With this exciting mix of JavaScript and these technologies, we've crafted a delightful and addictive 2048 Game for your enjoyment. Have a blast playing, and aim for that elusive 2048 tile! 🚀🎮

## How to Play

1. **Use Arrow Keys**: Navigate the game board by using the arrow keys on your keyboard (Up, Down, Left, Right).

2. **Combine Tiles**: Tiles with the same number will merge when they collide. Combine them strategically to reach the coveted 2048 tile.

3. **Winning**: The game is won when you successfully create a tile with the number 2048.

4. **Losing**: The game ends when there are no more valid moves left, and the board is full.

5. **Keep Going**: You can continue playing even after reaching 2048 to achieve higher scores.

## Try it Out

Ready to put your puzzle-solving skills to the test? [Play the 2048 Game now!](https://kolya-movchan.github.io/js-game-2048/)
Feel free to explore, modify, and share it as you like. Happy gaming! 🎮📜

**© 2023 Mykola Movchan**
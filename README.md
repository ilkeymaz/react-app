<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

</head>
<body>
  <h1>Tic-Tac-Toe Game</h1>

  <p>This is a simple implementation of the Tic-Tac-Toe game using React. The game allows two players to take turns and marks their moves on a 3x3 grid, either with "X" or "O". The game automatically detects a winner or a draw.</p>

  <h2>Features:</h2>
  <ul>
    <li>Two players can take turns to play (X and O).</li>
    <li>Player X starts the game.</li>
    <li>It automatically displays the winner once there's a winning combination.</li>
    <li>Each square can be clicked to make a move, and the game state updates accordingly.</li>
  </ul>


  <h2>Code Explanation:</h2>
  
  <h3>Square Component</h3>
  <p>This is a functional component that represents each individual square on the Tic-Tac-Toe board. It receives two props:</p>
  <ul>
    <li><strong>value</strong>: A string representing the current value ("X", "O", or null).</li>
    <li><strong>onSquareClick</strong>: A function that handles the click event of the square.</li>
  </ul>

  <h3>Board Component</h3>
  <p>The main game board component is responsible for the overall game state. It uses React's <code>useState</code> hook to keep track of the current player (X or O) and the state of all 9 squares in the game grid. It also calculates the winner using the <code>calculateWinner</code> function and updates the UI accordingly.</p>
  
  <h3>Game Logic</h3>
  <p>The <code>handleClick</code> function updates the game state by marking a square with "X" or "O" depending on the current player. The game checks for a winner after every move and updates the status displayed on the screen.</p>

  <h3>calculateWinner Function</h3>
  <p>This function checks the squares array for any winning combinations. If a winner is found, it returns the winner ("X" or "O"); otherwise, it returns null.</p>

  <h2>How to Run:</h2>
  <ol>
    <li>Clone the repository:</li>
    <pre>git clone https://github.com/yourusername/tic-tac-toe.git</pre>
    <li>Install dependencies:</li>
    <pre>npm install</pre>
    <li>Start the development server:</li>
    <pre>npm start</pre>
  </ol>

  <h2>Technologies Used:</h2>
  <ul>
    <li>React</li>
    <li>TypeScript</li>
    <li>HTML/CSS</li>
  </ul>

  <h2>License:</h2>
  <p>This project is open-source and available under the MIT License.</p>

  <h2>Contributing:</h2>
  <p>If you would like to contribute to this project, feel free to fork the repository and submit a pull request with your proposed changes!</p>
</body>
</html>

# ReactJS-NodeJS-PracticalExam

## Tic Tac Toe

This is a simple Tic Tac Toe game that allows two players to play on the same computer. The game is built using React for the frontend and Node.js for the backend.

### Project Structure

tic-tac-toe/<br>
├── client/<br>
│ ├── src/<br>
│ │ └── App.tsx<br>
│ └── public/<br>
│ └── index.html<br>
└── server/<br>
└── src/<br>
├── evaluateBoardState.ts<br>
└── server.ts<br>

The project consists of two main directories: `client` and `server`. The `client` directory contains the React frontend code, while the `server` directory contains the Express.js server code.

- `client/`: Contains the React frontend code.
  - `src/`: Contains the main React component file.
    - `App.tsx`: Main component that renders the Tic Tac Toe game.
  - `public/`: Contains the `index.html` file, which is the HTML template for the React app.

  &nbsp; 
- `server/`: Contains the Express.js server code.
  - `src/`: Contains the server code files.
    - `evaluateBoardState.ts`: Implements the logic to evaluate the board state.
    - `server.ts`: Sets up the Express.js server and defines the API endpoints.


### Development Environment

To set up the development environment and run the Tic Tac Toe game locally, follow these steps:

1. Clone the repository: `https://github.com/Kodego-Practical-Exam/ReactJS-NodeJS-practicalExam-Answer.git`
2. Install dependencies for the client: `cd tic-tac-toe/client` and run `npm install`
3. Install dependencies for the server: `cd ../server` and run `npm install`
4. Start the server: `npm start` in the `server` directory, and should run in port `3001`
5. Start the client: `npm start` in the `client` directory, and should run in the port `3000`
6. Finally, open your browser and navigate to `http://localhost:3000` to access the Tic Tac Toe game.

### Compromises and Limitations

To finish the minimum requirements I focused on the basic functionality stated on the practical exam. But if I can more features, here are the following:

1. Improve css and overall UI.
2. Allow the game to be played at same time in different browsers.
3. Add a real-time chat functionality.
4. Improve, code and logic.

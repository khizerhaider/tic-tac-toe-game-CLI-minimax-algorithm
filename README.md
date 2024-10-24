# tic-tac-toe-game-minimax-algorithm
Tic-Tac-Toe Game
🎮 Overview

Welcome to the Tic-Tac-Toe game! This is a simple and fun command-line game where you can challenge yourself against a computer opponent. The computer is smart—thanks to the Minimax algorithm—making it a tough competitor! The objective is to get three of your symbols (X or O) in a row, whether horizontally, vertically, or diagonally.
✨ Features

    Play against the Computer: Choose to play as X or O and see if you can outsmart the AI!
    Smart Computer: The computer uses the Minimax algorithm to make the best possible moves.
    Game Status Updates: You’ll always know the current state of the board.
    Win or Draw Detection: The game automatically checks if there’s a winner or if the game ends in a draw.
    Easy to Use: A simple command-line interface for a seamless experience.

🚀 Installation

To get started, you'll need to have Python 3.x installed on your computer. If you don’t have it yet, you can download it from python.org.
1.Clone the Repository: git clone "https://github.com/khizerhaider/tic-tac-toe-game-minimax-algorithm.git"
cd tic-tac-toe
2.Run the Game:
python3 tic_tac_toe.py
🕹️ How to Play

    Start the Game: Run the script to begin.
    Choose Your Symbol: You’ll be prompted to select X or O.
    Decide Who Goes First: You can choose to play first or let the computer make the first move.
    Make Your Move: Follow the prompts to enter your move based on the displayed board. The positions correspond to:
    1 | 2 | 3
    ---------
    4 | 5 | 6
    ---------
    7 | 8 | 9
      Enjoy the Game: Keep playing until someone wins or the game ends in a draw!

🤖 How the Computer Works

The computer uses the Minimax algorithm, a smart strategy for playing games. Here’s how it works:

    Analyzing Moves: The computer looks ahead at all possible future moves for both players.
    Scoring: It assigns scores to the outcomes: +10 if the computer wins, -10 if you win, and 0 for a draw.
    Choosing the Best Move: It selects the move that maximizes its chances of winning while minimizing yours, making it a formidable opponent!

📜 Code Structure

Here’s a quick overview of how the game is organized:

    evaluate_board(current_board): Checks the current state of the board.
    check_winner(current_board, current_player): Sees if a player has won.
    is_game_over(current_board): Determines if the game has ended.
    get_empty_cells(current_board): Finds the empty spots on the board.
    make_move(row, col, current_player): Places your symbol on the board.
    minimax_algorithm(board_state, depth, current_player): The brain behind the computer’s smart moves.
    display_board(board_state, computer_symbol, human_symbol): Shows the current board in the console.
    start_game(): This is where the magic begins—the main function that runs the game.

🤝 Contributing

We’d love to see your contributions! If you have ideas or improvements, feel free to fork the repository and submit a pull request.

    

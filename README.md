<h1>AI Tic-Tac-Toe Bot</h1>

<p>
    I developed an AI-powered <strong>Tic-Tac-Toe</strong> bot using Python. 
    The AI implements the Minimax algorithm to play optimally, ensuring that it never loses when playing against a human player. 
    The graphical user interface is powered by <strong>PyGame</strong>, making it a fun and interactive experience to play against the AI.
</p>

<h2>Game Features</h2>

<ul>
    <li><strong>Player vs AI:</strong> You can play against an intelligent AI bot that uses the Minimax algorithm.</li>
    <li><strong>Graphical Interface:</strong> The game features a clean and simple GUI built using PyGame.</li>
    <li><strong>Optimal AI:</strong> The AI bot ensures that it either wins or ties every game, as Tic-Tac-Toe is a tie with optimal play on both sides.</li>
</ul>

<h2>How to Play</h2>

<ol>
    <li>Run the game using the following command in your terminal:
        <pre><code>python runner.py</code></pre>
    </li>
    <li>The player playing as <strong>X</strong> always goes first. You can either make a move by clicking on the board or let the AI make its move.</li>
    <li>The game ends when a player has three in a row (horizontally, vertically, or diagonally) or when all cells are filled, resulting in a tie.</li>
</ol>

<h2>File Structure</h2>

<ul>
    <li><strong>runner.py</strong>: Handles the graphical interface and runs the game. It initializes the game window and captures user inputs.</li>
    <li><strong>tictactoe.py</strong>: Contains all the core game logic and AI. This includes functions to check valid moves, determine the game state, and implement the Minimax algorithm.</li>
</ul>

<h2>AI Logic - Minimax Algorithm</h2>

<p>
    The AI is implemented using the <strong>Minimax algorithm</strong>, which ensures optimal play. The algorithm evaluates the game tree by considering all possible moves, and selects the move that maximizes its chances of winning or at least results in a tie. Here's a brief explanation of the key functions in <strong>tictactoe.py</strong>:
</p>

<ul>
    <li><strong>player(board)</strong>: Returns which player’s turn it is (either <em>X</em> or <em>O</em>).</li>
    <li><strong>actions(board)</strong>: Returns the set of all possible actions that can be taken on the board.</li>
    <li><strong>result(board, action)</strong>: Returns the new board after a player makes a move.</li>
    <li><strong>winner(board)</strong>: Returns the winner of the game, if there is one.</li>
    <li><strong>terminal(board)</strong>: Checks if the game is over (either due to a win or a tie).</li>
    <li><strong>utility(board)</strong>: Assigns a score of 1 if <em>X</em> wins, -1 if <em>O</em> wins, and 0 if it’s a tie.</li>
    <li><strong>minimax(board)</strong>: Implements the Minimax algorithm to determine the optimal move for the current player.</li>
</ul>

<h2>Requirements</h2>

<p>
    To run the game, you will need:
</p>

<ul>
    <li>Python 3.x</li>
    <li>PyGame library: You can install it using:
        <pre><code>pip install pygame</code></pre>
    </li>
</ul>

<h2>Running the Game</h2>

<ol>
    <li>Clone the repository:
        <pre><code>git clone https://github.com/RikGanguli/AI-TicTacToe-Bot.git</code></pre>
    </li>
    <li>Navigate to the project directory:
        <pre><code>cd AI-TicTacToe-Bot</code></pre>
    </li>
    <li>Run the game:
        <pre><code>python runner.py</code></pre>
    </li>
</ol>

<h2>Credits</h2>

<p>
    Developed by Rik Ganguli Biswas.
</p>



Download Link: https://assignmentchef.com/product/solved-interactive-tic-tac-toe
<br>
<a href="https://www.youtube.com/playlist?list=PLhOuww6rJJNOlaMDHHIQrvWZn--GGNlHU" rel="nofollow">https://www.youtube.com/playlist?list=PLhOuww6rJJNOlaMDHHIQrvWZn–GGNlHU</a>

Write a Python program called <code>itictactoe.py</code> that will play an interactive game of Tic-Tac-Toe starting from a blank board and iterating between players <code>X</code> and <code>O</code> until the game is finished due to a draw or a win. When the game starts, a blank board with cells 1-9 should be shown along with a prompt for the current player (always starting with <code>X</code>) to select a cell:

<pre><code>-------------| 1 | 2 | 3 |-------------| 4 | 5 | 6 |-------------| 7 | 8 | 9 |-------------Player X, what is your move? [q to quit]: 1</code></pre>

If a player tries to select an occupied cell, the move is disallowed and the same player goes until a valid choice is made:

<pre><code>-------------| X | 2 | 3 |-------------| 4 | 5 | 6 |-------------| 7 | 8 | 9 |-------------Player O, what is your move? [q to quit]: 1-------------| X | 2 | 3 |-------------| 4 | 5 | 6 |-------------| 7 | 8 | 9 |-------------Cell "1" already takenPlayer O, what is your move? [q to quit]:</code></pre>

Play should stop when a player has won:

<pre><code>-------------| X | O | 3 |-------------| X | O | 6 |-------------| 7 | 8 | 9 |-------------Player X, what is your move? [q to quit]: 7X has won!</code></pre>

Or when the game is a draw:

<pre><code>-------------| X | O | O |-------------| O | X | X |-------------| X | 8 | O |-------------Player X, what is your move? [q to quit]: 8All right, we'll call it a draw.</code></pre>
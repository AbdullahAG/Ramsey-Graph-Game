# Ramsey-Graph-Game

### Welcome to the Ramsey Graph Game!

In this game, two players take turns coloring edges in a randomly generated graph. The goal is to create a monochromatic complete subgraph of a given size before the other player does.
Rules

The Ramsey Graph Game is a two-player game played on a complete graph with n vertices. Each player takes turns coloring an uncolored edge of the graph in their own color. The first player colors edges with red, and the second player colors edges with blue.

The game ends when either:

* One player creates a monochromatic triangle (a set of three vertices connected by edges of the same color), in which case they win.

* All edges are colored and no player has created a monochromatic triangle, in which case the game is a tie.

<br>
In this implementation of the game, players can also win by creating a monochromatic path of any length (not just three), with k vertices, where k is chosen at the start of the game.

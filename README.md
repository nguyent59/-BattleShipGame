# -BattleShipGame
Build the BattleShip game by C++ language

The Battleship game you are implementing is a simplified version of the electronic Battleship game
played in one player mode.

The game is played on four grids, two for each player. Each player has a Battlefield Grid and a Firing
Grid. The grids are a 10 by 10 square. The individual squares in the grid are identified by the x coordinate
(indicated by a letter) followed by the y coordinate (indicated by a number).

The Battlefield Grid holds the position of each player's fleet and the status of the fleet. The Firing Grid
hold the coordinates of each "Firing" during the game and whether the shot was a hit or miss.

Each player will have five ships to place on their Battlefield Grid. Each player will vary in size (the
number of squares they take up) based on Ship Type. The ships cannot overlap, so only one Ship can
occupy any given square in the grid. The types and numbers of ships allowed are the same for each
player.

# Game Play.
Randomly select who will start the game, the Computer Player (CP), or the Human Player (HP).
Proceed in rounds with both the CP and the HP getting a turn to "fire" into the other player's Battle Grid
in turns.

Firing is done by selecting a square on the opposing player's Battlefield Grid. The HP will choose the
square by entering the grid coordinates. The CP will randomly choose a square that has not yet been
selected.

If the selected square is occupied by a ship, that Ship is considered sunk. It's position should be notated
on the Firing Grid and it should be identified as "sunk". If the selected square is not occupied, that
square should be marked as "missed" on the Firing Grid so it will not be chosen again.
When prompting the HP for firing coordinates, also give them the option to quit the game if desired.

# Winning the Game.
When a player has sunk all of the opposing plays ships, the game ends. Identify the winner and Display
the Battlefield and Firing Grids of each player.

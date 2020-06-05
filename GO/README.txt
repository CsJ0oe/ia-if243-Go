myPlayer.py:
	# Techniques used:
	TODO: évoquez comment vous avez décidé d'utiliser telle ou telle technique
		- Minimax algorithm
		- Alpha-Beta pruning
		- iterative deepening
		- Transposition table
	# Heuristique
	TODO: décrivez l'heuristique codée

mctsPlayer.py:
	Monte Carlo Tree Search:
	we started with this algorithm because we didn't have a clear idea how to implement the evaluation function,
	but the implementation of Goban.py wasn't fast enough to run multiple simulation (300 simulation in 7.4 seconds, but we needed 1000 at least to make a good move),
	so we dropped this idea, and we ended up with the above implementation of alpha-beta (myPlayer.py)
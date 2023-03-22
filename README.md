# AI_Passing_the_Impossible
"Passing AI: Achieving the Impossible" is a project where an AI agent was developed to navigate a randomly generated 5x5 board, facing various obstacles and challenges along the way. The objective of the game is for the agent to successfully pass the course within the allotted time limit. This project is akin to the classic "Wumpus World" game, where the agent must explore the environment and make decisions based on sensory inputs.


The code that is contained in the file `workInProgress.ipynb` is responsible for the world definition from the perspective of the game (full definition) and the player (the known information + information obtained from the percepts)

Additional functionality is implemented that makes the game playable for the player. (The said functionality is a bit cursed and not fully complete.) 

Some functions that return suggested solutions are also implemented, but some calculations that were included in the paper were done "by hand". This means that we used the file `world generation.ipynb` to generate game states and checked if the said algorithm succeeded in that world or not.

# Vacuum_Sim
AI Vacuum agent (Course work)

In this project we design an AI program for a vacuum cleaner AI that is supposed to orient itself through a room and clean up all dirt while sensing and avoiding obstacles.

-- As the vacuum moves around in the room, it senses obstacles and dirt. It cannot trespass the obstacles, but it vacuumes the dirt.

-- We model the room as a $n\times m$ matrix of square blocks, at first every entry is give the value 0. An obstacle that the vacuum senses will be given a high value in the matrix. Dirt is not given any value, instead we prioritize moving to all possible squares so that all dirt is guaranteed to be picked up.   

-- Both the positions of the obstacles and the starting position of the vacuum are randomized. The vacuum can move up, down, left or right in the matrix. The program finds the best path using A* search.

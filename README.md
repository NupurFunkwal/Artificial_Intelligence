# Solved AI Problems

#### Genetic Algorithms
Genetic algorithms are based on the ideas of natural selection and genetics. These are intelligent exploitation of random search provided with historical data to direct the search into the region of better performance in solution space. They are commonly used to generate high-quality solutions for optimization problems and search problems. The folder contains solutions for improved versions of genetic algorithm for 8Queens and TSP.


#### MineField

There is an agent in room [1,1]. The goal of the agent is to exit the Land mine world alive. The agent can exit the Land mine world by reaching room [4,4]. The Land mine world may contain several landmines, but there will always be a safe path from [1,1] to the exit. The agent will be able to detect a land mine from the rooms adjacent to the room containing the land mine. There will be three possible percepts: ’= 0’, ’= 1’ and ’> 1’. The percept ’= 1’ means that one of the adjacent rooms have a land mine. The percept ’> 1’ means that two or more of the adjacent rooms have a land mine.

This is a python program that uses propositional logic sentences to check which rooms are safe. The inference should be drawn using the SAT solver python-sat
The logical agent can take four actions: Up, Down, Left and Right. These actions help the agent move from one room to an adjacent room. You may assume that there will always be a safe path that the agent can take to exit the Wumpus world. In other words, it can be assumed that the agent will not have to take a risk while navigating the minefield. The goal is to make the agent move from [1,1] to [4,4] using minimum number of actions.

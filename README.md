# Matchstick_Logic_Game (Made in Java)
A game played between the code and the player. There are an n amount of matches on a table, and each player can take either 1 or 2 matches at a time. The player to pick out the last match loses.

The logic- we need to recognise what the winning/losing poistions are. If we take all the possibilities using brute force for a small set of numbers, we can note down all the winning and losing positions. But we need a pattern that we can adopt into an n number of matches. Now, if we do postion%3, we see that all the winning positions= either 2 or 0, and all the losing positions= only 1. Therefore, using this data, we can build the game. 

Given all this though, it is clear that the winner can be determined by who starts and wheather the starting position is a winning or losing position.



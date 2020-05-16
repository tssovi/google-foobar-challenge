<h1 align= "center"><b>Save Beta Rabbit</b></h1>

Oh no! The mad Professor Boolean has trapped Beta Rabbit in an NxN grid of rooms. In the center of each room (except for the top left room) is a hungry zombie. In order to be freed, and to avoid being eaten, Beta Rabbit must move through this grid and feed the zombies.
 
Beta Rabbit starts at the top left room of the grid. For each room in the grid, there is a door to the room above, below, left, and right. There is no door in cases where there is no room in that direction. However, the doors are locked in such a way that Beta Rabbit can only ever move to the room below or to the right. Once Beta Rabbit enters a room, the zombie immediately starts crawling towards him, and he must feed the zombie until it is full to ward it off. Thankfully, Beta Rabbit took a class about zombies and knows how many units of food each zombie needs be full.
 
To be freed, Beta Rabbit needs to make his way to the bottom right room (which also has a hungry zombie) and have used most of the limited food he has. He decides to take the path through the grid such that he ends up with as little food as possible at the end.
 
Write a function solution(food, grid) that returns the number of units of food Beta Rabbit will have at the end, given that he takes a route using up as much food as possible without him being eaten, and ends at the bottom right room. If there does not exist a route in which Beta Rabbit will not be eaten, then return -1.
 
food is the amount of food Beta Rabbit starts with, and will be a positive integer no larger than 200.
 
grid will be a list of N elements. Each element of grid will itself be a list of N integers each, denoting a single row of N rooms. The first element of grid will be the list denoting the top row, the second element will be the list denoting second row from the top, and so on until the last element, which is the list denoting the bottom row. In the list denoting a single row, the first element will be the amount of food the zombie in the left-most room in that row needs, the second element will be the amount the zombie in the room to its immediate right needs and so on. The top left room will always contain the integer 0, to indicate that there is no zombie there.
 
The number of rows N will not exceed 20, and the amount of food each zombie requires will be a positive integer not exceeding 10.

<h2 align= "center"><b>Test Cases</b></h2>

```

Input:
    solution.solution(7, [[0, 2, 5], [1, 1, 3], [2, 1, 1]])
Output:
    0

Input:
    solution.solution(12, [[0, 2, 5], [1, 1, 3], [2, 1, 1]])
Output:
    1

```

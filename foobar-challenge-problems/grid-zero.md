<h1 align= "center"><b>Grid Zero</b></h1>

You are almost there. The only thing between you and foiling Professor Boolean's plans for good is a square grid of lights, only some of 
which seem to be lit up. The grid seems to be a lock of some kind. That's interesting. Touching a light toggles the light, as well as 
all of the other lights in the same row and column as that light. 

Wait! The minions are coming - better hide.

Yes! By observing the minions, you see that the light grid is, indeed, a lock. The key is to turn off all the lights by touching some of 
them. The minions are gone now, but the grid of lights is now lit up differently. Better unlock it fast, before you get caught.

The grid is always a square. You can think of the grid as an NxN matrix of zeroes and ones, where one denotes that the light is on, and 
zero means that the light is off.

For example, if the matrix was

    1 1
    0 0

Touching the bottom left light results in

    0 1
    1 1

Now touching the bottom right light results in

    0 0
    0 0

...which unlocks the door.

Write a function solution(matrix) which returns the minimum number of lights that need to be touched to unlock the lock, by turning off 
all the lights. If it is not possible to do so, return -1. 

The given matrix will be a list of N lists, each with N elements. Element matrix[i][j] represents the element in row i, column j of the 
matrix. Each element will be either 0 or 1, 0 representing a light that is off, and 1 representing a light that is on. 

N will be a positive integer, at least 2 and no more than 15.

<h2 align= "center"><b>Test Cases</b></h2>

```

Input:
    solution.solution([[1, 1], [0, 0]])
Output:
    2

Input:
    solution.solution([[1, 1, 1], [1, 0, 0], [1, 0, 1]])
Output:
    -1

```

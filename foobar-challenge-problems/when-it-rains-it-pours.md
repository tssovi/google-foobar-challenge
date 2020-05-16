<h1 align= "center"><b>When It Rains It Pours</b></h1>

It's raining, it's pouring. You and your agents are nearing the building where the captive rabbits are being held, but a sudden storm puts your escape plans at risk. The structural integrity of the rabbit hutches you've built to house the fugitive rabbits is at risk because they can buckle when wet. Before the rabbits can be rescued from Professor Boolean's lab, you must compute how much standing water has accumulated on the rabbit hutches.

Specifically, suppose there is a line of hutches, stacked to various heights and water is poured from the top (and allowed to run off the sides). We'll assume all the hutches are square, have side length 1, and for the purposes of this problem we'll pretend that the hutch arrangement is two-dimensional.

For example, suppose the heights of the stacked hutches are [1,4,2,5,1,2,3] (the hutches are shown below):

    . . . I . . .
    . I . I . . .
    . I . I . . I
    . I I I . I I
    I I I I I I I
    1 4 2 5 1 2 3

When water is poured over the top at all places and allowed to runoff, it will remain trapped at the 'O' locations:

    . . . I . . .
    . I X I . . .
    . I X I X X I
    . I I I X I I
    I I I I I I I
    1 4 2 5 1 2 3

The amount of water that has accumulated is the number of Xs, which, in this instance, is 5.

Write a function called solution(heights) which, given the heights of the stacked hutches from left-to-right as a list, computes the total area of standing water accumulated when water is poured from the top and allowed to run off the sides.

The heights array will have at least 1 element and at most 9000 elements. Each element will have a value of at least 1, and at most 100000.

<h2 align= "center"><b>Test Cases</b></h2>

```

Input:
    solution.solution([1, 4, 2, 5, 1, 2, 3])
Output:
    5

Input:
    solution.solution([1, 2, 3, 2, 1])
Output:
    0

```

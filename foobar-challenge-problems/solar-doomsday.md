<h1 align= "center"><b>Solar Doomsday</b></h1>

Who would've guessed? Doomsday devices take a LOT of power. Commander Lambda wants to supplement the LAMBCHOP's quantum 
antimatter reactor core with solar arrays, and she's tasked you with setting up the solar panels. 
Due to the nature of the space station's outer paneling, all of its solar panels must be squares. Fortunately, you have 
one very large and flat area of solar material, a pair of industrial-strength scissors, and enough MegaCorp Solar Tape(TM) 
to piece together any excess panel material into more squares. For example, if you had a total area of 12 square yards of 
solar material, you would be able to make one 3x3 square panel (with a total area of 9). That would leave 3 square yards, 
so you can turn those into three 1x1 square solar panels.

Write a function solution(area) that takes as its input a single unit of measure representing the total area of solar panels 
you have (between 1 and 1000000 inclusive) and returns a list of the areas of the largest squares you could make out of 
those panels, starting with the largest squares first. So, following the example above, solution(12) would return [9, 1, 1, 1].

<h2 align= "center"><b>Test Cases</b></h2>

```

Input:
    solution.solution(12)
Output:
[9, 1, 1, 1]

Input:
    solution.solution(15324)
Output:
[15129, 169, 25, 1]

```

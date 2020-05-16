<h1 align= "center"><b>Breeding Like Rabbits</b></h1>

As usual, the zombie rabbits (zombits) are breeding... like rabbits! But instead of following the Fibonacci sequence like all good rabbits do, the zombit population changes according to this bizarre formula, where R(n) is the number of zombits at time n:

    R(0) = 1
    R(1) = 1
    R(2) = 2
    R(2n) = R(n) + R(n + 1) + n (for n > 1)
    R(2n + 1) = R(n - 1) + R(n) + 1 (for n >= 1)

(At time 2, we realized the difficulty of a breeding program with only one zombit and so added an additional zombit.)

Being bored with the day-to-day duties of a henchman, a bunch of Professor Boolean/'s minions passed the time by playing a guessing game: when will the zombit population be equal to a certain amount? Then, some clever minion objected that this was too easy, and proposed a slightly different game: when is the last time that the zombit population will be equal to a certain amount? And thus, much fun was had, and much merry was made.

(Not in this story: Professor Boolean later downsizes his operation, and you can guess what happens to these minions.)

Write a function solution(str_S) which, given the base-10 string representation of an integer S, returns the largest n such that R(n) = S. Return the answer as a string in base-10 representation. If there is no such n, return "None". S will be a positive integer no greater than 10^25.

<h2 align= "center"><b>Test Cases</b></h2>

```

Input:
    solution.solution("7")
Output:
    "4"

Input:
    solution.solution("100")
Output:
    "None"

```

<h1 align= "center"><b>Name That Rabbit</b></h1>

"You forgot to give Professor Boolean's favorite rabbit specimen a name? You know how picky the professor is! Only particular names will do! Fix this immediately, before you're... eliminated!"

Luckily, your minion friend has already come up with a list of possible names, and we all know that the professor has always had a thing for names with lots of letters near the 'tail end' of the alphabet, so to speak. You realize that if you assign the value 1 to the letter A, 2 to B, and so on up to 26 for Z, and add up the values for all of the letters, the names with the highest total values will be the professor's favorites. For example, the name Annie has value 1 + 14 + 14 + 9 + 5 = 43, while the name Earz, though shorter, has value 5 + 1 + 18 + 26 = 50.

If two names have the same value, Professor Boolean prefers the lexicographically larger name. For example, if the names were AL (value 13) and CJ (value 13), he prefers CJ.

Write a function solution(names) which takes a list of names and returns the list sorted in descending order of how much the professor likes them.

There will be at least 1 and no more than 1000 names. Each name will consist only of lower case letters. The length of each name will be at least 1 and no more than 8.

<h2 align= "center"><b>Test Cases</b></h2>

```

Input:
    solution.solution(["annie", "bonnie", "liz"])
Output:
    ["bonnie", "liz", "annie"]

Input:
    solution.solution(["abcdefg", "vi"])
Output:
    ["vi", "abcdefg"]

```

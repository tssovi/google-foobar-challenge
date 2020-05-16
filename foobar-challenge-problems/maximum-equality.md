<h1 align= "center"><b>Maximum Equality</b></h1>

Your colleague Beta Rabbit, top notch spy and saboteur, has been working tirelessly to discover a way to break into Professor Boolean's lab and rescue the rabbits being held inside. He has just excitedly informed you of a breakthrough - a secret bridge that leads over a moat (likely filled with alligators, or zombies, or alligator-zombies, given his penchant for zombifying... You should probably stop thinking about it.). The only way over the moat is by a rickety train, but there's a catch: The train is rigged such that under particular conditions, it will throw its passengers overboard. You've determined that the best odds of getting safely across is to have as many cars share the same exact weight as possible. Luckily, all the rabbits' weights are essentially equal. How convenient!

The rabbits are already organized into families, but these families vary in size. In order for this plan to work, you need to find a way to make as many train cars as possible have exactly the same number of passengers.

Beta Rabbit will provide you with an array x, where each element in the array is an integer representing the number of rabbits that want to share a particular car. You can give the command for a rabbit to move from any one car to any other, and you have enough time to give as many commands as you need. In other words, choose two elements of the array, x[i] and x[j] (idistinct fromj) and simultaneously increment x[i] by 1 and decrement x[j] by 1. Your goal is to get as many elements of the array to have equal value as you can.

For example, if the array was [1,4,1] you could perform the operations as follows:

    Send a rabbit from the 1st car to the 0th: increment x[0], decrement x[1], resulting in [2,3,1]
    Send a rabbit from the 1st car to the 2nd: increment x[2], decrement x[1], resulting in [2,2,2]

All the elements are of the array are equal now, and you've got a strategy to report back to Beta Rabbit!

Note that if the array was [1,2], the maximum possible number of equal elements we could get is 1, as the cars could never have the same number of rabbits in them.

Write a function answer(x), which takes the array of integers x and returns the maximum number of equal array elements that we can get, by doing the above described command as many times as needed.

The number of cars in the train (elements in x) will be at least 2, and no more than 100. The number of rabbits that want to share a car (each element of x) will be an integer in the range [0, 1000000].

<h2 align= "center"><b>Test Cases</b></h2>

```

Input:
    solution.solution([1, 4, 1])
Output:
    3

Input:
    solution.solution([1, 2])
Output:
    1

```

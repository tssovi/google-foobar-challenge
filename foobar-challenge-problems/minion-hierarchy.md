<h1 align= "center"><b>Minion Hierarchy</b></h1>

Rumor has it there's a mad scientist out there who has abducted hundreds of rabbits to test out a new zombie serum. 
Agent Beta Rabbit, spy and brilliant mathematician, storms into the room: "I know who's behind that plan. It's a man who calls himself 
Professor Boolean. My preliminary recon data shows that he's operating a lab somewhere on the islands near Silicon Valley. 
I also recently got a tip that Professor Boolean's lab minions have a certain hierarchical structure: Each manager has no more than 7 direct reports."

Interesting... This information can help us estimate how many minions are working in this lab, and thus, the size of this operation. 
We need to know what we're facing here. Write a function called answer(x) that returns the maximum number of minion employees a company following the "no more than 7 direct reports" theory can have, with no more than x levels of supervision.

You can assume that:

    1. Professor Boolean is the highest level of supervision and has no manager.
    2. Each minion employee (other than Professor Boolean) has exactly one manager.

For example, with no more than 1 level of supervision, we could have a maximum of 8 employees: Professor Boolean and his 7 reports.

x will be a positive integer, not exceeding 10.

<h2 align= "center"><b>Test Cases</b></h2>

```

Input:
    solution.solution(1)
Output:
    8

Input:
    solution.solution(2)
Output:
    57

```

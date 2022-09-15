# hacker-rank-Fibonacci-Modified

https://www.hackerrank.com/challenges/fibonacci-modified/problem

Given three integers, t1, t2, and N, compute and print the Nth  term of a modified Fibonacci sequence.

```
Example:
t1 = 0
t2 = 1
n = 6

where a^^b is a to the power of b.

• t3 = 0 + 1^^2 = 1
• t4 = 1 + 1^^2 = 2
• t5 = 1 + 2^^2 = 5
• t6 = 2 + 5^^2 = 27

Constraints
• 0 ≤ t1, t2 ≤ 2
• 3 ≤ n ≤ 20
• t(n)  may far exceed the range of a -bit integer.

Sample Input:
0 1 5

Sample Output:
5

Note:
test cases:
#0:   0 1  5
#1:   0 1 10
#2:   1 1 20
#3:   1 2 20 << current cpp code times out, too slow with deque<BigInt>, 
             << cpp passses when internal digits uses vector<int> instead of string class
#4:   1 2 15
#5:   2 0 12
#6:   2 2 20 << current cpp code times out, too slow
#7:   0 2  9
#8:   1 1  9
#9:   2 1  7


fib-mod.js  Passes all tests #0 through #9.
fib-mod.cpp Times out on test case 3 & 6. Passes 0,1,2,_,4,5,_,7,8,9
```


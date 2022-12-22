<h1 align="center"> Algorithm Design and Analysis </h1>

<h2>To be covered</h2>

:white_check_mark: Sieve - Eratosthenes, Linear, Bitwise, Segmented<br>
:white_check_mark: Divisor - Count, Sum<br>
:white_check_mark: Phi<br>
:white_check_mark: Modular Inverse - with Power, with Ext. euclid<br>
:white_check_mark: CRT - Ext. Euclid

:white_check_mark: Floyd Warshall<br>
:white_check_mark: Bellman Ford<br>
:white_check_mark: Heapsort - Heap<br>
:white_check_mark: Counting Sort, Radix Sort, Bucket Sort<br>
Order Statistics<br>
Hash Table<br>
Binary Search Tree<br>
Balance Binary Search Tree - Treap / AVL Tree

:white_check_mark: DP: Top Down(Recursive), Bottom Up(Iterative), 0-1 Knapsack<br>
:white_check_mark: Longest Common Subsequence<br>
Matrix Chain Multiplication, CoinChange<br>
Greedy - Task Scheduling<br>

:white_check_mark: Max Flow - Ford Fulkerson

:white_check_mark: String Matching - KMP, Rabin Karp (Hashing)<br>
Suffix Array<br>
Strongly Connected Component

FFT* (probably)

**Covered in CP Course**<br>
- [x] Quicksort
- [x] DSU
- [x] MST
- [x] Dijkstra
- [x] DFS 
- [x] BFS

<br><h2><u>Lecture-01: 23th August, 2022</u></h2>

1. Sieve of Eratosthenes
2. Linear Sieve

<br><h2><u>Lecture-02: 28th August, 2022</u></h2>

1. Bitwise Operation
2. Bitwise Sieve


<br><h2><u>Lecture-03: 30th August, 2022</u></h2>

1. Segmented Sieve


<br><h2><u>Lecture-04: 4th September, 2022</u></h2>

1. Euler phi
1. Count of Divisor
2. Sum of Divisor
3. Prime in cube root complexity, N = P * Q * R, Miler Rabin

<br><h2><u>Lecture-05: 6th September, 2022</u></h2>

1. BigMod / Modular Exponentiation
2. [Extended Euclid](https://cp-algorithms.com/algebra/extended-euclid-algorithm.html)
3. Modular Multiplicative Inverse
4. Fermat's Little Theorem


<br><h2><u>Lecture-06: 11th September, 2022</u></h2>

1. Shortest Path 
2. Floyd Warshall

<br><h2><u>Lecture-07: 18th September, 2022</u></h2>

1. Bellman Ford
2. Chinese Remainder Theorem - Weak Form

<br><h2><u>Lecture-08: 20th September, 2022</u></h2>

1. Chinese Remainder Theorem - Strong Form

<br><h2><u>Lecture-09: 25th September, 2022</u></h2>

1. Heap Sort (Heapify & Sorting)

<br><h2><u>Lecture-10: 16th October, 2022</u></h2>

1. Stable Sort properties
2. Count Sort


<br><h2><u>Lecture-11: 18th October, 2022</u></h2>

1. Primary info about Git operation.
2. Pull Request, Fork, Collaborations.
3. Sublime Merge

<br><h2><u>Lecture-12: 23th October, 2022</u></h2>

1. Radix Sort
2. Bucket sort

<br><h2><u>Lecture-13: 30th October, 2022</u></h2>

Algorithm & Complexity Analysis

1. Merge Sort 
2. Quick Sort

<br><h2><u>Lecture-14: 8th November, 2022</u></h2>

1. String Hashing
    - h(k1) = h(k2) [k1!=k2]<br>
    - if this condition is violated, collision occurs.
    - Goal is to reduce collision probability.


2. Ways to mitigate collision
    1. **Hashing With Chain**<br>
        For each index, a linked list

    2. **Linear Probing**<br>
        Put in immediate next empty index. Worst case of insertion is O(n).

    3. **Quadratic Probing**<br>
        Put in index derived from formula. Worst case improved.


3. How to retrieve?
4. Why prime is used to mod?

5. Load Factor (alpha)
    - At most how many value will be mapped at a index?
    - N/K  (Assuming keys are random)
    - So, O(1 + alpha)

6. Resource

    - [Hash Table 1](https://www.programiz.com/dsa/hash-table)
    - [Hash Table 2](https://www.hackerearth.com/practice/data-structures/hash-tables/basics-of-hash-tables/tutorial/)
    - [Hash Table 3](https://datastructures.maximal.io/hash-tables/)
    - [Hashing](https://medium.com/basecs/hashing-out-hash-functions-ea5dd8beb4dd)



<br><h2><u>Lecture-15: 13th November, 2022</u></h2>

1. Hashing proof
2. Universal Hashing Function
3. Random Indicator

<br><h2><u>Lecture-16: 15th November, 2022</u></h2>

1. Ford Fulkerson for MaxFlow

<br><h2><u>Lecture-17: 22th November, 2022</u></h2>

1. 0-1 knapsack
2. Top Down/Recusive & Bottom Up/Iterative approach
3. Next Class: Coin Change, LCS
4. [DP Resource](https://bit.ly/dpseriestuf)

<br><h2><u>Lecture-18: 4th December, 2022</u></h2>

1. Length of **Longest Common Subsequence (LCS)** with Top-Down & Bottom-Up approach

2. Print the Subsequence

<br><h2><u>Lecture-19: 13th December, 2022</u></h2>

1. KMP
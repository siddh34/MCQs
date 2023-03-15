# DAA MCQ's

## Unit 1  

> Q1. An ___ is defined as a set of well-defined instructions used to accomplish a particular task.

    A. Algorithm
    B. Function
    C. Program
    D. Procedure

**Answer  :** Option A

> Q2. The measure of the longest amount of time possibly taken to complete an algorithm is expressed as  ___

    A. Little-O
    B. Little-Omega
    C. Big-Omega
    D. Big-O

**Answer  :** Option D

> Q3. A ___ is a compact, informal, and environment-independent description of a computer programming algorithm.

    A. Stack
    B. Queue
    C. Psuedocode
    D. Non-linear data structure

**Answer  :** Option C

> Q4. ___ of an algorithm is the amount of time required for it to execute.

    A. Time complexity
    B. Space complexity
    C. Compiling time
    D. Best case

**Answer  :** Option A

> Q5. Which of the following is used for solving the N Queens Problem

    A. Greedy Algorithm
    B. Dynamic Programming
    C. Backtracking
    D. Sorting

**Answer  :** Option C

> Q6. ______is the first step in solving the problem ?

    A. Understanding the Problem
    B. Identify the Problem
    C. Evaluate the Solution
    D. Coding the Problem

**Answer**  : Option B

> Q7. The  correctness  and  appropriateness  of  ___________ solution  can  be  checked  very easily.

    A. Algorithmic solution 
    B. heuristic solution
    C. random solution
    D. Brute force Solution

**Answer  :** Option A

> Q8. Two main measures for the efficiency of an algorithm are

    A. Processor and memory 
    B. Complexity and capacity
    C. Time and space
    D. Data and space

**Answer  :** Option C

> Q9. Which of the following sorting algorithms provide the best time complexity in the worst-case scenario

    A. Merge Sort
    B. Quick Sort
    C. Bubble Sort
    D. Selection sort

**Answer  :** Option A

> Q10. Partition and exchange sort is____________  

    A. Quick sort
    B. Tree sort
    C. Heap sort
    D. Bubble

**Answer  :** Option A

> Q11. Which of the following sorting algorithm is of divide and conquer type

    A. Quick sort
    B. Insertion sort
    C. Merge sort
    D. Bubble

**Answer  :** Option C

> Q12. The time complexity of a quick sort algorithm which makes use of median, found by an O(n) algorithm, as pivot element is

    A. O(n2)
    B. O(nlogn) 
    C. O(nloglogn) 
    D. O(n)

**Answer  :** Option B

> Q13. Which of the following algorithm design technique is used in the quick sort algorithm

    A. Dynamic programming
    B. Backtracking 
    C. Divide-and-conquer
    D. Greedy method

**Answer  :** Option C

> Q14. Which of the following is not a stable sorting algorithm

    A. Quick sort
    B. Insertion sort
    C. Merge sort
    D. Bubble

**Answer  :** Option A

> Q15. Master’s theorem is used for

    A. Solving recurrences
    B. Solving iterative relations
    C. Analyzing loops
    D. Calculating the time complexity of any code 

**Answer  :** Option A

> 16. Prim’s algorithm starts constructing a minimum spanning tree from ___

    A. An arbitary root vertex
    B. The shortest arc
    C. The left most vertex
    D. The right most vertex
    
**Answer  :** Option A

> 17. Which method of encoding does not consider the probability of occurrence of symbols?

    A. Static Huffman coding
    B. Variable length coding
    C. Adaptive Huffman coding
    D. Fixed length coding
    
**Answer  :** Option D

> 18. In distribution counting to sorting elements in an array ___ is used.
   
    A. Accumulated sum of frequencies
    B. Frequency
    C. Count of repeating elements in the array
    D. The length of the array
    
**Answer  :** Option A

> 19. Dijkstra’s algorithm is used to solve which problems
    
    A. Network Lock
    B. Single source shortest Path
    C. All pair shortest path
    D. Sorting
    
**Answer  :** Option B

> 20. The basic operation of the ___ algorithm is the comparison between the element and the array given.
   
    A. Binary search
    B. Greedy
    C. Brute force
    D. Insertion sort
    
**Answer  :** Option D

> 21. What is the result of the recurrences which fall under first case of Master’s theorem (let the recurrence be given by T(n)=aT(n/b)+f(n) and f(n)=nc?
   
    A. T(n) = O(n^logba)
    B. T(n) = O(nc log n)
    C. T(n) = O(f(n))
    D. T(n) = O(n2)
    
**Answer  :** Option A

> 22. The rate at which storage memory or time grows as a function of the input size is called
   
    A. Storage
    B. Complexity
    C. Efficiency
    D. Load
    
**Answer  :** Option C

> 23. Internal and External factors of Algorithm Complexity are 

    A. Processor Quality
    B. Space Complexity
    C. Time Complexity
    D. All of the above
    
**Answer  :** Option D

> 24. Which method is practical to perform a single search in an unsorted list of elements?

    A. Sequential search
    B. Bubble sort
    C. Horspool’s method of string matching
    D. Brute force method of string matching
    
**Answer  :** Option A

> 25. Which algorithm finds the solution for the single-source shortest path problem for a tree?

    A. Prim’s
    B. Dijkstra’s
    C. Kruskal’s
    D. Huffman code
    
**Answer  :** Option B


## Unit I && II  CIE Questions and Answers

>   A freelancer has the choice of completing/partially completing tasks to maximize his profits. For partial completion of jobs, partial profit can be obtained.           Example for a job with (time-in-hours, profit) =(3,90), if 1/3rd is completed, then 30 profit is received; and likewise, if 1/6th is done then 15 is the profit         received
    He has a constraint of 100 hours and choice of 5 jobs. The 5 jobs -
    J1,J2,J3,J4,J5 have the following (time-in-hours, profit) respectively -((20,5), (30,20), (66, 30), (40,40), (60,50). 
    
    What is the maximum profit he can get in the given time constraint ?

    A. 152
    B. 156
    C. 162
    D. 216
    
**Answer  :** Option C

>  Given the recurrence relation of an algorithm is T(n)=8T(n/2) +n3, what is it's time 
   complexity as per master's theorem 

    A. θ(n^3) 
    B. O O(n^4 logn) 
    C. θ(n^2 logn)
    D. θ(n^3 logn)
    
**Answer  :** Option D

>  The time complexity of an algorithm is given as T(n)=3n+2. Select all correct statements related to the algorithm. 

    A. Space complexity is O(n) 
    B. Time complexity is Omega(n)
    C. It is a sublinear algorithm
    D. Algorithm has non polynomial time complexity
    
**Answer  :** Option B && D 

>  Select correct statements regarding multi-stage graph problem

    A. It can be solved faster with a greedy strategy, like Dijkstra. 
    B. It requires solution of optimal subpaths of vertices (in stages nearer to destination) to destination, in forward approach 
    C. It requires solution of optimal subpaths of vertices (in stages nearer to destination) to destination, in backward approach
    D. The backwàrd approach uses, optimal subpaths from start vertex. 
    
**Answer  :** Option A

> For the problem of job sequencing with deadlines, where each job requires 1 unit time to complete, on the single available machine, select all the feasible solution   sequence/sequences for the 5 jobs - J1,J2,J3,J4,J5 where their respective (profits, deadlines) are in following tuples (12,3), (15,2), (9,1), (18,2), (7,3). 

    A. J1,J2,J3 
    B. J5,J4,J1 
    C. J2,J4,J5
    D. None of Above
    
**Answer  :** Option B

> Which statements are correct related to Greedy strategy

    A. The greedy algorithm guarantees optimal solution to a given maximization / minimization criterion function 
    B. Greedy algorithm always makes the choice (greedy criteria) that looks best at the moment, to optimize a given objective function. 
    C. Greedy Knapsack problem (fractional knapsack) will generally give a better profits as compared to dynanic 0/1 Knapsack 
    D. Greedy strategy generates a single feasible and single optimal solution
    E. Time complexity of Greedy strategy, as per its control abstraction, is O(n)
    
**Answer  :**  B,C,D,E

> Select all correct options related to Quicksort and Mergesort. 

    A. Mergesort çan have a worst-case time complexity of O(n^2) when the merging is poorly done 
    B. Other than the requirement of storing n elements, Quicksort has a space complexity of O(log n) due to the recursive call stack 
    C. Quicksort is better in terms of worst-case sorting performance and may be a better choice for scenarios where memory usage is nota concern
    D. In terms of time complexity, both Quicksort and Mergesort algorithms have the same average case time complexity of O(nlogn)
    E. Other than the requirement of storing n elements, Mergesort has a space complexity of O(n) due to the need to create temporary arrays to merge subarrays.
    
**Answer  :** B,C,E 

> Given the recurrence relation of an algorithm is T(n)=8T(n/2)+n, what is it's time complexity as per master's theorem? 

    A. θ(n^3)
    B. O(n^2)
    C. θ(n^2 logn)
    D. θ(n^2 log^2(n))
    
**Answer  :** Option A

> For the problem of job sequencing with deadlines, where each job requires 1 unit time to complete, on the single available machine, select the optimal solution sequence for the 5 jobs -J1,J2,J3,J4,J5 where their respective (profits, deadlines) are given in following tuples ((12,3), (15,2), (9,1), (18,2), (7,3).

    A. J1,J2,J3
    B. J3,J2,J1
    C. J5,J4,J1
    D. J4,J2,J1
    
**Answer  :** Option D

> For 0/1 knapsack problem solved usng dynamic progranmng, to lraceback the solution from the avalable, filled, 2 D, Kn xm] table of optinmal sub solutions, what needs   to be done? Select all correct answers. 

    A. Start fronn last cell, ie. extreme bottom right cell ie. K[n,m]
    B. Start from the first, i.e. extreme left uppermost cell i.e. K|1,1]
    C. If K[i,j]=K[i-1,j] then this means that ith object=0 (is not selected)
    D. If K[i,j]!=K[i-1,j] , then this means that ith object=l (is selected)
    
**Answer  :** A,C,D

> What is true regarding the general divide and conquer strategy? Select all correct options.

    A. Its control abstraction -first, divides the problem into subproblems, and then combines the solution and next applies the strategy to the subproblems 
    B. For n>1, its time complexity generally is -> aT(n/b)+f(n), where f(n) is the time to divide the problem into subproblems 
    C. The solution to the small(P) situation is generally T(1) 
    D. It is naturally expressed as a recursive algorithm
    
**Answer  :** A,B,D 

> Which options have the correct sequences of decreasing time complexities?

    A. O(n^2 n^n),O(n^3 2^n),O(2^n),O(n!)
    B. O(n*n!),O(n*2^n),O(2^n),O(n^7)
    C. O(2^n),O(n),O(log n),O(1)
    D. O(n^4),O(n^3),O(n^2 2^n),O(n^n)

    
**Answer  :** Option C

> When constructing OBST for the following instance, n = 4, and, for nodes (n1, n2, n3, n4) the p and q values are (p1, p2, p3, p4) = (12, 16, 13, 7), (q0, q1,42, q3, q4) =(17, 14, 15, 12, 19), what is the cost of the subproblem c(1,2) and root r(3,4), if c(0,4) is the cost of OBST, and r(0,4) is its root node?
    
    A. c(1,2)=48 and r(3,4) =n3
    B. c(1,2)=45 and r(3,4)=n3 
    C. c(1.2)=43 and r(3,4)=n4
    D. c(1.2)=45 and r(3,4)=n4
    
**Answer  :** Option A

> What is correct asymptotically?
    
    A. If a function is O(n) it is also O(n^2), and O(n^3)
    B. Ifa function is O(n^3) it is also O(n)
    C. If a function is Ω (n^2) it is also Ω(n) and Ω(1) 
    D. o(n^2) = 2n^2 +8
    E. If a function is Ω(n^2) and also O(n^2), it is also θ(n^2)
    
**Answer  :** A,C,D,E 

## Unit 2

> Q1. Greedy Algorithms have following characteristic.

    A. Objective function
    B. Feasible solution
    C. Selection function
    D. All of these

**Answer  :** Option D

> Q2. Branch & Bound Technique uses

    A. Lower Bound
    B. Upper Bound
    C. Both Lower Bound & Upper Bound
    D. None of these

**Answer  :** Option C

> Q3. Longest Common Subsequence Problem can be solved by

    A. Greedy Method
    B. Divide & Conquer
    C. Dynamic Programming
    D. None of these

**Answer  :** Option C

> Q4. Divide and Conquer is a general design paradigm does not consist the following part

    A. Divide
    B. Recursion
    C. Iteration
    D. Conquer

**Answer  :** Option C

> Q5. The Knapsack problem where the objective function is to minimize the profit is

    A. Greedy
    B. Dynamic 0 / 1
    C. Back tracking 
    D. Branch & Bound 0/1

**Answer  :** Option D

> Q6. The worst case time complexity of the nondeterministic dynamic knapsack algorithm is

    A. O(n log n)
    B. O( log n)
    C. O(n2) 
    D. O(n) 

**Answer  :** Option D

> Q7. Which of the following standard algorithms is not a Greedy algorithm

    A. Dijkstra's shortest path algorithm
    B. Prim's algorithm
    C. Kruskal algorithm
    D. Huffman Coding
    E. Bellmen Ford Shortest path algorithm

**Answer  :** Option E

> Q8. From the following algorithm design techniques which one is used to find all the pairs of shortest distances in a graph

    A. Backtracking
    B. Greedy
    C. Dynamic programming
    D. Divide and Conquer

**Answer  :** Option C

> Q9. Kruskal’s algorithm uses-------- and prim’s algorithm uses------ in determining the MST

    A. edges,vertex 
    B. vertex,edges 
    C. edges,edges 
    D. vertex,vertex

**Answer  :** Option A

> Q10. The Knapsack problem is an example of 

    A. Greedy algorithm
    B. 2D dynamic programming
    C. 1D dynamic programming
    D. Divide and conquer

**Answer  :** Option B

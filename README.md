# Unit III – Assignment  

Name: Aakanksha  
Enrollment no: 03313302723

## SECTION A – Short Theory [15 Marks]

1) DP essentials  
- List the three ingredients of DP and one-line purpose of each. 
  
   Ans:  - Optimal Substructure: Optimal solution is built from optimal solutions of subproblems.  
         - Overlapping Subproblems: Same subproblems repeat; solve once and reuse.  
         - State & Transition: Define DP state and recurrence to compute and store results efficiently.  

---
2) DP vs D&C  
- State two differences focusing on subproblem overlap and reuse; give one example for each. 

    Ans: DP: Overlapping subproblems and results reused using memoization/tabulation.  
             Example: Fibonacci using DP.  
        - Divide & Conquer:Subproblems independent; recomputation occurs.  
             Example: Merge Sort.  

---
3) Principle of optimality  
- Define it in one sentence and name any one problem satisfying it.
Ans- Definition: If an optimal solution contains optimal solutions to its subproblems, the problem follows the principle of optimality.  
- Example: Matrix Chain Multiplication.  

---

 4. Memoization  
Define memoization and contrast with tabulation in one line each.

Ans- Memoization:Top-down approach storing results of solved subproblems to avoid recomputation.  
- Tabulation: Bottom-up approach computing all subproblems iteratively in a table.  

---

5. Branch and Bound Idea  
Define BnB and the role of bounding in pruning in two lines.

Ans- Definition: A state-space search method that generates branches of partial solutions while tracking bounds of optimal value.  
- Bounding: Bound estimates the best achievable value from a node; weak nodes are pruned to reduce search.  

---

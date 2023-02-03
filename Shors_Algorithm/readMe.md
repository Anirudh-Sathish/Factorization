# Prime Factorisation using Shors Algorithm 

_Side Notes_
- Shors algorithm is considered to be one of the most impressive quantum algorithms , along with grovers algorithm for quantum search 
_How it works_
Shors Algo:
1. Quantum Fourier Transform 
2. Modular Arthimetic (Classical Part)
3. Quantum Parallelism 

Problem : 
Given an odd composite number N , find an integer d strictly between 1 and N , that divides N

Shor's Algorithm consists of two parts : 
1. Converting the problem of factoring to a problem of finding periods (Classical Implementation )
2. Finding period using Quantum Fourier Transform (Quantum Computational Speed Up)

Insights on the Part1:
- Input: Non Prime Number N 
- Output : Non trivial Factor of N 

_Non trivial , since 1 is always a factor of n_


Shor's ALgorithm consists of five steps , with only step2 requiring the use of quantum computers 

### Step1:
Chose a random integer m , such that m < N , and they are co prime 

### Step 2 
Use a quantum computer to determine the unknown period P of the function 
```
f<sub>m,n</sub>(X) = m<sup>x</sup>mod N
```



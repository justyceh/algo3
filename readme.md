### Github repo for lecture 3 of algorithms


### Asymptotic notations
- A way to describe behavior of functions in the limit
   - How we indicate run times of algorithms
   - Describe the running time of an algorithm as n grows to infinity


- Big o notation is asymptotic less than or f(n) is less than g(n)
- Big Omega notation is asymptotic greater than or f(n) is greater than g(n)
- Big theta notation is asymptotic equality or f(n) is equal to g(n)

### Omega notation

- Omega(g(n)) = {f(n): there exist positive constants c and n0 such that rate of growth of cg(n) is less than or equal to f(n) for all n where n is greater than or equal to n0 }

- Intuitvely Omega(g(n)) is the set of functions with a larger or same order of growth as g(n)


### Mathematical Induction

- We find c, and n0 to prove either omega, theta, or big o notation
- We are proving in terms of what grows the fastest or the slowest which is sort of related to the algorithm run times

### Proof by contradiction

- We can prove by contradiction, we assume the statement is true

- If we are given a statement f(n) != omega(g(n)) then it is essentially saying the rate of growth of g(n) is actually greater than f(n)


### Theta notation

- theta(g(n)) = {f(n) there exist positive constants c1, c2, and no such that 0 <= c1g(n) <= f(n) <= c2g(n) for all n >= n0}

- Intuitvely theta(g(n)) is equal to the set of functions with the same order of growth as g(n)


### More on asymptotic notations

- There is no unique set of values for n0 and c in proving the asymptotic bounds


### Comparisons of Functions

- Theorem: f(n) = theta(g(n)) <==> f = O(g(n)) and f = omega(g(n))

- Transitivity:
f(n) = theta(g(n)) and g(n) = theta(h(n)) so f(n) = theta(h(n))
Same goes for O and omega


- Reflexivity:
f(n) = theta(f(n))
Same for O and omega

- Symmetry:
f(n) = theta(g(n)) if and only if g(n) = theta(f(n))

- Transpose Symmetry:
f(n) = O(g(n)) if and only if g(n) = omega(f(n))


### Asymptotic notations in equations
- On the right hand side
theta(n^2) stands for some anonoymous function in theta(n^2)
Example:

2n^2 + 3n + 1 = 2n^2 + theta(n) means:
There exist a function f(n) belong to theta(n) such that 2n^2 + 3n + 1 = 2n^2 + f(n)


- On the left hand side

2n^2 + theta(n) = theta(n^2)

- No matter how the anonymous function is choosen on the left hand side, there is a way to choose the anonymous function on the right hand side to make the equation valid



### Simple summation formulas we will use

- Arithmetic series

- Geometric series
    - Special case: x < 1

Harmonic series

- Other important formulas


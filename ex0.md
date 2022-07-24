# Exercises - Set 0

[Exercises - Set 0](#exercises)
  - [Ex.1](#ex1)
  - [Ex.2](#ex2)
  - [Ex.3](#ex3)
  - [Ex.4](#ex4)
  - [Ex.5](#ex5)
  - [Ex.6](#ex6)
  - [Ex.7](#ex7)
  - [Ex.8](#ex8)
  - [Ex.9](#ex9)
  - [Ex.10](#ex10)
  - [Ex.11](#ex11)
  - [Ex.12](#ex12)
  - [Ex.13](#ex13)
  - [Ex.14](#ex14)

## Ex.1

- a) Natural Odd numbers
- b) Whole Even numbers
- c) Natural Even numbers
- d) Natural Multiples of 6
- e) Binary Palindromes
- f) The Empty Set

## Ex.2

- a) {1, 10, 100}
- b) {6, 7, 8, ...}
- c) {0 .. 4}
- d) {aba}
- e) {""}
- f) {}

## Ex.3

$A =$ {x, y, z},
$B =$ {x, y}

- a) $False$, because: $ z \in A, z \notin B $.
- b) $True$, bacause: $ \forall e \in B, e \in A $.
- c) $ A \cup B = A $.
- d) $ A \cap B = B $.
- e) $ A \times B =$ {(x, x), (x, y), (y, x), (y, y), (z, x), (z, y)}.
- f) $PowerSet(B) =$ {{}, {x}, {y}, {x, y}}.

## Ex.4

$|A| = |B| = b$
$|A \times B| = ?$

$(*)$ Tuples starting with the ith element of A $=$ b.
$(**)$ b number of these types of tuples.

$(*), (**) \rArr |A \times B| = b^{2}$

## Ex.5

$|C| = c$
$|PowerSet(C)| = ?$

- Base cases:
Number of sets with cardinal 0 = 1 (the empty set)
Number of sets with cardinal 1 = c (elements of C)
- Inductive step:
$P(n) \rArr P(n+1)$
Suppose $P(n)$ is $True$.
$S_{n} =$ {$a_{1}$, $a_{2}$, ..., $a_{n}$}
$S_{n+1} = $ { $a_{n+1} $ } $ \cup S(n)$
$(*)P(n): |S_{n}| = 2^{n}$
$(**)S_{n+1}$ has $2^{n}$ subsets containing $a_{n+1}$
$(*), (**) \rArr |S_{n+1}| = 2^{n} \times 2^{n} \rArr P(n+1)$ is $True$ $\rArr |PowerSet(C)| = 2^{|C|}$ qed.

## Ex.6

- a) $f(2) = 7$
- b) $f :$ {1,2,3,4,5,6} $\rArr$ {6,7}
- c) $g(2,10) = 6$
- d) $g:$ {1,2,3,4,5} $\times$ {6,7,8,9,10} $\rArr$ {6,7,8,9,10}
- e) $f(4) = 7\rArr g(4,7) = 8$

## Ex.7

- a) Reflexive, symmetrix but not transitive:
$R1=${$(1,1),(1,2),(2,1),(2,2),(2,3),(3,3)$}
- b) Reflexive, transitive but not symmettrix:
$R2=${$(1,1),(2,2),(3,3),(4,4),(1,2),(2,3),(1,3)$}
- c) Symmetric, transitive but not reflexive:
$R3=${$(1,2),(2,1),(1,1)$}

## Ex.8

$Degree(1) = 3$
$Degree(3) = 2$
$Path(3,5)= 3 \rArr 1 \rArr 2 \rArr 4$

## Ex.9

The graph is formed by two sides: {1,2,3} and {4,5,6}.
For every node in one side:

- It is not connected to any node from its own side.
- It is connected to all nodes from the other side.

## Ex.10

The error lies in the division by $(a - b)$.
$a = b \rArr a - b = 0$ so division by 0 is undefined behavior, which means the proof is incorrect.

## Ex.11

Adding another more general base case will disprove this.

## Ex.12

## Ex.13

## Ex.14

# dismathportfolio-MParro
dismathportfolio of Manuel Lorenzo Parro created by Classroom for GitHub

## Week 1
- I was introduced to a new and interesting course called **Discrete Mathematics** (DISMATH)
- Our professor (Sir Melvin Cabatuan) told us that our project will be a mobile application which makes the course more interesting.
- I was introduced to logic and proofs and learned that **proposition** is a statement that is either true (1) or false (0) and there is NO in between!
- I've learned the logical connectives which are shown in the table below:

| Logical Symbol  |  Logical Operator     | Shorthand | Formula                                       | Logical Expression             |
| :-------------: |:---------------------:|:---------:|:---------------------------------------------:|:-----------------------------:|
| ¬               | Negation              | not       | val(¬p) = 1 - val(p)                          | ¬p                           |
| ∧               | Conjunction           | and       | val(p ∧ q) = min(val(p), val(q))              | p ∧ q                          
| v               | Disjunction           | or        | val(p v q) = max(val(p), val(q))              | p v q                        |
| ⊕              | Exclusive disjunction | xor       | if val(p)  not equal val(q) = 1 , otherwise  0|  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |
| →               | Conditional           | if, then  | if val(p)  ≤ val(q) = 1 , otherwise  0        | p → q ≡  ¬p v q              |
| ↔               | Biconditional         | iff       | if val(p) equals val(q) = 1 , otherwise  0    |  p ↔ q ≡ (p → q) ∧ (q → p)    |

- I've also learned how to use these logical connectives in truth tables.


## Week 2
- I've learned about the laws and rules in DISMATH called **Logical Equivalences** which is shown in the table below:

|         Name        |                           Equivalence                                 |
|:-------------------:|:--------------------------------------------------------------------: |
|    Identity laws    |                      p ∧ T ≡ p <br> p v F ≡ p                         |
|   Domination laws   |                       p v T ≡ T <br> p ∧ F ≡ F                        |
|   Idempotent laws   |                       p v p ≡ p <br> p ∧ p ≡ p                        |
| Double negation law |                            ¬(¬p) ≡ p                                  |
|   Commutative laws  |                   p v q ≡ q v p <br> p ∧ q ≡ q ∧ p                    |
|   Associative laws  |       (p v q) v r ≡ p v (q v r) <br> (p ∧ q) ∧ r ≡ p ∧ (q ∧ r)        |
|  Distributive laws  | p v (q ∧ r) ≡ (p v q) ∧ (p v r) <br>  p ∧(q v r) ≡ (p ∧ q) v (p ∧ r)  |
|   De Morgan's laws  |              ¬(p ∧ q) ≡ ¬p v ¬q <br> ¬(p v q) ≡ ¬p ∧ ¬q               |
|   Absorption laws   |                 p v (p ∧ q) ≡ p <br> p ∧ (p v q) ≡ p                  |
|    Negation laws    |                     p v ¬p ≡ T <br> p ∧ ¬p ≡ F                        |

- I've also learned **Propositional logic** which deals with propositions as a whole (subject + predicate)
- I've also learned about **Quantifiers** which indicates the generality of an open sentence in which a variable occurs. 
- Quantifiers have two classifications:
  - Existential Quantifiers (∃x)
    - "There exist"
  - Universal Quantifiers (∀x)
    - "For all"

## Week 3
- This week I was introduced to a new topic called the **Rules of Inference**. 
- There are different forms of Rules of Inference which are shown below:

|          Name          |   Rule of Inference       |            Tautology           |
|:---------------------: |:-------------------------:|:-----------------------------:|
|      Modus ponens      |       p<br>p→q<br>∴q      |        (p ∧ (p → q)) → q       |
|      Modus tollens     |     ¬q<br>p→q<br>∴ ¬p     |       (¬q ∧ (p → q)) → ¬p      |
| Hypothetical syllogism |     p→q<br>q→r<br>∴p→r    |  ((p → q) ∧ (q → r)) → (p → r) |
|  Disjunctive syllogism |      p∨q<br>¬p<br>∴q      |       ((p ∨ q) ∧ ¬p) → q       |
|        Addition        |       p<br>∴p ∨ q         |           p → (p ∨ q)          |
|      Simplication      |       p ∧ q<br>∴p         |           (p ∧ q) → p          |
|       Conjunction      |      p<br>q<br>∴p ∧ q     |      ((p) ∧ (q)) → (p ∧ q)     |
|       Resolution       | p ∨ q<br>¬p ∨ r<br>∴q ∨ r | ((p ∨ q) ∧ (¬p ∨ r)) → (q ∨ r) |

- I learned how to identify arguments based on what Rule of Inference was used. 
- We used Rules of Inference in showing the premises of our homework "*Superman doesn't exist!*"
- I've also learned about Methods of Proof. 
- The first method we discussed is about **Direct Proof**.
  - P → Q
  - In this method of proof, we first assume that P is true then show that Q must also be true.

## Week 4
- We discussed about the **Contraposition** (Indirect proof).
  - ¬Q → ¬P
  - In this method of proof, we first assume ¬Q is true then show ¬P is also true.
- Vacuous Proof
  - ¬P → (P → Q)
  - In this method of proof, we show that P is false, because P → Q must be true when p is false.
- Trivial Proof
  - Q → (P → Q)
  - We show that Q is true, it follows that P → Q must also be true
- Proof by Contradiction
  - In this proof, first we assume that the premise is not true, then show that the premise will end up in a contradiction
- I have also learned the definition of a rational number = {a/b | a, b ∈ ℤ, where b≠0, a & b does no have common factor other than ±1}

## Week 5
- We discussed about **Proof by Equivalence** (Biconditionals)
  - (P ↔ Q) ↔ [(P → Q) ∧ (Q → P)]
  - In this proof, we should show that P → Q and Q → P are both true
- We also discussed about **Mathematical Induction**
  1. Basis:
    - Show that P(1) or P(0) to be true
  2. Direct Proof
    1. Asumme P(k) = T
    2. Show P(k+1) = T

## Week 6
- I learned about **Recursive/Inductive Definition**
  - Basis step: using 0 as a value in the function
  - Recursive step: giving definition to the function
- I learned about **Recursive Algorithms**
- I've also learned about **Program Verification**
  - We first show that correct answer is obtained if the program terminates
  - Then we show that the program always terminates
- If the program terminates then it is **Partial Correctness** wherein two propositions are used
  - Initial assertion (p) - properties of the input values
  - Final assertion (q) - output 
- I've also learned about the Hoare triple: p{S}q where S is the program segment

## Week 7
- We first discussed about our Project 0.0 where we will use MIT App Inventor as the platform
  - Due: March 02, 2016 
  - Title: DISMATH_Project0.0
  - Individual
- We were introduced to a new topic called **Set Theory**
  - *Set* is an unordered collection of distinct objects
  - We used '{}' to denote set
- I've learned that ∅ ≠ {∅}
  - ∅ means it is an empty set while {∅} means that it is a set cointaining empty set
- I've learned about Union (A U B), Intersection (A ∩ B), and Difference (A-B or A\B)
- We discussed about **Set Identities** which are very similar to Logical Equivalences
- We also discussed about **Subsets** 
  - Ex. {1,2,3} ⊆ { 1, 2, 3, 4}
- We also discussed Power sets 
  - ℘(S) = {T| T ⊆ S }
- Lastly, we discussed about **Cardinality**
  - it is the number of elements in a set
  - If S is a set, we denote its cardinality by writing |S|
    - Ex. <br> |{a, b, c, d, e}| = 5 <br> |{{a, b}, {c, d, e, f, g}, {h}}| = 3 <br> |{1, 2, 3, 3, 3, 3, 3}| = 3 <br> |{ n ∈ ℕ | n < 137}| = 137
  - The Cardinality of ℕ
    - since |ℕ| is infinitely large we define |ℕ| = ℵ₀
    - ℵ₀ is pronounced “aleph-zero,” “alephnought,” or “aleph-null
  
## Week 8
- We discussed Functions and its types
  - One - to - one Function (Injection) 
  - Onto Function (Surjective) 
  - One - to - one Correspondence (Bijection) 
- We discussed about Algorithms.
- **Algorithm** is defined as a finite set of precise instructions for performing a computation or for solving a problem
- Properties of Algorithm:
  - Input 
  - Output
  - Definiteness
  - Correctness
  - Finiteness
  - Generality
- Pseudocode
  - Preconditions - statements that describe valid input
  - Postconditions - conditions that the ouput should satisfy when the program has run

## Week 9 
- We discussed about the types of Algorithm
  - Searching Algorithms
  - Sorting Algorithms
  - Greedy Algorithms

## Week 10
- We discussed about the Growth of Functions.
- Big-O Notation
- Big-Omega and Big-Theta Notation
- Algorithm Time Complexity
- Division and Modulo Operator
  - Q = a div d
  - r = a mod d
- Cryptology (Caesar Cipher)

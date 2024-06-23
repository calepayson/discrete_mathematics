# Propositional Equivalences

Propositional equivalences allow us to replace one statement with another that shares the same truth value.

A **tautology** is a compound proposition that is always true no matter the truth values of the variables within it.
- a or !a

A **contradiction** is a compound proposition that is always false no matter the truth values of the variables within it.
- a and !a

A **contingency** is a compound proposition that is neither a tautology or a contradiction.
- a

## Logical equivalences

Compound propositions that have the same truth values in all possible cases are **logically equivalent**.
- p <-> q == p ≡ q == p and q are equal in every case.

Logical equivalences:
- **Identity laws**
    - p and true == p
    - p or false == p
- **Domination laws**:
    - p or true == true
    - p and false == false
- **Idempotent laws**:
    - p or p == p
    - p and p == p
- **Double negation laws**:
    - !!p == p
- **Comutative laws**:
    - p or q == q or p
    - p and q == q and p
- **Associative laws**:
    - (p or q) or r == p or (q or r)
    - (p and q) and r == p and (q and r)
- **Distributive laws**:
    - p or (q and r) == (p or q) and (p or r)
    - p and (q or r) == (p and q) or (p and r)
- **De Morgan's laws**:
    - !(p and q) == !p or !q
    - !(p or q) == !p and !q
- **Absorption laws**:
    - p or (p and q) == p
    - p and (p or q) == p
- **Negation laws**:
    - p or !p == true
    - p and !p == false

Logical equivalences involving conditional statements
- p -> q == !p or q
- p -> q == !q -> !p
- p or q == !p -> q
- p and q == !(p -> !q)
- !(p -> q) == p and !q
- (p -> q) and (p -> r) == p -> (q and r)
- (p -> r) and (q -> r) == (p or q) -> r
- (p -> q) or (p -> r) == p -> (q or r)
- (p -> r) or (q -> r) == (p and q) -> r

Logical equivalences involving biconditional statements
- p <-> q == (p -> q) and (q -> p)
- p <-> q == !p <-> !q
- p <-> q == (p and q) or (!p and !q)
- !(p <-> q) == p <-> !q

## De Morgan's law

De Morgan's law is particularly important as (it seems) negating conjuctions and disjunctions is a frequent task.

## Constructing new logical equivalences

Using the established logical equivalences above you can prove new equivalences to help simplify expressions.

## Satisfiablility

A compound proposition is **satisfiable** if there is an assignment of truth values to its variables that makes it true.

A compound proposition is **unsatisfiable** if there is no assignment of truth values to its variables that makes it true.

## Applications of satisfiability

Real-world problems can be simplified by modeling them in terms of satisfiability.

## Solving Satisfiability Problems

Satisfiability problems are incredibly complex when involving more than a few variables. Some computer programs are able to solve complex satisfiability problems of specific classes (like sudoku).

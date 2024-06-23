# Predicates and Quantifiers

## Predicates

In the statement "x is greater than 3":
- The **subject** is x.
- The **predicate** is "is greater than 3".
- The statement is a **propositional function** and can be denoted as P(x).
- The truth value of P(x) can be evaluated for each/any value of x.

**Preconditions** describe valid input.
**Postconditions** are conditions the program should satisfy after running.
- (x > 3) -> (x := 1)
- The precondition is (x > 3)
- The postcondition is (x := 1)

## Quantifiers

**Quantifiers** describe a range of values. The area of logic that deals with predicates and quantifiers is called the **predicate calculus**.

**The universal quantifier** specifies all values of a variable.
- ∀xP(x) == P(x) is true for every value of x.

**The existential quantifier** specifies one or more values of a variable.
- ∃xP(x) == P(x) is true for one or more values of x.

**The uniquencess quantifier** specifies only one value of a variable.
- ∃!xP(x) == P(x) is true for only one value of x.

## Quantifiers over finite domains

When the domain of a quantifier is finite, quantifiers can be expressed with propositional logic.
- ∀xP(x) == P(x1) and P(x2) and ... and P(xn)
- ∃xP(x) == P(x1) or P(x2) or ... or P(xn)

**Think of quantifiers as a loop**!

## Quantifiers with restricted domains

Propositions can be used to restrict the domain of quantifiers:
- ∀x(x > 0) == for every positive value of x.

## Precedence of quantifiers

Quantifiers have higher precedence than all logical operators.

## Binding Variables

A variable is **bound** when a quantifier is used on it.

A variable is **free** if it is not bound by a quantifier or set to a particular value.

## Logical equivalences involving quantifiers

Statements are **logically equivalent** if and only if they have the same truth value no matter which predicates are substituted into these statements and which domain of discourse is used for the variables in these propositional functions.

## Negating quantified expressions

**Demorgan's laws for quantifiers**:
- !∀xP(x) == ∃x!P(x)
- !∃xP(x) == ∀x!P(x)

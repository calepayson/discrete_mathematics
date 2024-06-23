# Nested Quantifiers

Nested quantifiers are where one quantifier is in the scope of another.

## Understanding Statements Involving nested Quantifiers

View each quantifier as the initilization of a nested loop:

'''
for every value x:
    for one or more values y:
        x + y = 0
'''

## The Order of Quantifiers

If there is a mix of universal and existential quantifiers then order matters.

## Exercises

1.
- a - For every value x there is a value y where x is less than y.
- b - For every value x and every value y, if x and y are greater than or equal to zero then x times y is greater than or equal to zero.
- c - For every value x and every value y there is a value z where x times y is equal to z.

3. 
- a - There is a student in my class that has sent an email to another student in my class.
- b - There is a student in my class that has sent an email to every student in my class.
- c - Every student in my class has sent an email to at least one student in my class.
- d - There is a student in my class that has recieved an email from every student in my class.
- e - Every student in my class has recieved an email from some student in my class.
- f - Every student in my class has recieved an email from every student in my class.

5.
- a - Sarah Smith has visited www.att.com.
- b - A student has visited www.imdb.org.
- c - Jose Orez has visited a website.
- d - Ashok Puri and Cindy Yoon have visited the same website.
- e - If David Belcher has visited a website then another student has visited that website.
- f - There are two different students who have visited all of the same websites.

7.
- a - Abdallah Hussein does not like Japanese cuisine
- b - Some student like Korean cuisine and every student likes Mexican cuisine
- c - There is some cuisine that either Monique Arsenault or Jay Johnson likes
- d - For every pair of students there is some cuisine that one or both of them does not like
- e - Some pair of students has the same taste for every cuisine
- f - Every pair of students likes some of the same cuisine

9.
- a - ∀xL(x, Jerry)
- b - ∀x∃yL(x, y)
- c - ∃y∀xL(x, y)
- d - !∃x∀yL(x, y)
- e - ∃x!L(Lydia, x)
- f - ∃y!∃xL(x, y)
- g - ∃!y∀xL(x, y)
- h - ∃!x∃!y((x != y) and L(x, y))
- i - ∀xL(x, x)
- j - ∃x∀y((x != y) and !L(x, y))

11.
- a - A(Lois, Professor Michaels)
- b - ∀x(S(x) -> A(x, Professor Gross))
- c - ∀x(F(x) -> (A(x, Professor Miller) or A(Professor Miller, x)))
- d - ∃x∀y((S(x) and F(y)) -> !A(x, y))
- e - ∃x∀y((S(y) and F(x)) -> !A(y, x))
- f - ∃x∀y((S(x) and F(y)) -> A(x, y))
- g - ∃x∀y((F(x) and F(y) and (x != y)) -> A(x, y))
- h - ∃x∀y((S(x) and F(y)) -> A(y, x)

13.
- a - !M(Chou, Koko)
- b - !M(Arlene, Sarah) or !T(Arlene, Sarah)
- c - !M(Deborah, Jose)
- d - ∀xM(x, Ken)
- e - ∀x!T(x, Nina)
- f - ∀x(M(x, Avi) or T(x, Avi))
- g - ∃x∀yM(x, y)
- h - ∃x∀y(M(x, y) or T(x, y))
- i - ∃x∃y((x != y) -> (M(x, y) and M(y, x)))
- j - ∃xM(x, x)
- k - ∃x∀y(!M(y, x) and !T(y, x))
- l - ∀x∃y((x != y) -> (M(y, x) or T(y, x)))
- m - ∃x∃y((x != y) -> (M(x, y) and T(y, x)))
- n - ∃x∃y∀z((x != y) -> (M(x, z) or T(x, z) or M(y, z) or T(y, z)))

19.
- a - ∀x∀y((x < 0) and (y < 0) -> (x + y < 0))
- b - ∀x∃y((x > 0) and (y > 0) -> (x - y <= 0)
- c - ∀x∀y((x * x + y * y) > ((x + y) * (x + y)))
- d - ∀x∀y(|x * y| = |x| * |y|)

21.
∀x∃y∃z∃a∃b((x > 0) -> ((y * y) + (z * z) + (a * a) + (b * b) = x))

23.
- a - ∀x∀y(((x < 0) and (y < 0)) -> (x * y > 0))
- b - ∀x(x - x = 0)
- c - ∀x∃y∃z(((x > 0) and (y != z)) -> ((y * y = x) and (z * z = x)))
- d - ∀x∀y((x < 0) -> !(y * y = x))

25.
- a - There is some value x where for every value y, x times y is equal to y
- b - The product of two negative numbers is greater than zero
- c - There is some value x and some value y where the square of x is greater than y and x is less than y
- d - Any two numbers produce some number when summed

27.
- a - true
- b - false
- c - true
- d - false
- e - true
- f - true
- g - false
- h - true
- i - true

29.
- a - P(1, 1) and P(1, 2) and ... and P(3, 3)
- b - P(1, 1) or P(1, 2) or ... or P(3, 3)
- c - (P(1, 1) and P(1, 2) and P(1, 3) or ... (and P(3, 3))
- d - (P(1, 1) or P(1, 2) or P(1, 3) and ... (or P(3, 3))



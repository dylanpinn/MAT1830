# Lecture 13: Functions

**Functions - why should you care?**

The concept of a function is extremely important in both computer science and
maths.

- Functions (subroutines) in programming are closely related to functions in the
  mathematical sense.
- In the case of functional programming languages (e.g. Lisp, Haskell, Rust)
  they are exactly functions in the mathematical sense.
- Functions are used to define a lot of important concepts in maths and
  theoretical computer science.

A function can be thought of as a "black box" which accepts inputs and, for each
input, produces a single output.

- Each input produces exactly one output. (Always the same output for a given
  input).
- Input = Domain
- Output = Codomain

**Remember:** The domain and codomain are part of the function and must always
be defined.

## 13.1 Defining functions via sets

Formally we represent a function $f$ as a set $X$ of possible inputs, a set $Y$
so that every output of $f$ is guaranteed to be in $Y$, and a set of (input,
output) pairs from $X \times Y$. The vital property of a function is that each
input gives exactly one output.

A function $f$ consists of a _domain_ $X$, a _codomain_ $Y$, and a set of
ordered pairs from $X \times Y$ which has exactly one ordered pair $(x,y)$ for
each $x \in X$.

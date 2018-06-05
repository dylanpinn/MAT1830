# Lecture 14: Examples of Functions

The functions discussed in the last lecture were familiar functions of real
numbers. Many other examples occur elsewhere, however.

## 14.1 Functions of several variables

We might define a function sum $: \mathbb{R} \times \mathbb{R} \rightarrow
\mathbb{R}$ by sum $(x,y) = x + y$.

Because the domain of this function is $\mathbb{R} \times \mathbb{R}$, the
inputs to this function are ordered pairs $(x,y)$ of real numbers. Because its
codomain in $\mathbb{R}$, we are guaranteed that each output will be a real
number. This function can be thought of as a function of two variables $x$ and
$y$.

Similarly we might define a function binomial $: \mathbb{R} \times \mathbb{R}
\times \mathbb{N} \rightarrow \mathbb{R}$ by binomial $(a,b,n) = (a+b)^n$.

Here the inputs are ordered triples $(x,y,n)$ such that $x$ and $y$ are real
numbers and $n$ is a natural number. We can think of this as a function of three
variables.

**Question** What are the ordered pairs which define the function sum $: \{1,2\}
\times \{1,2\} \rightarrow \mathbb{N}$ defined by sum $(x,y)=x+y$?

**Answer** We have sum $((1,1))=2$, sum$((1,2))=3$, sum$((2,1))=3$, and
sum$((2,2))=4$.

So $\{((1,1),2), ((1,2),3), ((2,1),3), ((2,2),4) \}$.

**Note** We often abbreviate $f((x,y))$ to $f(x,y)$ and so on when dealing with
multivariable functions.

**Question 14.1** Suggest domains and codomains for the following functions.

- gcd
  - domain: $\mathbb{Z} \times \mathbb{Z}$
  - codomain: $\mathbb{N}$
- reciprocal
  - domain: $\mathbb{R} - \{0\}$
  - codomain $\mathbb{R} - \{0\}$

**Question** Suggest a domain and codomain for $\cap$ (intersection) function
for sets of real numbers.

- **A** domain: $\mathbb{R} \times \mathbb{R}$, codomain: $\mathbb{R}$
- **B** domain: $\wp(\mathbb{R}) \times \wp(\mathbb{R})$, codomain:
  $\wp(\mathbb{R})$
- **C** domain: $\wp(\mathbb{R})$, codomain: $\wp(\mathbb{R})$
- **D** domain: $\mathbb{R} \times \mathbb{R}$, codomain: $\wp(\mathbb{R})$

**Example** Input: $(\{1,2,3,4\},\{2,3,\pi\})$ Output: $\{2,3\}$

**Answer** The function must output a *set* of real numbers. So the codomain
must be the set containing all sets of real numbers. $\mathbb{R}$ is the set of
real numbers, so $\wp(\mathbb{R})$ is the set of real numbers.

The function must accept a *pair* of *sets* of real numbers. So the domain must
be the set containing all pairs of real numbers. $\wp(\mathbb{R})$ is the set of
of all sets of real numbers, so $\wp(\mathbb{R}) \times \wp(\mathbb{R})$ is the
set of pairs of sets of real numbers. So **B**.

**Note** $\cup$ (union) would have the same domain and codomain.

## 14.2 Sequences

An infinite sequence of numbers, such as

$$1, \frac{1}{2}, \frac{1}{4}, \frac{1}{8}, \frac{1}{16}, \dots,$$

can be viewed as the function $f: \mathbb{N} \rightarrow \mathbb{R}$ defined by
$f(n) = 2^{-n}$. In this case, the inputs to $f$ are natural numbers, and its
outputs are real numbers.

Any infinite sequence $a_0, a_1, a_2, a_3, \dots$ can be viewed as a function
$g(n) = a_n$ from $\mathbb{N}$ to some set containing the values $a_n$.

**Question** For each of the following sequences, find a function $f$ such that
the sequence is $f(0), f(1), f(2), \dots$

$$1, \frac{1}{2}, \frac{1}{3}, \frac{1}{4} \frac{1}{5},\dots \Rightarrow f:
\mathbb{N} \rightarrow \mathbb{Q}, f(n) = \frac{1}{n+1}$$
$$5, 1, -3, -7, -11, -15, \dots \Rightarrow f: \mathbb{N} \rightarrow
\mathbb{Z}, f(n) = 5-4n$$
$$4, 12, 36, 108, 324, 972, \dots \Rightarrow f: \mathbb{N} \rightarrow
\mathbb{Z}, f(n) = 4(3^n)$$

## 14.3 Characteristic functions

A subset of $\mathbb{N} = {0,1,2,3,\dots\}$ can be represented by its
characteristic function. For example, the set of squares is represented by the
function $\chi: \mathbb{N} \rightarrow \{0,1\}$ defined by

$$
\chi A(a) =
     \begin{cases}
       1 &\text{ if } n \text{ is a square } \\
       0 &\text{ if } n \text{ is not a square } \\
     \end{cases}
$$

which has the following sequence of values

$$110010000100000010000000010000000000100\dots$$

(with 1s at the positions of the squares $0,1,4,9,16,25,36,\dots$).

Any property of natural numbers can be likewise be represented by a
characteristic function. For example, the function $\chi$ above represents the
property being a square.

Thus any set or property of natural numbers is represented by a function

$$\chi : \mathbb{N} \rightarrow \{0,1\}$$

Characteristic functions of two or more variables represent relations between
two or more objects. For example, the relation $x \leq y$ between real numbers
$x$ and $y$ has the characteristic function $\chi : \mathbb{R} \times \mathbb{R}
\rightarrow \{0,1\}$ defined by

$$
\chi A(a) =
     \begin{cases}
       1 &\text{ if } x \leq y \\
       0 &\text{ if } \text{ otherwise } \\
     \end{cases}
$$

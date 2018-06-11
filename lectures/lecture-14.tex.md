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

**Question 14.2** If $A$ and $B$ are subsets of $\mathbb{N}$ with characteristic
functions $\chi_A(n)$ and $\chi_B(n)$, then what set does the function
$\chi_A(n)\chi_B(n)$ represent?

**Answer**

If $n \in A$ and $n \in B$ then $\chi_A(n) \chi_B(n) = 1 \times 1 = 1$.

If $n \in A$ and $n \not \in B$ then $\chi_A(n) \chi_B(n) = 1 \times 0 = 0$

If $n \not \in A$ and $n \in B$ then $\chi_A(n) \chi_B(n) = 0 \times 1 = 0$

If $n \not \in A$ and $n \not \in B$ then $\chi_A(n) \chi_B(n) = 0 \times 0 = 0$

So $\chi_A(n) \chi_B(n)$ is the characteristic function of $A \cap B$.

**Question** Let $d$ be a positive integer. If $\chi_d: \mathbb{N} \rightarrow
\{0,1\}$ is a function defined by

$$
\chi A(a) =
     \begin{cases}
       1, &\text{ if } x \text{ divides } d \\
       0, &\text{ if } x \text{ does not divide } d \\
     \end{cases}
$$

then what is $1 \chi_d(1) + 2\chi_d(2) + 3\chi_d(3) + \dots + d\chi_d(d)$?

**Answer** The sum of positive divisor of $d$.

**Question** How many functions are there with domain $\{1,2,3,4\}$ and codomain
$\{-1,0,1\}$?

**Answer** The domain has 4 elements. (There are 4 possible inputs.) For each
input, we can decide if it's mapped to -1 or 0 or 1. We can do this in $3 \times
3 \times 3 \times 3 = 3^4 = 81$ ways.

**Question** How many functions are there with domain $X$ and codomain $Y$?

**Answer** The domain has $|X|$ elements. (there are $|X|$ possible inputs.) For
each input, we have $|Y|$ options for where it's mapped to. We can do this in
$|Y| \times |Y| \times \times \dots |Y| = |Y|^{|X|}$ ways.

## 14.4 Boolean functions

The connectives $\land, \lor$ and $\neg$ are functions of variables whose values
come form the set $\mathbb{B} = \{T,F\}$ of Boolean values (named after George
Boole).

$\neg$ is a function of one variable, so $\neg: \mathbb{B} \rightarrow
\mathbb{B}$ and it is completely defined by giving its values on **T** and
**F**, namely $\neg T = F$ and $\neg F = T$. This is what we did previously by
giving the truth table of $\neg$.

$\land$ and $\lor$ are functions of two variables, so $\land: \mathbb{B} \times
\mathbb{B} \rightarrow \mathbb{B}$ and $\lor : \mathbb{B} \times \mathbb{B}
\rightarrow \mathbb{B}$. They are completely defined by giving their values on
the pairs $\{T,T\}, \{T,F\}, \{F,T\}, \{F,F\}$ in $\mathbb{B} \times
\mathbb{B}$, which is what their truth tables do.

**Question:** Let $\mathbb{B} = \{0,1\}$. How many functions are there with
domain $\mathbb{B} \times \mathbb{B} \times \dots \times \mathbb{B}$ and
codomain $\mathbb{B}$?

- **A.** $n^2$
- **B.** $2^{(n^2)}$
- **C.** $2^n$
- **D.** $2^{(2^n)}$

**Answer:** The domain has $2^n$ elements. (There are $2^n$ possible inputs.)
For each input, we can decide if it's mapped to 0 or 1. We can do this in $2
\times 2 \times \dots \times \2 = 2^{(2^n)}$ ways.

So **D**.

**Example (Hamming distance)** Let $B_n$ be the set of all binary strings of
length $n$.

**Hamming distance** is a function $h:$ defined by $h$ equals the number of
places in which $s$ and $t$ disagree.

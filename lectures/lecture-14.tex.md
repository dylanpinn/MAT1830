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

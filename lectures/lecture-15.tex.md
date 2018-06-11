# Lecture 15: Composition and Inversion

Complicated functions are often built from single parts. For example, the
function $f: \mathbb{R} \rightarrow \mathbb{R}$ defined by $f(x) = (x^2 + 1)^3$
is computed by doing the following steps in succession:

* square
* add 1,
* cube.

We say that function $f(x) = (x^2 + 1)^3$ is the composite of the functions
(from $\mathbb{R}$ to $\mathbb{R}$)

- square $(x) = x^2$,
- successor $(x) = x + 1$,
- cube $(x) = x^3$.

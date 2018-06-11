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

## 15.1 Notation for composite functions

In the present example we write $f(x) = $ cube(successor(square(x))), of $f = $
cube $\circ$ successor $\circ$ square.

In general, if $f() = g(h(x))$ we write $f = g \circ h$ and say $f$ is the
_composite_ of $g$ and $h$.

**Warning:** Remember that $g \circ h$ means "do $h$ first, then $g$." $g \circ
h$ is usually different from $h \circ g$.

**Example.**

square(successor(x)) = $(x+1)^2 = x^2 + 2x + 1$

successor(square(x)) = $x^2 + 1$

**Question 15.1** Let _f_, _m_ and _s_ be the functions on the set of people
defined by

- _m(x)_ = mother of _x_
- _f(x)_ = father of _x_
- _s(x)_ = spouse of _x_

What are the following?

- $m \circ s(x)$ mother in law of _x_
- $f \circ s(x)$ father in law of _x_
- $m \circ m(x)$ grandmother (maternal) of _x_
- $f \circ m(x)$ grandfather (maternal) of _x_
- $s \circ s(x)$ _x_

**Question 15.2** Write the following as composites of square(x), sqrt(x),
successor(x) and cube(x).

(Assume that all of these have domain and codomain $\{x: x \in \mathbb{R}$ and
$x \geq 0 \}$.)

- $\sqrt{1 + x^3}$ = sqrt(successor(cube(x))) = sqrt $\circ$ successor $\circ$
  cube(x)
- $x^{\frac{3}{2}}$ = sqrt((cube(x)) = sqrt $\circ$ cube(x)
- $(1+x)^3$ = cube(successor(x)) = cube $\circ$ successor(x)
- $(1+x^3)^2$ = square(successor(cube(x))) = square $\circ$ successor $\circ$
  cube(x)

**Note** Composition of functions is associative: $(f \circ g) \circ h = f \circ
(g \circ h)$. So we don't bother with the brackets.

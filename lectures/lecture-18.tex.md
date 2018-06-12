# Lecture 18: Order Relations

## 18.1 Partial order relations

A _partial order relation R_ on a set _A_ is a binary relation with the
following three properties.

1. Reflexivity. $aRa$ for all $a \in A$.
2. Antisymmetry. $aRb$ and $bRa \Rightarrow a = b$ for all $a,b \in A$.
3. Transitivity. $aRb$ and $bRc \Rightarrow aRc$ for all $a,b,c \in A$.

For a binary relation $R$ on a set $A$.

**Antisymmetry:** For all $x,y \in A$, if $yRx$ then $x=y$.

This definition is useful for proofs but I think the contrapositive is more
intuitive.

**Antisymmetry (equivalent dfn):** For all $x,y \in A$, if $x \not = y$ then it
is not the case that $xRy$ and $yRx$.

**Antisymmetry** (For a binary relation _R_ on a set _A_)

![](images/L18-P5.png)

To prove _R_ is antisymmetric, show that; For all $x,y \in A$, if $xRy$ and
$yRx$ then $x=y$.

To prove _R_ is not antisymmetric, show that; There is some $x,y \in A$ such
that $x \not = y, xRy$ and $yRx$.

**Warning** Antisymmetric does not mean "not symmetric"!

**Question** Let _R_ be the relation _A_ pictured below. Is _R_ antisymmetric?

![](images/L18-P7-1.png)

Yes. For all $x,y \in A$, if $xRy$ and $yRx$ then $x=y$.

**Question** Let _S_ be the relation _A_ pictured below. Is _S_ antisymmetric?

![](images/L18-P7-2.png)

No. $3S5$ and $5S3$ (and $3 \not = 5)$.

**Examples.**

1. $\leq$ on $\mathbb{R}$
  Reflexive: $a \leq a$ for all $a \in \mathbb{R}$.
  Antisymmetric: $a \leq b$ and $b \leq a \Rightarrow a = b$ for all, $a,b \in
  \mathbb{R}$.
  Transitive: $a \leq b$ and $b \leq c \Rightarrow a \leq c$ for all $a,b,c \in
  \mathbb{R}$.
2. $\subseteq$ on $\wp(\mathbb{N})$.
  Reflexive: $A \subseteq A$ for all $a \in \wp(\mathbb{N})$.
  Antisymmetric: $A \subseteq B$ and $B \subseteq A \Rightarrow A = B$ for all
  $A,B \in \pw(\mathbb{N})$.
  Transitive: $A \subseteq B$ and $B \subseteq C \Rightarrow A \subseteq C$ for
  all $A,B,C \in \wp(\mathbb{N})$.
3. Divisibility on $\mathbb{N}$.
  The relation "_a_ divides _b_" on natural numbers is reflexive, antisymmetric
  and transitive.
4. Alphabetical order of words.
  Words on the English alphabet are alphabetically ordered by comparing the
  leftmost letter at which they differ.

**Definition** A binary relation _R_ on a set _A_ is a _total order relation_
if:

- it is a partial order relation; and
- for any $x,y \in A$ we have $xRy$ or $yRx$.

![](images/L18-P9.png)

**Example** $\leq$ on $\mathbb{R}$ is a total order relation (because for any
$x,y \in \mathbb{R}$ we have that $x \leq y$ or $y \leq x$).

**Example** $\subseteq$ on $\wp(\{1,2,3\})$ is not a total order relation (for
example, $\{1\} \not \subseteq \{2,3\}$ and $\{2,3\} \not \subseteq
\{1\}$).

## 18.2 Total order relations

A total order relation is a special kind of partial order relation that "puts
everything in order".

A _total order relation R_ on a set _A_ is a partial order relation that also
has the property $aRb$ or $bRa$ for all $a,b \in A$.

**Examples.**

1. $\leq \text{ and } \mathbb{R}$.
  This is a total order relation because for all real numbers _a_ and _b_ we
  have $a \leq b$ or $b \leq a$.
2. $\subseteq$ on $\wp(\mathbb{N})$.
  This is not a total order because, for example, $\{1,2\} \not \subseteq
  \{1,3\}$ and $\{1,3\} \not \subseteq \{1,2\}$.
3. Divisibility on $\mathbb{N}$.
  This is not a total order because, for example, 2 does not divide 3 and 3 does
  not divide 2.
4. Alphabetical order of words.
  This is a total order because given any two different words, one will appear
  before the other in alphabetical order.

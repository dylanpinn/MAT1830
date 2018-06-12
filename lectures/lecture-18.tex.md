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

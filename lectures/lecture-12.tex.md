# Lecture 12: Operations on Sets

There is an "arithmetic" of sets similar to ordinary arithmetic. There are
operations similar to addition, subtraction and multiplication.

## 12.1 Venn diagrams

The simple operations on sets can be visualised with the help of _Venn
diagrams_, which show sets $A,B,C,\dots$ as disks within a rectangle
representing the universal set $U$.

![](images/L12-P3.png)

## 12.2 Union

The union $A \cup B$ of sets $A$ and $B$ consists of the elements in $A$ _or_
$B$, and is indicated by the shaded region in the following Venn diagram.

![](images/L12-P4-1.png)

## 12.3 Intersection

The intersection $A \cap B$ of sets $A$ and $B$ consists of the elements in $A$
_and_ $B$, indicated by the shaded region in the following Venn diagram.

![](images/L12-P4-2.png)

**Questions**

What is $\{1,2,3\} \cup \{2,5,7\}$? = $\{1,2,3,5,7\}$

What is $\{1,2,3\} \cap \{2,3,6,7\}$? = $\{2,3\}$

What is $\{1,2,3\} \cup \{2,3\}$? = $\{1,2,3\}$

What is $\{1,2,3\} \cap \{3\}$? = $\{3\}$

What is $\{1,2,3\} \cap \{7,8\}$? = $\{\}$

## 12.4 Difference

The difference $A - B$ of sets $A$ and $B$ consists of the elements in $A$ and
_not_ in $B$, indicated by the shaded region in the following Venn diagram.

![](images/L12-P6-1.png)

The difference $U - B$ relative to the universal set $U$ is called the
_complement_ $\overline{B}$ of $B$. Here is the Venn diagram of $\overline{B}$.

![](images/L12-P6-2.png)

## 12.5 Symmetric difference

The union of $A-B$ and $B-A$ is called the _symmetric difference_ $A \triangle
B$ of $A$ and $B$.

![](images/L12-P7.png)

$A \triangle B$ consists of the elements of _one_ of $A,B$ but not the other.

It is clear from the diagram that we have not only

$$A \triangle B = (A-B) \cup (B-A)$$

but also

$$A \triangle B = (A \cup B) - (A \cap B)$$

**Questions**

What is $\{1,2,3\} = \{2,5,7\}$? = $\{1,3\}$

What is $\{1,2,3\} = \triangle \{2,3,6,7\}$? = $\{1,6,7\}$

What is $\{2,3\} - \{1,2,3\}$? = $\{\}$

What is $\{1,2,3\} \triangle \{3\}$? = $\{1,2\}$

What is $\{1,2,3\} - \{7,8\}$? = $\{1,2,3\}$

**Question** Let $S = \{-2,-1,0,1,2\} \cap \mathbb{N}$. If we know that $S
\subseteq (\{-1,0,1\} \cup T)$, what can we say about $T$?

- **A.** $T$ must equal $\{2\}$
- **B.** $T$ must equal $\mathbb{N}$
- **C.** $T$ can be any set such that $-2 \in T$
- **D.** $T$ can be any set such that $2 \in T$

**Answer**

Note $S = \{0,1,2\}$. So for $S$ to be a subset of $\{-1,0,1\} \cup T$ we need
that each of 0,1,2 is an element of $\{-1,0,1\} \cup T$. This is definitely true
for 0 and 1 because they're in $\{-1,0,1\}$. So we just need that 2 be an
element of $T$. So **D**.

**Question 12.1** Draw a Venn diagram for $A \cap \overline{B}$. What is another
name for this set?

![](images/L12-P10.png)

So $A \cap \overline{B} = A - B$.

**Question 12.2** Show that $\overline{A \cup B} = \overline{A} \cap
\overline{B}$ is true using Venn diagrams.

![](images/L12-P13.png)

![](images/L12-P14.png)

So $\overline{A \cup B} = \overline{A} \cap \overline{B}$

**Question** Show that $\overline{A \cup B} = \overline{A} \cap \overline{B}$ is
true using logic.

$$\begin{align}
  x \in \overline{A \cup B} &\equiv \neg(x \in A \cup B) \\
  &\equiv \neg((x \in A) \lor (x \in B)) \\
  &\equiv \neg(x \in ) \land \neg (x \in B) \\
  &\equiv (x \in \overline{A}) \land (x \in \overline{B}) \\
  &\equiv x \in \overline{A} \cap \overline{B}
\end{align}$$

So $\overline{A \cup B} = \overline{A} \cap \overline{B}$

**Question 12.3** Find whether $A \cap (B \triangle C) = (A \cap B) \triangle (A
\cap C)$ is true using Venn diagrams.

![](images/L12-P17.png)

So $A \cap (B \triangle C) = (A \cap B) \triangle (A \cap C)$

## 12.6 Ordered Pairs

For sets we have $\{a,b\} = \{b,a\}$.

But sometimes order is important.

So we defined ordered pairs $(a,b)$, where the order is significant: $(a,b) \not
= (b,a)$.

We can of course can also define ordered triples $(a,b,c)$ etc.

## 12.7 Cartesian product

The set of ordered pairs

$$A \times B = \{(a,b) : a \in A \text{ and } b \in B \}$$

is the _Cartesian product_ of sets $A$ and $B$.

Remember the elements of $A \times B$ are always _ordered pairs_.

**Question** If $A = \{0,1\}$ and $B = \{1,2,3\}$ what is $A \times B$?

$$\{(0,1),(0,2),(0,3),(1,1),(1,2),(1,3)\}$$

**Question** If $A = \{0,1\}$ what is $A \times \mathbb{N}$?

$$\{(0,0),(1,0),(0,1),(1,1),(0,2),(1,2),\dots\}$$

**Question** Let $S = \{-1,1\} \times \{0,1,2\}$. Is $(-1,1) \in S$? Is $(0,1)
\in S$?

- **A.** Yes, yes
- **B.** Yes, no
- **C.** No, yes
- **D.** No, no

**Answer**

$(-1,1) \in S$ because $-1 \in \{-1,1\}$ and $1 \in \{0,1,2\}$.
$(0,1) \not \in S$ because $0 \not \in \{-1,1\}$. So **B**.

## 12.8 A x B and Multiplication

If $A$ has $|A|$ elements and $B$ has $|B|$ elements, then $A \times B$ has $|A|
\times |B|$ elements.

Similarly, if $L$ is a line of length $l$, and $W$ is a line of length $w$, then
$L \times W$ is a rectangle of area $l \times w$. In fact, we call it an "$l
\times w$ rectangle." This is probably the reason for using the $\times$ sign,
and for calling $A \times B$ a "product".

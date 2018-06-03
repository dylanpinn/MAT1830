# Lecture 11: Sets

**Sets - why should you care?**

- Sets are an important data structure when programming.
- Sets are very important concepts CS and maths.
- Set notation is used a lot in writing about CS and maths.
- The standard approach to building maths up from logic is based on sets.

Sets are vital in expressing mathematics formally and are also very important
data structures in computer science.

A set is basically just an unordered collection of distinct objects, which we
call its _elements_ or _members_. Note that there is no notion of order for a
set, even though we often write down its elements in some order for convenience.
Also, there is no notion of multiplicity: an object is either in a set or not -
it cannot be in the set multiple times.

Sets _A_ and _B_ are equal when every element of _A_ is an element of _B_ and
vice-versa.

## 11.1 Set notation

- $x \in S$ means that _x_ is an element of set _S_.
- $\{x_1, x_2, x_3, \dots \}$ is the set with elements $x_1, x_2, x_3, \dots$
- $\{x : P(x) \}$ is the set of all _x_ with property _P_.

**Example.**

$$17 \in \{ x : x \text{ is prime } \} = \{2,3,5,7,11,13,\dots\}$$
$$\{1,2,3\} = \{3,1,2\}$$
$$\{1,1,1\} - \{1\}$$

For a finite set $S$, we write $|S|$ for the number of elements of $S$.

**Question:** Let $S = \{a, \{a\}, \{b\}, \{a,b,c\}\}$.

Is $a \in S$? Yes

Is $b \in S$? No

**Question:** Is $\{a\} \in S$? Is $\{a,b\} \in S$?

Answer: Yes, No.

**Question:**

Let $R = \{a,b,c\}$. What is $|R|$? **3**

Let $S = \{a,\{a\},\{b\},\{a,b,c\}\}$. What is $|S|$? **4**

Let $T = \{0,1,2,\dots,100\}$. What is $|T|$? **101**

What is $|\{\}|$? **0**

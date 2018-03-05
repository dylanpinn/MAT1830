# Lecture 3: Congruences

Even integers are those that can be written as $2k$ for some integer $k$. The
odd integers are those that can be written as $2k + 1$ for some integer $k$.

We can split the integers into three classes; those that are $3k$ for some
integer $k$, those that are $3k + 1$ for some integer $k$, and those that are
$3k + 2$ for some integer $k$.

These classes also have particular properties. For example, the some of an
integer in the second class and an integer in the third class will always be in
the first class.

We don't have to stop with 3. We could divide integers into 4 different classes
according to their remainders when divided by 4, and so on.

## 3.1 Congruences

Let $n$ be a positive integer and let $a$ and $b$ be integers.

Basically $a \equiv b$ (mod $n$) means that $a$ and $b$ have the same remainder
when you divide them by $n$.

**Definition** We say $a \equiv b$ (mod $n$) if $n$ divides $a - b$.

**Equivalent definition** We say $a \equiv b$ (mod $n$) if $a = kn + b$ for some
integer $k$.

Note we are talking about "congruence modulo _n_" as a relation here, which is
not quite the same as using a mod operation.

### Questions

Is $25 \equiv 9$ (mod $4$)? Yes (because $4$ divides $25 - 9$)

Is $9 \equiv 16$ (mod $3$)? No (because $3$ doesn't divide $16 - 9$)

What integers are congruent to 3 modulo 4?

$$\dots, -9, -5, -1, 3, 7, 11, \dots$$

Is $6 \equiv 3$ (mod $3$)? Yes

Is $9 \equiv 18$ (mod $8$)? No (because $8$ doesn't divide $18 - 9$)

Is $5x + 6 \equiv 2x$ (mod $3$)? Yes (because $3$ does divide $5x + 6 - 2x = 3x
+ 6$)

## 3.2 Working with congruences

When working with congruences modulo some fixed integer $n$, we can "substitute
in" just like we can with equalities.

```
If a ≡ b (mod n) and b ≡ c (mod n), then a ≡ c (mod n).
```

We can add, subtract and multiply congruences just like we can with equations.

```
If a1 ≡ b1 (mod n) and a2 ≡ b2 (mod n), then
* a1 + a2 ≡ b1 + b2 (mod n)
* a1 - a2 ≡ b1 - b2 (mod n)
* a1a2 ≡ b1b2 (mod n)
```

### Examples

Suppose we know that $x \equiv 3$ (mod $4$) and $y \equiv 2$ (mod $4$).

Adding these, we see $x + y \equiv 5$ (mod $4$).

So $x + y \equiv 1$ (mod $4$) (because $5 \equiv 1$ (mod $4$)).

Suppose we know that $3x \equiv 1$ (mod $5$) and $2x \equiv 4$ (mod 5).

Subtracting the second from the first, we see $x \equiv -3$ (mod 5)

So $x \equiv 2$ (mod 5) (because $-3 \equiv 2$ (mod 5))

### Question 3.2 (one part)

**Fact.** If $a_{1} \equiv b_{1}$ (mod $n$) and $a_{2} \equiv b_{2}$ (mod $n$),
then $a_1 + a_2 \equiv b_1 + b_2$ (mod $n$).

**Proof.**

Because $a_1 \equiv b_1$ (mod $n$), $n$ divides $a_1 - b_1$

This means that $a_1 - b_1 = k_{1}n$ for some integer $k_1$.

Because $a_2 \equiv b_2$ (mod $n$), $n$ divides $a_2 - b_2$

This means that $a_2 - b_2 = k_{2}n$ for some integer $k_2$.

So, $(a_1 - b_1) + (a_2 - b_2) = k_{1}n + k_{2}n$.

So, $(a_1 + a_2) - (b_1 + b_2) = (k_1 + k_2)n$.

Because $k_1 + k_2$ is an integer, this means $n$ divides $(a_1 + a_2) - (b_1 +
b_2)$.

So $a_1 + a_2 \equiv b_1 + b_2$ (mod $n$).

### Substituting in

In the two most common situations, "substituting in" using congruences is legal:

**Fact:**

If $a \equiv b + c$ (mod $n$) and $c \equiv d$ (mod $n$), then $a
\equiv b + d$ (mod $n$).

**Proof:**

Because $c \equiv d$ (mod $n$) and $b \equiv b$ (mod $n$), we have $b + c \quiv
b + d$ (mod $n$).

So because $a \equiv b + c$ (mod $n$), we have $a \equiv b + d$ (mod $n$).

**Fact:**

If $a \equiv bc$ (mod $n$) and $c \equiv d$ (mod $n$), then $a \equiv bd$
(mod $n$).

**Proof:**

Because $c \equiv d$ (mod $n$) and $b \equiv b$ (mod $n$), we have $bc \equiv
bd$ (mod $n$).

So because $a \equiv bc$ (mod $n$), we have $a \equiv bd$ (mod $n$).

But you can't substitute into exponents, logarithm bases, etc:

**Example:**

We know $6 \equiv 1$ (mod 5), but $2^6 \not\equiv 2^1$ (mod 5).

In some situations we can also "divide through" a congruence by an integer.

If a ≡ b (mod n) and d divides a, b and n, then

$$\frac{a}{d} \equiv \frac{b}{d} (\text{mod} \frac{n}{d})$$

**Question:**

If we know that $2x + 4y \equiv 4$ (mod 8) and $y \equiv 3$ (mod 4) what can we
say about $x$?

**Answer:**

$x + 2y \equiv 2$ (mod 4) (dividing the first congruence by 2)

$x + 6 \equiv 2$ (mod 4) (substituting $y \equiv 3$ (mod 4))

$x \equiv -4$ (mod 4) (subtract 6 from both sides)

$x \equiv 0$ (mod 4) (because $-4 \equiv 0$ (mod 4))

## 3.3 Solving linear congruences

Think of a congruence like $7x \equiv 5$ (mod 9). This will hold if 9 divides
$7x - 5$ or in other words if there is an integer $y$ such that $7x - 5 = 9y$.
So to solve our original congruence we can find an integer solution to $7x - 9y
= 5$.

Some congruences don't have solutions. For example, there is no soltuion to $10x
\equiv 6$ (mod 20) because there are no integers $x$ and $y$ such that $10x -
20y = 6$.

We can find an expression for all the integers $x$ that satisfy a congruence
like $ax \equiv b$ (mod n) in the following way:

1. Find $d = gcd(a, n)$
2. If $d$ doesn't divide $b$, then there are no solutions.
3. If $d$ divides $b$, then divide through the congruence by $d$ to get an
   equivalent congruence
   $\frac{a}{d}x \equiv \frac{b}{d}(\text{mod}\frac{n}{d})$.
4. Find integers $x'$ and $y'$ such that $\frac{a}{d}x' - \frac{n}{d}y' =
   \frac{b}{d}$. The integers $x$ that satisfy the original congruence are
   exactly those for which $x \equiv x^\prime$ (mod $\frac{n}{d}$).

### Question 3.3

Find an expression for all the integers x that satisfy $9x \equiv 36$ (mod 60).

First calculate gcd(9, 60) = 3.

3 does divide 36 so there are solutions.

Divide through by 3 to get $3x \equiv 12$ (mod 20).

We now want to find $x'$ and $y'$ such that $3x' - 20y' = 12$.

$x' = 4$ and $y' = 0$ work.

So the integers $x$ that satisfy $9x \equiv 36$ (mod 60) are exactly those for
which $x \equiv 4$ (mod 20).

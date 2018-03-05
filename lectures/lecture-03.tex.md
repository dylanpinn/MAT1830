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

## 3.w Working with congruences

When working with congruences modulo some fixed integer $n$, we can "substitute
in" just like we can with equalities.

```
If a ≡ b (mod n) and b ≡ c (mod n), then a ≡ c (mod n).
```
